## Enums

Esse repositorio tem como objetivo mostrar a utilização de Enums em Java.

---

## O que são Enums?

Enums são uma lista de constantes que são utilizadas para representar um conjunto de valores fixos. Eles são utilizados para representar valores que não mudam, como os dias da semana, meses do ano, etc.

---

## Exemplos de Enums

```java
public enum DiasDaSemana {
    DOMINGO,
    SEGUNDA,
    TERCA,
    QUARTA,
    QUINTA,
    SEXTA,
    SABADO
}
```

```java
public enum MesesDoAno {
    JANEIRO,
    FEVEREIRO,
    MARCO,
    ABRIL,
    MAIO,
    JUNHO,
    JULHO,
    AGOSTO,
    SETEMBRO,
    OUTUBRO,
    NOVEMBRO,
    DEZEMBRO
}
```

---

## Utilização de Enums

```java
public class Main {
    public static void main(String[] args) {
        DiasDaSemana dia = DiasDaSemana.SEGUNDA;
        MesesDoAno mes = MesesDoAno.JANEIRO;

        System.out.println("Dia da semana: " + dia);
        System.out.println("Mês do ano: " + mes);
    }
}
```

---

## Conclusão

Enums são uma forma de representar valores fixos em Java. Eles são muito úteis para representar valores que não mudam, como os dias da semana, meses do ano, etc.
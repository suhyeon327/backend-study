# TypeConversion

## String → Primitive

```java
Integer.parseInt("123");      // int
Long.parseLong("123");        // long
Double.parseDouble("123.45"); // double
Float.parseFloat("123.45");   // float
Boolean.parseBoolean("true"); // boolean
```

## Primitive → String

```java
String.valueOf(123);
String.valueOf(123L);
String.valueOf(123.45);
String.valueOf(true);
```

## Wrapper → String

```java
Integer.toString(123);
Long.toString(123L);
Double.toString(123.45);
```

## char ↔ 숫자

```java
int n = c - '0';
```

```java
char c = (char) ('0' + 7);
```

## String ↔ char

```java
char c = str.charAt(0);
```

```java
char[] arr = str.toCharArray();
```

```java
String s = String.valueOf(c);
```

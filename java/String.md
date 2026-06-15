# String

## 문자열 길이

```java
str.length();
```

## 특정 위치 문자 가져오기

```java
str.charAt(0);
```

## 부분 문자열

```java
str.substring(1, 3);
```

## 문자열 포함 여부

```java
str.contains("abc");
```

## 문자열 치환

```java
String str = "Java Java";
str.replace("Java", "Spring");

// Spring Spring
```

```java
str.replaceAll("[aeiou]", "");

// ppl
```

```java
String str = "Java Java";
str.replaceFirst("Java", "Spring");

// Spring Java
```

차이점
- replace(): 문자열 그대로 비교하여 치환
- replaceAll(): 정규표현식 사용 가능
- replaceFirst(): 첫 번째 일치 항목만 치환

## 특정 문자열이 시작되는 위치(인덱스값)

```java
str.indexOf("Java");
```

## 반복

```java
str.repeat(반복횟수)
```

## 구분자로 나누기

```java
String[] arr = str.split(구분자, limit);
```

- limit > 0: 최대 limit개로 분할
- limit = 0: 뒤의 빈 문자열 제거
- limit < 0: 뒤의 빈 문자열 유지, 음수면 동일하게 동작하여 보통 -1를 씀

## 앞뒤 공백 제거

```java
my_string.trim();
```

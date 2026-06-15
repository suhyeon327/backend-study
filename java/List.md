# List

## 생성

```java
List<Integer> list = new ArrayList<>();
```

## 추가

```java
list.add(1);
```

## 조회

```java
list.get(0);
```

## 크기

```java
list.size();
```

## 삭제

```java
list.remove(0);
```

## 배열 -> List 변환

```java
String[] data = {"A", "B", "C"};

ArrayList<String> list = new ArrayList<>(Arrays.asList(data));
```

## List -> 배열 변환

```java
list.toArray(new String[0]);
```

```java
String[] arr = list.toArray(new String[list.size()]);
```

## 구분자로 문자열 연결

```java
ArrayList<String> list = new ArrayList<>(Arrays.asList("138", "129", "142"));
String result = String.join(",", list);
```

## 정렬

```java
import java.util.Comparator;

list.sort(Comparator.naturalOrder());   // 오름차순
list.sort(Comparator.reverseOrder());   // 내림차순
```

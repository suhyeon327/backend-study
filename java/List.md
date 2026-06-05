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

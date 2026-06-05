# Set

## 생성
```java
HashSet<String> set = new HashSet<>();
```

## 교집합

```java
set.retainAll(set2);
```

## 합집합

```java
set.addAll(set2);
```

## 차집합

```java
set.removeAll(set2);
```

## 값 추가

```java
set.add("Java");
```

## 여러 값 추가

```java
set.addAll(Arrays.asList("To", "Java"));
```

## 값 제거

```java
set.remove("Java");
```

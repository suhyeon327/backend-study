# Map

```java
HashMap<String, String> map = new HashMap<>();
```

## key, value 추가

```java
map.put("people", "사람");
```

## key에 해당하는 value 가져오기

```java
map.get("people")
```

```java
map.getOrDefault("java", "자바")
```
->  key가 없을 때 null 대신 기본값 얻는 방법

## key 포함 여부

```java
map.containsKey("people")
```

## 항목 삭제

```java
map.remove("people")
```
-> value 값 반환

## 요소의 개수

```java
map.size()
```

## 모든 key 반환

```java
map.keySet()
```

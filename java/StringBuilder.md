# StringBuilder

## 개념

문자열을 효율적으로 수정하기 위한 클래스이다.

String은 한 번 생성되면 변경할 수 없는(Immutable) 객체이기 때문에 문자열을 계속 이어붙이면 새로운 객체가 반복적으로 생성된다.

StringBuilder는 내부 버퍼를 사용하여 문자열을 수정하므로 성능이 더 좋다.

---

## 생성

```java
StringBuilder sb = new StringBuilder();
```

## 문자열 추가

```java
sb.append("abc");
```

## 문자열 뒤집기

```java
sb.reverse();
```

## String으로 변환

```java
sb.toString();
```

## 특정 문자 수정

```java
sb.setCharAt(인덱스, 새로운 문자);
```

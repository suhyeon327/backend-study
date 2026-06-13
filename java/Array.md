# Array

## 생성

```java
String[] arr = new String[배열의 크기];
```

## 정렬

```java
import java.util.Arrays;

Arrays.sort(arr)
```

## 출력

```java
Arrays.toString(arr)
```

## 복사

```java
Arrays.copyOf(원본 배열, 복사할 길이)
```

- 원본 배열이 입력한 길이보다 클 경우 입력한 길이 이후의 인덱스는 제거되어 copy
- 원본 배열이 입력한 길이보다 작을 경우 원본 베열에서 존재하지 않는 인덱스 이후의 값은 배열의 타입 기본값으로 초기화되어 copy

```java
Arrays.copyOfRange(원본 배열, 시작 인덱스, 끝 인덱스)
```

- 원본 배열의 길이가 끝 인덱스보다 작을 경우 끝 인덱스 이후의 값은 배열의 타입 기본값으로 초기화되어 copy
- 시작 인덱스가 원본 배열의 길이보다 크면 exception 발생

```java
System.arraycopy(복사할 배열, 복사 시작 인덱스, 붙여넣을 배열, 붙여넣기 시작 인덱스, 길이)
```

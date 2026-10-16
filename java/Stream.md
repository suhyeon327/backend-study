# Stream

## import

```java
import java.util.stream.IntStream;
```

## 배열 합

```java
IntStream.of(arr).sum();
```

```
Arrays.stream(arr).sum();
```

## 배열 합치기

```java
IntStream.concat(Arrays.stream(arr1),
                 Arrays.stream(arr2))
         .toArray();
```

## List -> int[]

```java
answer.stream()
      .mapToInt(Integer::intValue)
      .toArray();
```

## 배열 연산
```java
IntStream.range(0, a.length).map(index -> a[index] * b[index]).sum();
```

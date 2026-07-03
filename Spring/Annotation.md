# Annotation

## 개념

Java 어노테이션을 활용하여 빈 관리, 의존성 주입, 트랜잭션 관리 등 다양한 기능을 자동으로 처리한다.

주로 '컴포넌트 스캔', '의존성 주입', '애플리케이션 설정' 등을 위한 기능을 제공한다.

## 역할

- 설정: XML 설정 없이 어노테이션만으로 설정 가능
- 자동화: @Autowired를 사용해 의존성 자동 주입
- 행동 제어: @Transactional, @Cacheable 같은 어노테이션으로 기능 추가
- 메타데이터 제공: 코드가 어떤 의미를 가지는지 설명

## 기본 어노테이션

- @Component: Spring이 관리하는 일반적인 객체를 정의
- @Controller: MVC에서 컨트롤러 역할을 하는 클래스 지정
- @Service: 서비스 역할을 하는 클래스 지정 (비지니스 로직)
- @Repository: 데이터베이스 관련 작업을 하는 클래스 지정

## 의존성 주입 어노테이션

- @Autowired: 필요한 객체를 자동으로 주입 (DI)
- @Qualifier("이름"): 주입할 객체를 특정 이름으로 지정
- @Inject: @Autowired와 같은 역할 (Java 표준)
- @Value("${설정값}"): application.properties의 값을 주입

## 요청 매핑 어노테이션
- @RequestMapping("/경로"): 특정 URL과 메서드를 연결
- @GetMapping("/경로"): GET 요청을 처리
- @PostMapping("/경로"): POST 요청을 처리
- @PutMapping("/경로"): PUT 요청을 처리
- @DeleteMapping("/경로"): DELETE 요청을 처리

## 트랜잭션 어노테이션
- @Transactional: 트랜잭션을 관리하여 오류 발생 시 자동 롤백

## 기타 어노테이션

- @RestController: @Controller + @ResponseBody (JSON 반환)
- @ResponseBody: 메서드의 반환값을 JSON으로 변환
- @PathVariable: URL 경로 변수 값을 가져옴
- @RequestParam: GET 또는 POST 요청의 파라미터 값을 가져옴
- @ExceptionHandler: 예외가 발생했을 때 특정 메서드에서 처리

## Lombok 어노테이션
- @Getter, @Setter : Java Bean 규약에 있는 setter, getter를 생성
- @ToString : Object에 기본 구현된 ToString 대신 객체의 값 보여주는 ToString을 생성
- @NoArgsConstructor: 인자가 없는 기본 생성자를 생성
- @AllArgsConstructor:모든 프로퍼티를 인자로 갖는 생성자를 생성
- @RequiredArgsConstructor : 필수 인자를 가진 생성자를 생성
- @Data : @Getter/@Setter/@ToString/@EqualsAndHashCode/@RequiredArgsContructor을 포함
- @Slf4j : 객체에 맞는 로그를 췹게 출력하는걸 도와줌
- @UtilityClass : 유틸리티 성 클래스의 생성자를 private으로 만들어서 인스턴스가 생성되지 못하게 함

### @NoArgsConstructor, @AllArgsConstructor, @RequiredArgsConstructor


출처: https://itconquest.tistory.com/entry/Spring-Boot-Annotation-개념-이해하기 [개발자일지:티스토리]

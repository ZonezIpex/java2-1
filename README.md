# 신민수 학번 202130413

## 3월 29일 강의

## 3월 22일 강의
맨위 중간 검색기 클릭
명령어 : 컨트롤 + 쉬프트 + p
--> java pro까지만 검색 
--> java create java project 선택 
--> 파일지정

1. 자바 --> .java파일은 버전이 모두 다르고 사용환경 (ex: 윈도우, 맥, 리눅스 등)
2. 모두 다르기 때문에 윈도우에서 작업한 파일은 맥에서 작동하지 않는다.
3. 따라서 .java파일을 .class 파일로 변환하여 저장하면 모든 플랫폼에서 작업이 가능하다.

이 과정에 필요한 것은 "자바 버추얼 머신( 통칭: JVM )" 이다.

" 개발하는 과정에서 필요한 것은 ( JDK ) 이다 "
" 사용하는 입장에서 필요한 것은 ( JRE ) 이다 "

서블릿은 웹브라우저에서 실행되는 자바스킄립트 코드와 통신

[ 자바의 특성 ]
1. 플랫폼 독립성
    <1>하드웨어, 운영체제에 종속되지 않는 바이트 코드로 플랫폼 독립성
2. 객체지향
    <1>캡슐화, 상속, 다형성 지원
3. 소스와 클래스 파일
    <1>하나의 소스파일에 여러 클래스 작성 가능
        ↑ public 클래스는 하나만 가능
    <2>소스파일의 이름과 public으로 선언된 클래스 이름은 같아야함
    <3>클래스 파일에는 하나의 클래스 파일만 존재
        ↑ 다수의 클래스를 가진 자바 소스를 컴파일하면 클래스마다 별도 클래스 파일 생성
4. 실행코드 배포
    <1>한 개의 class 파일 또는 다수의 class로 구성
    <2>여러 폴더에 걸쳐 다수의 클래스 파일로 구성된 경우 jar압축 파일로 제공
    <3>하나의 클래스 파일에 두 개 이상의 main()매소드가 있을 수 없음
5. 패키지
    <1>서로 관련 있는 여러 클래스를 패키지로 묶어 관리
    <2>패키지는 폴더개념으로 존재
6. 멀티스레드
    <1>여러 스레드를 동시에 할당 x

7. 가비지 컬렉션
    <1>자바 언어는 메모리 할당 기능은 있어도 메모리 변환 기능은 없다

[ 자바의 특성 2 ]
1. 실시간 응용프로그램에 부적합
    <1>실행 도중 예측할 수 없는 시점에 기바지 컬랙션 실행 때문
2. 자바 프로그램은 안전
    <1>타입 체크 일격
    <2>물리적 주소를 사용하는 경우가 존재
3. 프로그램 작성 쉬움
    <1>자바언어는 개발하는 환경에 유리
4. 실행속도 개선을 위한 JIT 컴파일러 사용
    <1>실행속도가 개선됨

[ 식별자 ]
1. 클래스, 변수, 상수, 메소드 등에 붙이는 이름
2. 식별자의 원칙
 <1>특수문자와 공백 또는 탭은 식별자로 사용이 불가능하다
 <2>유니코드 문자 사용가능, 한글도 사용가능
 <3>자바언어의 키워드는 식별자로 사용불가
 <4>식별자의 첫 번째 문자는 숫자로 불가능

[ 자바 데이터 타입 종류 ]
boolean
char
byte
short
int
long
float
double

[ 리터럴과 정수 리터럴 ]
1. 리터럴
    <1>프로그램에서 직접 표현한 값
    <2>정수, 실수, 문자, 논리, 문자열 리터럴이 있음
2. 정수 리터럴
    <1>10진수, 16진수, 8진수 등..

[ 실수 리터럴 ]
1. 소수점 형태나 지수 형태로 표현한 실수
    <1>12, 12.0, 12.00, 12.000
2. 실수 타입 리터럴은 double로 표현

[ 문자 리터럴 ]
1. 단일 인용부호 (**)로 문자 표현
2. 특수문자 리터럴은 백슬래시| ( \ ) 로 표현 함

[ 상수 ]
1. 상수 선언
    <1>final 키워드 사용
    <2>선언 시 초기값 지정
    <3>실행 중 값 변경 불가

[ var 키워드 ]
* JAVA 10 부터 도입됨 *
1. 기존 변수선언 방식 : 변수의 타입 반드시 지정
2. var키워드
    <1>타입을 생략하고 변수 선언 가능
    <2>컴파일러가 추론하여 변수 타입 결정
    <3>변수 선언 시 초기값이 주어지지 않으면 컴파일 오류

[ 타입 변환 ]
1. 한 타입의 값을 다른 타입의 값으로 변환

[ 자동 타입 변환 ]
1. 컴파일러에 의한 월래의 타입보다 큰 타입으로 자동 변환

## 3월 15일 강의
내용 정리

올리지마세요!!!!!!

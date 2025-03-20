# 최원재 202230137
## 3월 20일(3주차)
# 2교시

프로그래밍 언어의 진화
고급언어, 어셈블리어언어, 객체지향언어 쓰임새

* 프로그래밍과 컴파일<br>
자바 -> .java -> .class
c -> .obj -> .exe

* 자바의 태동<br> 
가전제품에 들어갈 소프트웨어를 위해 개발
목적 : 플랫폼 호환성 문제 해결, 플랫폼 독립적인 언어 개발, 메모리사용량이 적고 여러제품에 적용

* 자바 JVM과 자바 실행 환경<br>
바이트 코드(.class)
자바 jvm에서 실행가능한 바이너리 코드
jVM(Java Virtual Machine)
각기 다른 플랫폼에 맞는 JVM제공

# 3교시
* 자바 응용프로그램 실행 환경<br>
JVM + Java API

* Java의 네이밍 방식<br>
내부 버전 표기 1.x.x 형태로 유지중

모듈 : 자바패키지들과 이미지 XML파일 등의 자원들을 묶은 단위

* 자바의 특징<br>
-실행 코드 배포 : 한 개의 class파일 또는 다수의 class 파일로 구성<br>
-패키지 : 서로 관련 있는 여러 클래스를 패키지로 묶어 관리<br>
-멀티스레드 : 여러 스레드의 동시 수행 환경 지원 <br>
자바는 운영체제의 도움없이 자체적으로 멀티스레드 지원





### README 파일 편집

# 최원재 202230137
## 3월 13일(2주차)
소스 컨트롤을 왜 사용하고 이용해야 하는지 그리고 여러 기본 태그들을 배움

### README 파일 편집 

# h1 tag
## h2
### h3
#### h4
##### h5
###### h6

---

* 가가가
- 나나나

1. 나나나
2. 가가가
7. 다다다

```java
import java.util.Scanner;

public class HelloWorld {

    public static void main(String[] args) {

        // Creates a reader instance which takes
        // input from standard input - keyboard
        Scanner reader = new Scanner(System.in);
        System.out.print("Enter a number: ");

        // nextInt() reads the next integer from the keyboard
        int number = reader.nextInt();

        // println() prints the following line to the output screen
        System.out.println("You entered: " + number);
    }
}
```

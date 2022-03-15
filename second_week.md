# 2주차 내용정리
## apache-tomcat
1. locathost:8080 접속
2. servlet을 정의하고 class 이름 정의, mapping을 통해 접근해야 할 url 패턴 지정(가상의 url 위치를 가르키는 것 처럼 구현, 실제 서버는 class파일을 실행 : WEB-INF에 web.xml에 해당하는 파일을 classes에서 실행)
  - sevlet 배포 및 설정 : Tomcat 설치 폴더 > webapps 폴더에서 작업
    - ex> /webapp/mytest/WEB-INF/classes/HelloServlet.class
- \work\Catalina\localhost\mytest\org\apache\jsp
  - > `.java` 는 jsp파일의 코드를 변환한 소스파일, `.class`는 컴파일 된 파일
## .jsp 에서의 html
* `<%@ page import="java.util.*" %>` : 자바 소스 파일에서 import와 같은 역할
* `<%= new Date() %>` : 자바 소스 파일에서 `pw.println("Server Time: " + new Date());` 와 같은 역할
 
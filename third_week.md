# Web Project 시작하기
## Servlet vs Servlet Container
- Servlet:  클라이언트가 서버에게 요청한 서비스를 처리하기 위한 Java 기반의 기술이나 해당 서비스를 처리하는 Java class (혹은 객체)를 의미
  - 웹 초창기에 CGI 기반의 동적 페이지 생성 방식의 성능 문제로 인해 도입됨
- Servlet Container: Servlet을 hosting하는 서버 측의 실행 환경 (dynamic함)
  - Servlet/JSP 지원 및 생명주기 관리, 멀티스레딩, 보안 관리 등의 부가 기능 제공
## applet vs servlet
- applet : client-side
- sevlet : sever-side

## CGI
- 웹 서버와 외부 helper 프로그램들 간의 데이터 교환을 위한 규격
- servlet보다 성능 및 보안 상의 장점이 떨어짐
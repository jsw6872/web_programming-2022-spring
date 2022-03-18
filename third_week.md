# Web Project 시작하기
## Servlet vs Servlet Container
- Servlet:  클라이언트가 서버에게 요청한 서비스를 처리하기 위한 Java 기반의 기술이나 해당 서비스를 처리하는 Java class (혹은 객체)를 의미
  - 웹 초창기에 CGI 기반의 동적 페이지 생성 방식의 성능 문제로 인해 도입됨
- Servlet Container: Servlet을 hosting하는 서버 측의 실행 환경 (dynamic함)
  - Servlet/JSP 지원 및 생명주기 관리, 멀티스레딩, 보안 관리 등의 부가 기능 제공
## applet vs servlet
- applet : client-side
- sevlet : sever-side
  - applet과 sevlet는 90년대 초반 부터 후반까지 사용한 기술임
  - 현재는 client-side는 vue.js , react 등 컴포넌트 기반의 JS 프레임워크가, sevlet에 해당하는 기술등은 API 형태로 진화되고 있음
  - 이는 기본적인 코드의 진화방향과도 유사한데 일종의 각자의 역할을 명확히 하여 클라이언트 사이드는 화면 상 표현에 집중하고, 서버사이드는 데이터의 관리 및 전송에 집중하는 것으로 발전하고 있음  

## CGI
- 웹 서버와 외부 helper 프로그램들 간의 데이터 교환을 위한 규격
- servlet보다 성능 및 보안 상의 장점이 떨어짐

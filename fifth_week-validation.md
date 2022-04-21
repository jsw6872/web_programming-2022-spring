# 사용자 입력 값의 검증
Client-side validation의 유무와 관계없이 Server-side validation이 필수적
- Client
  - Browser에서 data의 전송 전에 입력을 추가적으로 검증
  - Browser의 기본(확장) 기능을 통하거나, JavaScript와 같은 script 등을 활용
  - 네트워크 트래픽을 유발하지 않으며, 사용자 입력 화면에 머물면서 기존 입력 값을 유지한 채로 검증이 이루어지므로 훨씬 바람직
  - 주로, 입력 형태(pattern)나 입력 값의 존재 여부와 같은 1차적인 검증에 활용
- Server
  - Servlet/JSP를 통해 진행됨, 필수적인 과정
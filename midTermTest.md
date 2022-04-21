# 중간 정리
## 프로젝트 생성
1. new project
2. Web
3. dynamic Web Project

## Servlet 및 JSP
### servlet
- Servlet은 web.xml을 통해 매핑 필요
- form에 actions=에서 .do
### JSP
- JSP는 매핑 필요 X
- form에 actions=에서 .jsp를 통해
- 로직 작업은 Servlet

## file upload
- file 타입은 request.getParts()를 통해 접근 
- 처리후 결과 HTML 은 JSP로 처리

## validation
- input 태그에 pattern 등으로 설정

## regular expression
- /bac/ : ‘bac’ 글자 자체의 포함 패턴, ‘bac’, ‘back’, ‘rollback’, …
- /ba*c/ : ‘b’와 ‘c’ 사이에 ‘a’가 0번 이상 발생 가능: ‘bc’, ‘bac’, ‘baac’, …
- /ba+c/ : ‘b’와 ‘c’ 사이에 ‘a’가 1번 이상 발생 가능: ‘bac’, ‘baac’, …
- /^Ab*/ : 첫 글자가 ‘A’로 시작함, ‘A’, ‘Ab’, ‘Abb’, … (‘aA’, ‘ A’ 등은 아님)
- /t$/ : 마지막 글자가 ‘t’로 끝남, ‘pat’, ‘stat’, … (‘ate’, ‘date’ 등은 아님)
- \w, \d : ‘_’를 포함하는 alphanumeric 글자, 아라비아 숫자에 각각 대응됨
  - 각각 [A-Za-z0-9_] 과 [0-9]와 동일함
- \W, \D : \w와 \d가 아닌 임의의 글자에 대응됨. [^A-Za-z0-9_] 및 [^0-9]와 동일
  - /\D/ : ‘s2’, ‘a1’, …
  - /\W/ : ‘50%’, ‘Émanuel’, …

## javascript event handler
- document.formName.inputName.select(): inputName 요소의 값을 전체 선택
- document.formName.inputName.focus(): 입력 focus를 지정해 줌
- document.formName.inputName.value: inputName의 (문자열) 값
- document.formName.inputName.value.length: 문자열 값의 길이
- document.formName.inputName.value.charAt(x): 문자열의 x번째 글자
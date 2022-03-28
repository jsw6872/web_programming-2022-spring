# HTML Form
## form 개요
- user input의 수집 용도로 사용되는 tag
- ‘submit’ button에 의해 form-handler를 호출
- 반드시 name이 지정되어 있어야만 서버 측으로 값이 전달됨
## form attribute
## form element
### input 요소
- type 속성 이용해 형태와 기능 결정
  - button
  - checkbox
    - label 태그와 for 속성을 통해 글자를 클릭해도 체크가 되기 가능
  - color
  - date
  - datetime-local
  - email
  - file
  - hidden
  - image
  - month
  - number, 
  - password, 
  - radio, 
  - range, 
  - reset, 
  - search,
  - submit, 
  - tel, 
  - text, 
  - time, 
  - url, 
  - week
### label 요소
- form-element들에 대한 label을 정의
- for 속성: `<input>` 요소의 id 속성과 일치시켜서 사용
### textarea
### select
- drop-down list를 정의
- 내부에 `<option value=“optionValue”>Item</option>` 형태의 선택항목 지님
### fieldset
### datalist
### button
### output
## GET vs POST
- GET 방식 
  - 지정된 resource로부터 data를 요청(수정X)하기 위해 활용
  - query string이 URL에 부가되어 전송: ‘?’ symbol 뒤에 name=value 형식
  - 전송할 수 있는 요청의 길이가 최대 URL 길이(2048 characters)에 의해 제한이 걸림
- POST 방식
  -  resource의 생성 및 수정을 위한 data의 전송에 활용
  -  전송할 data를 HTTP Request의 body에 담아 보냄 - data의 길이에 제한이 없음
## File upload 기능
### servlet 과 JSP 역할 분담
- File Upload의 처리 -> servlet 담당
- 처리 후 결과 HTML 문서의 작성 -> JSP 담당
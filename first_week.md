# 1주차 내용 정리
## web protocal
* WWW는 web client(web browser) 와 web server 간 통신하는 곳
* HTTP Request(client가) 보내고 HTTP Response(server가 보내주는 답)를 보냄  
  * stateless(독립적이며 영속적이지 않음)
---
## HTML
* `<map />`
* `<area />` : 영역 설정해서 a 태그와 같은 역할
---
* `<picture />`
* `<source />`  : @media 와 비슷한 역할
---
* favicon : 웹 탭에 보여지는 이미지, `<head>` 부분에 `<link rel="icon" type="image/x-icon" href="/images/favicon.ico">`와 같이 작성 
---
* `table`의 옵션
  * ex) `<th colspan="2">Name</th>` : 열 2개 잡아먹음
  * Ex) `<th rowspan="2">Phone</th>` : 행 2개 잡아먹음
  * Ex) :nth-child()
  ```css
    td:nth-child(even), th:nth-child(even) {
    background-color: #D6EEEE;
    }
  ```
  * `<colgroup />`
---
* `<iframe />` : 페이지 내에 다른 html페이지를 삽입할 수 있도록 하는 기능
---
* `<meta name='viewport' ~~>` : 기기에 따라 보이는 영역 설정
---
컴퓨터 코드나 결과를 예쁘게 나타내는 태그들
* `<kbd>` element defines keyboard input
* `<samp>` element defines sample output from a computer program
* `<code>` element defines a piece of computer code
* `<var>` element defines a variable in programming or in a mathematical expression
* `<pre>` element defines preformatted text
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
---
## html의 일반적 룰
* 띄어쓰기 자제 (= 사이에)
* `<img />` 사용 시 `alt` 및 `크기` 지정 고려

---
## form 태그
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```
* input의 타입
  * `<input type="text">`
  * `<input type="radio">`
  * `<input type="checkbox">`
  * `<input type="submit">`
    ```html
    <form action="/action_page.php">
      <label for="fname">First name:</label><br>
      <input type="text" id="fname" name="fname" value="John"><br>
      <label for="lname">Last name:</label><br>
      <input type="text" id="lname" name="lname" value="Doe"><br><br>
      <input type="submit" value="Submit">
    </form> 
    <!-- action에 있는 주소로 이동 submit 제출 시 -->
    ```
  * `<input type="button">`
* target의 속성
  * _blank	The response is displayed in a new window or tab
  * _self	The response is displayed in the current window
  * _parent	The response is displayed in the parent frame
  * _top	The response is displayed in the full body of the window
  * framename	The response is displayed in a named iframe
* method의 속성
  * get
  * post
    * Tip: Always use POST if the form data contains sensitive or personal information!
* form elements
  * `<input>`
  * `<label>`
  * `<select>`
  * `<textarea>`
  * `<button>`
  * `<fieldset>`
  * `<legend>`
  * `<datalist>`
  * `<output>`
  * `<option>`
  * `<optgroup>`
* form attribute
  * `action`
  * `formenctype`
  * `formmethod`
    *  [get vs post (html input form attributes)](https://www.w3schools.com/html/html_form_attributes_form.asp)
 * `formtarget`
 * `formnovalidate`
 * `novalidate`
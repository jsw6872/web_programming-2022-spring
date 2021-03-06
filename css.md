# CSS
## 새로 알게된 태깅 및 기능
### display: inline-block
- inline 엘리먼트처럼 전후 줄바꿈 없이 한 줄에 다른 엘리먼트들과 나란히 배치됩니다. 하지만 inline 엘리먼트에서 불가능하던 width와 height 속성 지정 및 margin과 padding 속성의 상하 간격 지정이 가능
### css 여러 요소 동시 선택 적용
- [css 동시 선택 참조](https://blog.naver.com/PostView.nhn?blogId=shinekjm&logNo=221618781015)
### websafe fonts for HTML and CSS
- Arial (sans-serif)
- Verdana (sans-serif)
- Helvetica (sans-serif)
- Tahoma (sans-serif)
- Trebuchet MS (sans-serif)
- Times New Roman (serif)
- Georgia (serif)
- Garamond (serif)
- Courier New (monospace)
- Brush Script MT (cursive)
### font fallback
- Serif
- Sans-serif
- Monospace
- Cursive
- Fantasy
- google fonts
  ```html
  <head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Trirong">
    <style>
      body {
        font-family: "Trirong", serif;
      }
    </style>
  </head>
  ``` 
### icon
- font awesome icons
  > `<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>`
- bootstrap icons
  > `<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">`
- Google Icons
  > `<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">`
### styling links
- a:link - a normal, unvisited link
- a:visited - a link the user has visited
- a:hover - a link when the user mouses over it
- a:active - a link the moment it is clicked
### cursor styling
```html
<span style="cursor: auto">auto</span><br>
<span style="cursor: crosshair">crosshair</span><br>
<span style="cursor: default">default</span><br>
<span style="cursor: e-resize">e-resize</span><br>
<span style="cursor: help">help</span><br>
<span style="cursor: move">move</span><br>
<span style="cursor: n-resize">n-resize</span><br>
<span style="cursor: ne-resize">ne-resize</span><br>
<span style="cursor: nw-resize">nw-resize</span><br>
<span style="cursor: pointer">pointer</span><br>
<span style="cursor: progress">progress</span><br>
<span style="cursor: s-resize">s-resize</span><br>
<span style="cursor: se-resize">se-resize</span><br>
<span style="cursor: sw-resize">sw-resize</span><br>
<span style="cursor: text">text</span><br>
<span style="cursor: w-resize">w-resize</span><br>
<span style="cursor: wait">wait</span>
```
### list style type
```css
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
ul {
  list-style-image: url('sqpurple.gif');
}
/* list position */
ul.a {
  list-style-position: outside;
}

ul.b {
  list-style-position: inside;
}
```
### nth-child
부모안에 모든 요소 중 N번째 요소 : `tr:nth-child(N) {background-color: #f2f2f2;}`
### responsive table
`overflow-x:auto`
### position
- `position: sticky`
### z-index
`z-index` : 값은 정수이며, 숫자가 클 수록 위로 올라오고, 숫자가 작을 수록 아래로 내려가며 요소들을 겹치는 표현을 하고 싶을 때 활용
### overflow
- visible - Default. The overflow is not clipped. The content renders - outside the element's box
- hidden - The overflow is clipped, and the rest of the content will be invisible
- scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content
- auto - Similar to scroll, but it adds scrollbars only when necessary
- overflow-x
- overflow-y
### float
- `clear` : 요소를 아래로 내린다.
### combinator
```css
/* div 다음으로 오는 형제 p 태그 하나만 적용 */
div + p {
  background-color: yellow;
}
/* 한 개가 아닌 전역으로 형제 태그 적용 */
div ~ p {
  background-color: yellow;
}
```
### pseudo-class
### pseudo-element
### attribute selector
```css
input[type="text"] {
  width: 150px;
  display: block;
  margin-bottom: 10px;
  background-color: yellow;
}

input[type="button"] {
  width: 120px;
  margin-left: 35px;
  display: block;
}
```
### CSS counters
### CSS layout
[layout](https://www.w3schools.com/css/css_website_layout.asp)
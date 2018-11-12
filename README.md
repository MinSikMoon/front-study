# front-study
생활코딩 CSS 강의정리

````css
ul li{
    ul 밑의 li    
}
````

````css
ol>li {
    ol 바로 밑의 자손만 (직계자손)
}
````

````css
ol, li {
    여러개 고를때
}
````

### CSS Diner  
- CSS 선택자를 게임의 형식을 통해서 익힐 수 있는 사이트

- http://flukeout.github.io/

````css
- pseudo 선택자
a:active {
}
a:hover {
}
a:visited {
}
a:link {
}
a:focus {
}
````

````css
//최고 우선순위로 만들기
body {
    background-color:black !important; 
}
````

### 캐스캐이딩
 - 저자 - 사용자 - 브라우저 의 우선순위
 - style - id - class - tag(포괄적)
````css
  //+는 동등위치 >는 자식
  #other+#parent>#me
````
# 기본 이론    

## 텍스트 서식, 문단  
1. s, del : 글자 취소선  
2. sup, sub : 위 첨자, 아래 첨자  
3. mark : 형광펜 배경색  
4. u : 글자 밑줄 표시  
5. b, strong : bold  
6. text-transform : 영어에 대해 앞글자, 전체 대소문자 지정  
  
  
## 목록 만들기  
1. 순서가 있는 목록  
ol : Ordered List  
```html
ol > li
<ol>
  <li></li>
</ol>
```  
  
2. 순서가 없는 목록  
ul : Unordered List  
```html
ul > li
<ul>
  <li></li>
</ul>
```
  
3. 예시  
- 2단 메뉴의 경우 해당 메뉴의 자식 요소로 들어가야한다.  
```html
<ul>
  <li>1단 메뉴 1</li>

  <li>1단 메뉴 2
    <ul>
      <li>2단 메뉴</li>
    </ul>
  </li>

  <li>1단 메뉴 3</li>
</ul>
```
  
## CSS 우선 순위
1. !important    
2. inline  
3. ID selector  
4. Class selector  
5. Tag selector  
  
  
## 

## inline JS  
```html
<a href="javascript:history.back()">뒤로 이동</a>
<a href="javascript:history.forward()">앞으로 이동</a>

<button onclick="javascript:history.back()">뒤로 이동</button>
<button onclick="javascript:history.forward()">앞으로 이동</button>

<a href="javascript:location.reload()">새로고침</a>
<a href="javascript:window.close()">창닫기</a>

<button onclick="location.href='주소'">현재 탭에서 오픈</button>
<button onclick="window.open('주소')">새 탭에서 오픈</button>
```  
  
  
## display 속성의 이해  
1. 인라인 요소  
- 크기값을 지정못함  
- 한 줄에 여러개 배치  
- 상하마진 못가짐  
- 기본 너비값은 컨텐츠의 너비값  
- span, a, small, em, b, br, audio, video, s, u, mark, q, strong, sup, sub, i, big, del, label  
  
2. 블록 요소  
- 크기값을 지정할 수 있음  
- 한 줄에 한개만 배치  
- 상하좌우 마진 모두 가짐  
- 기본 너비값은 100%  
- div, ul, ol, li, h, hr, form, dl, dt, dd, p, table, header, article, footer, section, nav, details, summary, center  
  
3. 인라인블록 요소  
- 크기값을 지정할 수 있음  
- 한 줄에 여러개 배치  
- 상하마진 모두 가짐  
- 기본 너비값은 컨텐츠의 너비값  
- img, input, button, fontawesome, icon  

* 어떤 요소건 position: absolute 또는 fixed가 적용되면 인라인블록으로 변함  
* before after는 기본적으로 인라인 요소  
  
  
  
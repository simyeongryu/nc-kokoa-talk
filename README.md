# 노마드 코더 카카오톡 클론 코딩

# 이론

### 2-1 what is HTML

웹사이트의 요소를 무엇인지 정의하고 구분해주는 언어.

### 2-2 Anatomy of a HTML tag

웹서버들이 `index.html` 먼저 찾도록 설계되어 있다.

### 2-3 HTML

```html
<!-- <!DOCTYPE html> 스스로 열고 닫는 self-contained 태그. 해당 문서라 HTML 문서라는 걸 브라우저에 알려준다. -->
<!DOCTYPE html>
<html>
  <!-- <head> 내 정보는 유저에게 보이지 않는다. 브라우저에게 필요한 정보를 전달한다. -->
  <head>
  </head>
  <!-- <body> 사람들이 볼 수 있는 요소들은 body에 있다. -->
  <body>
  </body>
</html>
```

### 2-4 meta: 추가 정보 태그

`<meta>`는 추가 정보를 나타낸다. meta name은 구글 등에서 검색할 때 웹사이트 요약 내용 등을 결정한다.

```html
<meta name="author" content="ryusimyeong" />
<meta name="description" content="nomad coder html-css lecture note" />
```

### 2-5 semantic tag, non-sematinc tag

의미가 있는 태그, 의미가 없는 태그

h1, section, article 등은 시멘틱. span, div는 논 시멘틱

div는 블록을 위한 컨테이너. span은 텍스트를 위한 컨테이너.

# 실전

## ColorZila

화면에서 원하는 색상 얻는 크롬 어플

## 글로벌 class

반복되는 요소를 위한 전역 class

## css import 
```css
@import "./reset.css";
```

내용을 끌고 온다. html 등에서는 link를 하나만 하면 된다.

## google fonts

구글 폰트

필요한 폰트를 고른 다음 필요한 굵기만 고르고

CSS import할지 HTML link할지 고르고 사용한다.

## 샘플 사이트

dribble - 디자인

subtle patterns - 패턴 샘플

ui gradient - gradient sample

## positionL fixed 혹은 absolute일 때 요소 가운데 정렬 

margin: auto;
left: 0;
right: 0;

## 형제선택자 

### 인접 형제선택자 

```css
/* 같은 부모를 갖는 상태에서, E + F 
 * E 바로 뒤에 나오는 F에만 속성값 부여  */
.chat__write:focus + .chat__icon {
  display: none;
}
```

### 일반 형제선택자  

```css
/* 같은 부모를 갖는 상태에서, E ~ F
 * E 뒤에 나오는 F들에 속성값 부여  */
.chat__write:focus ~ .chat__icon {
  display: none;
}
```

## box sizing

<img src="https://t1.daumcdn.net/cfile/tistory/99D6524D5BB1675724" /> 

### content-box

```css
/* width와 height의 기준을 content로 설정한다 
 * width: 500px; 을 지정하면 content만 500px가 되고 padding, border 등은 따로 계산해야 한다.
*/
* {
  box-sizing: content-box;
}
```

### border-box
```css
/* box-sizing: width와 height의 기준을 boder box를 포함한 크기로 설정한다 
 * width: 500px; 을 지정하면 border를 포함한 크기가 500px로 설정된다.
*/
* {
  box-sizing: border-box;
}
```

# 챌린지

## 1. 

### 문제

https://i.imgur.com/WZM57Z2.png

- The has to have a height of 1500px;
- The top red bar should stay at the top of the page even if I scroll.
- The white title should have a 50px space from the borders of the blue box.
- The yellow box should have a grey border.
- There should be one .css file and one .html file.
- The green box should be in the intersection between the red, blue and yellow.

### 코드

- 내 코드 : https://codesandbox.io/s/blueprint-4wg10

## 3. 

### 문제

https://i.imgur.com/lDf56lt.png

### 코드

- 내코드 : https://codesandbox.io/s/blueprint-8t8p9
- 정답코드: https://codesandbox.io/s/1on3n2430l

## 4. 

### 문제

https://nomad-coders-assets.s3.amazonaws.com/media/public/django-summernote/2019-07-26/d1478780-7606-4986-b058-3ffb9fc31953.gif

### 코드

- 내코드 : https://codesandbox.io/s/blueprint-el7rb
- 정답코드 : https://codesandbox.io/s/vy3k3kyxr3

## 5.

- 내코드 : https://codesandbox.io/s/blueprint-1hggo
- 정답코드 : https://codesandbox.io/s/2w4kkl1p8r

## 6.

### 문제 

https://i.ibb.co/qRyBr3M/00.png

### 코드

- 내코드 : https://codesandbox.io/s/blueprint-0pl3b
- 정답코드 : https://codesandbox.io/s/znpprpw58l

## 7.

### 문제

https://i.ibb.co/85Lx7jT/1.png

### 코드

- 내코드 : https://codesandbox.io/s/blueprint-upbri
- 정답 코드 : https://codesandbox.io/s/7wkzmj8n9q

## 8. 

### 문제

https://nomad-coders-assets.s3.amazonaws.com/media/public/django-summernote/2019-07-27/faa40d7c-7fc0-4aa5-9bf2-26626b666ffc.png

### 코드

- 내코드 : 
- 정답 코드 : https://codesandbox.io/s/0y1945ov0n

## 9.

### 문제

https://nomad-coders-assets.s3.amazonaws.com/media/public/django-summernote/2019-07-27/27d503b9-cb42-4013-9c41-6e7d550cad17.png

### 코드

- 내코드 : https://codesandbox.io/s/blueprint-mqv1w
- 정답 : https://codesandbox.io/s/xpz04x8x6w

## 10. 

### 문제

https://nomad-coders-assets.s3.amazonaws.com/media/public/django-summernote/2019-07-27/189255b8-7241-4d97-b48a-ee8d4ef9c527.png

### 코드

- 내 코드 : https://codesandbox.io/s/blueprint-b6ug6
- 정답 코드 : https://codesandbox.io/s/48p48w2wv9

## 11.

### 문제 

https://lh3.googleusercontent.com/xWu12ctIdOUput7vMWUaC1KUMqD4z8zoCSzUuP-PrfvPlAT4VySoqxjOhStKnWOOra8as8d6lUj_E7jVgpsv8mH-q-plfx9AkIvMD_htqvhvIqZ8Yg-MdZgYrUG44x0DEn62-_re

https://lh5.googleusercontent.com/ercLrzGF0ot_bfbO4zlPr073qUaUkfwnFYGt9gieZwuglGjwGtylDDBmcV0Bx720CpZzxO5XB7-qHTPGbq-m_plkt69MuTiNZ5Z2RZOxC1kymRUyy-mJPtzjy1k9WrH9D-QTOfqh

### 코드

두 번째 박스 마우스 hover 및 height 조정이 좀 어렵다

- 내코드 :https://codesandbox.io/s/blueprint-pewm1


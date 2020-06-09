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
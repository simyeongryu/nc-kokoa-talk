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


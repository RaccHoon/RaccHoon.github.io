---
layout: post
title: "HTML 기본 구조"
date: 2023-04-18
categories: HTML-CSS
---

## HTML 구조
``` HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
Emmet 명령어를 이용해 `!`를 입력한 후 `tab`을 누르면 자동으로 HTML의 기본 틀을 만들어준다.  
> Emmet: HTML, CSS를 편리하게 사용할 수 있도록 도와주는 플러그인  

### `<!DOCTYPE HTML>`
현재 문서가 HTML5 언어로 작성된 문서임을 알려줌
  
### `<html>`
> 문서의 시작과 끝을 나타냄  

### `<head>`
> 브라우저가 문서를 해석하는데 필요한 정보를 입력  
> #### `<meta>`
> > 브라우저에는 보이지 않지만 웹 문서와 관련된 정보를 지정할 때 사용.  
> > `<meta charset="UTF-8">`: 한글을 읽을 수 있는 방식의 인코딩 적용.
> #### `<title>`
> > 웹 문서의 제목을 입력함.
 
### `<body>`
> 실제 웹 브라우저에 표시할 내용을 입력.

## 시맨틱 태그
시맨틱 태그를 이용해 소스 코드의 어느 부분이 제목, 메뉴, 본문인지 쉽게 알 수 있게 표시해주는 태그.  
웹 문서 구조를 만들 때 반드시 시멘틱 태그를 사용할 필요는 없고, 웹 문서에서 무언가 크게 달라지지도 않지만, 여러 부분에서 웹 사이트 사용자에게 정확한 정보를 전달하기 수월해진다.  
* `<header>`: 주로 맨 위쪽이나 왼쪽에서 검색 창이나 사이트 메뉴를 포함한다  
* `<nav>`: 웹 문서 안에서 다른 위치나 다른 웹 문서로 연결하는 내비게이션을 만들 때 흔히 사용하며, 헤더나 푸터, 사이드 바 등에 포함될 수 있다. 또한 id 속성을 이용해 여러 `<nav>` 태그에 다른 스타일을 적용할 수 있다.
* `<main>`: 웹 문서의 핵심이 되는 내용을 넣으며, 웹 문서에서 단 한번만 사용할 수 있다.
* `<section>`: 관련된 글 등 몇 개의 콘텐츠를 묶는 용도로 사용
* `<div>`: 단순히 스타일 적용을 위해 콘텐츠를 묶는 경우 사용
* `<aside>`: 본문 왼쪽 혹은 오른쪽에 사이드바를 만드는 경우 사용.
* `<footer>`: 웹 문서 맨 아래에 기타 정보를 담을 때 사용.

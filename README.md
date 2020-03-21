
## 🚀 미션: 90년생 HTML 소개하기

이번 미션의 주제는 바로 90년생 HTML을 주제로 웹페이지를 작성하는 것입니다.
작성방식은 자유입니다. 
신문기사, 블로그, 위키백과 같은 사전 등 여러가지 형태로 남길 수도 있을텐데요. 본인이 원하는 형태로 작성해주시면 됩니다. 
90년생 HTML의 이야기를 담아내면서 글, 링크, 사진, 동영상, 구독 메일 등을 담을 수 있을텐데요. 그 과정에서 필요한 HTML 태그들을 [MDN](https://developer.mozilla.org/ko/docs/Web/HTML/Element) 링크를 통해 직접 찾아보시길 바랍니다.

<img src="https://techcourse-storage.s3.ap-northeast-2.amazonaws.com/2020-03-16T10:41:53.786image.png" width="400">

<br/>

## 사용한 HTML tags

- `<meta>`: 문자 인코딩 및 문서 키워드 요약 정보 (ex. `<meta charset="utf-8">`: 웹 페이지의 문자 인코딩 방식을 utf-8로 지정하라)
- `<style>`: 스타일 정보를 정의할 때 사용하는 태그이다. (`<head></head>`사이에 정의한다.)
- `<header>`: 제목을 지정할 때 사용한다.
- `<nav>`: 문서 연결 링크. 같은 사이트 안의 페이지나 다른 사이트의 페이지로 연결하는 링크이다.
- `<main>`: 문서 `<body>`의 주요 내용을 담을 때 사용한다.
- `<section>`: 독립적인 내용을 담는 태그이다.
- `<article>`: 주제별로 그룹화된 내용을 담는 태그이다. (내용이 서로 관련 있을 때 사용한다.)
- `<div>`: 컨텐츠를 묶어야 할 때 사용한다. 특별한 의미는 없다.
- `<img>`: 이미지를 삽입할 때 사용한다.
- `<a>`: 다른 문서나 사이트로 연결해주는 하이퍼링크(hyperlink)를 만들때 사용한다. (ex. `<a href="연결할 링크의 경로">내용</a>`)
- `<iframe>`: 외부 페이지를 삽입할 때 사용한다. (`<iframe src="삽입할 페이지 주소" [속성="속성값"]></iframe>`)
- `<ol>`: 순서(orderlist)가 있는 리스트(list)를 만들때 사용한다. (cf. `<ul>`순서가 없는 리스트)
- `<li>`: `<ul>`과`<ol>` 안에서 각 항목을 나열할 때 사용한다.
- `<hr>`: 위 아래 구분을 위해 수평 직선을 그릴 때 사용한다.
- `<p>`: 단락을 생성한다. 내용 앞뒤로 빈 줄이 생기며 단락을 만든다.
- `<b>`: 글자를 볼드체로 만든다.

## 요구사항

- [x]  `<html>` `<head>` `<title>` `<body>` 태그를 반드시 포함한다.
- [x]  `<head>` 태그 안에는 `<meta charset="utf-8">` 를 삽입한다.
- [x]  위 5개의 태그를 제외하고 최소 10개 이상의 태그를 이용한다.
- [x]  1개 이상의 이미지 또는 비디오를 삽입한다.
- [x]  댓글을 작성하는 `input` 또는 `textarea` 태그를 사용한다. (실제 동작할 필요는 없음)
- [x]  자신이 사용한 태그들의 기능을 README.md에 작성한다.

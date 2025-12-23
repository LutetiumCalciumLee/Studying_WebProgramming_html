<details>
<summary>ENG (English Version)</summary>

# Web Programming

## Core Web Structure
HTML5 documents use `<!DOCTYPE html>`, `<html lang="ko">`, `<head>` for metadata/title/CSS links, and `<body>` for visible content.
Semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` define page structure for better accessibility and SEO.
Forms use `<form>`, various `<input type="">` (email, date, range, color), `<label>`, `<fieldset>`, `<datalist>` with built-in validation.

## CSS3 Styling Systems
CSS applies via inline `style=""`, internal `<style>`, or external `<link rel="stylesheet">`; selectors include tags, classes (`.class`), IDs (`#id`), attributes, pseudo-classes (`:hover`, `:focus`).
Box model controls content, padding, border, margin; properties like `border-radius`, `box-shadow`, `text-shadow` create modern effects.
Advanced: `position` (static/relative/absolute/fixed), `float`, `z-index`, `@keyframes` animations, `transform` (rotate/scale), 3D `perspective`.

## JavaScript Fundamentals
Variables use `var`/`let`/`const`; dynamic typing supports numbers/strings/booleans/arrays/objects; operators include arithmetic/comparison/logical.
Control flow: `if/else`, `switch`, `for/while/do-while` loops; functions defined with `function name() {}` support parameters/returns.
Core objects: `Date` (getFullYear/month), `String` (length/charAt/replace), `Math` (random/floor), `Array` (push/pop/sort/slice).

## DOM/BOM/Event Handling
DOM accessed via `document.getElementById/className/querySelector`; modify with `.innerHTML`, `.style`, `.classList`.
BOM: `window.open/close`, `location.href`, `navigator.userAgent`, `screen.width`, `history.back()`; timers `setTimeout/setInterval`.
Events: `addEventListener('click', func)`, event object (`e.target`, `e.offsetX`), mouse/keyboard/form events with bubbling/capturing.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 웹프로그래밍

## 웹 핵심 구조
HTML5 문서는 `<!DOCTYPE html>`, `<html lang="ko">`, `<head>`(메타/제목/CSS), `<body>`(가시 콘텐츠)로 구성.
`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` 시맨틱 태그로 접근성/SEO 향상.
폼: `<form>`, `<input type="email/date/range/color">`, `<label>`, `<fieldset>`, `<datalist>` 내장 검증 지원.

## CSS3 스타일링 체계
인라인 `style=""`, 내부 `<style>`, 외부 `<link rel="stylesheet">` 적용; 태그/클래스(`.class`)/ID(`#id`)/속성/의사클래스(`:hover`/:focus`) 선택자.[file:51]
박스모델: content/padding/border/margin 제어; `border-radius`, `box-shadow`, `text-shadow` 현대적 효과.
고급: `position`(static/relative/absolute/fixed), `float`, `z-index`, `@keyframes` 애니메이션, `transform`(회전/크기), 3D `perspective`.

## 자바스크립트 기초
`var`/`let`/`const` 변수; 동적 타입(숫자/문자열/불린/배열/객체); 산술/비교/논리 연산자.
제어문: `if/else`, `switch`, `for/while/do-while`; `function name() {}` 매개변수/반환 지원.
코어 객체: `Date`(getFullYear/month), `String`(length/charAt/replace), `Math`(random/floor), `Array`(push/pop/sort/slice).

## DOM/BOM/이벤트 처리
DOM: `getElementById/className/querySelector`; `.innerHTML`, `.style`, `.classList` 수정.
BOM: `window.open/close`, `location.href`, `navigator.userAgent`, `screen.width`, `history.back()`; `setTimeout/setInterval` 타이머.
이벤트: `addEventListener('click', func)`, 이벤트 객체(`e.target`, `e.offsetX`), 마우스/키보드/폼 이벤트 버블링/캡처링.

</details>

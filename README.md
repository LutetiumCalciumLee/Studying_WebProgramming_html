<details>
<summary>ENG (English Version)</summary>

# Chapter 9. JavaScript Events and Event Listeners

### Event Concepts and Types
- Events notify JavaScript code of user actions (mouse clicks, key presses) or document/browser state changes (loading, resizing), with listeners handling responses.
- Common events include `click`, `dblclick`, `keydown`, `keyup`, `load`, `change`, `submit`, `resize`; listener names prefixed with `on` (e.g., `onmousedown`).

### Event Listener Registration Methods
- Four methods: HTML tag attributes (`onmouseover="..."`), DOM properties (`p.onmouseover = over`), `addEventListener()` (recommended), and anonymous functions for concise code.
- Examples show mouseover effects changing background colors using each method, with `addEventListener("mouseover", over)` for modern usage.

### Event Object and Flow
- Event object provides details like `type`, `target`, `currentTarget`; passed as first parameter to listeners (`function(e)`).
- Event flow: capturing phase (window → target) then bubbling phase (target → window); register capture listeners with `addEventListener(event, func, true)`.

### Mouse and Form Events
- Mouse events: `mousedown`, `mouseup`, `mouseover`, `mouseenter`, `wheel` (with `wheelDelta` for direction); prevent context menu with `oncontextmenu` returning `false`.
- Form events: `onchange` for selects/radio/checkbox, `onfocus`/`onblur` for validation, `onsubmit`/`onreset` to control form submission/reset.

### Image Loading and Keyboard Events
- `onload` for document/image completion; use `new Image()` for preloading, check dimensions only after `onload` fires.
- Keyboard events: `onkeydown` (all keys), `onkeypress` (character keys), `onkeyup`; detect modifiers (`altKey`, `shiftKey`, `ctrlKey`) and key codes.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 9장. 자바스크립트 이벤트와 이벤트 리스너

### 이벤트 개념과 종류
- 마우스 클릭, 키보드 입력, 문서 로딩 등 사용자 행위나 상태 변화를 자바스크립트에 알리는 이벤트와 이를 처리하는 리스너 코드 설명.
- `click`, `dblclick`, `keydown`, `keyup`, `load`, `change`, `submit` 등 주요 이벤트와 `on` 접두사 리스너명(`onmousedown` 등) 정리.

### 이벤트 리스너 등록 방법
- HTML 태그 속성, DOM 프로퍼티(`p.onmouseover = over`), `addEventListener()`(권장), 익명함수 4가지 방법으로 마우스오버 효과 구현 예제 제시.
- `addEventListener("mouseover", over)` 방식으로 현대적 이벤트 등록과 배경색 변경 실습 예제 포함.

### 이벤트 객체와 흐름
- 이벤트 객체의 `type`, `target`, `currentTarget` 등 정보 확인과 리스너 첫 매개변수로 전달받기(`function(e)`).
- 캡처 단계(window→타겟)와 버블 단계(타겟→window) 이벤트 흐름, `addEventListener(event, func, true)`로 캡처 리스너 등록.

### 마우스와 폼 이벤트
- `mousedown`, `mouseup`, `mouseover`, `mouseenter`, `wheel`(`wheelDelta` 방향 판별) 등 마우스 이벤트와 `oncontextmenu`로 컨텍스트 메뉴 차단.
- `onchange`(select/라디오/체크박스), `onfocus`/`onblur`(유효성 검사), `onsubmit`/`onreset`(폼 제어) 폼 이벤트 처리.

### 이미지 로딩과 키보드 이벤트
- 문서/이미지 로딩 완료 `onload`, `new Image()` 사전 로딩과 `onload` 후 크기 확인 방법 제시.
- `onkeydown`(모든 키), `onkeypress`(문자키), `onkeyup`과 `altKey`, `shiftKey`, `ctrlKey` 수정키 감지 및 키코드 확인.

</details>

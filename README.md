<details>
<summary>ENG (English Version)</summary>

# Chapter 6. JavaScript Basics

### What is JavaScript?
- Lightweight, interpreted scripting language created in 1995.
- Embedded in HTML and executed by browsers, powering dynamic content and interactivity.
- Used on both client side (browsers) and increasingly on the server side (Node.js).



### How to Use JavaScript in HTML
- Code can be placed directly in HTML element event attributes (e.g., `onclick`).
- Write code inside `<script>` tags in the `<head>` or `<body>`.
- For modularity and reuse, link external `.js` files with `<script src="file.js"></script>`.



### Output and Dialogs
- Use `document.write()` to directly output content to the page during page load.
- Show messages with `alert()`.
- Get user input with `prompt()`.
- Request confirmation with `confirm()`.



### Variables and Data Types
- Declare variables with `var`, `let`, or `const`.
- Store numbers, strings, booleans, arrays, objects, etc.
- Variables are dynamically typed and can change type at runtime.



### Operators
- Arithmetic: `+`, `-`, `*`, `/`, `%`
- Assignment: `=`, `+=`, `-=`, etc.
- Comparison: `==`, `!=`, `>`, `<`, etc.
- Logical: `&&`, `||`, `!`
- Bitwise and ternary (conditional) operators



### Control Structures
- Conditionals: `if`, `if-else`, `switch`
- Loops: `for`, `while`, `do-while`
- Use `break` and `continue` to control execution flow



### Functions
- Define reusable code blocks with the `function` keyword
- Functions can accept parameters and return values
- Call functions multiple times with different arguments



### Scope
- Variables are global or local depending on where they are declared
- Block scope with `let` and `const`; function scope with `var`



### Built-in Functions
- `eval()`: Evaluate strings as code
- `parseInt()`: Convert string to integer
- `isNaN()`: Check for non-numeric value



### Event Handling
- Respond to user actions (clicks, key presses, etc.)
- Assign JavaScript to HTML event attributes, or use `addEventListener` for dynamic behavior

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 6장. 자바스크립트 기초

### 자바스크립트란?
- 1995년에 개발된 가볍고 인터프리터 방식의 스크립트 언어임.
- HTML에 포함되어 브라우저에서 실행되며, 동적 콘텐츠와 상호작용 구현에 필수임.
- 클라이언트(브라우저)뿐 아니라 서버(Node.js)에서도 사용 가능함.



### HTML에서 자바스크립트 사용 방법
- HTML 요소의 이벤트 속성(예: `onclick`)에 직접 코드 작성 가능함.
- `<head>`나 `<body>`의 `<script>` 태그 안에 코드 작성 가능함.
- 코드 재사용성을 높이려면 외부 `.js` 파일을 `<script src="파일.js"></script>`로 연결함.



### 출력 및 대화창
- `document.write()`로 페이지에 직접 출력(페이지 로딩 중에만 작동함).
- `alert()`로 메시지 표시.
- `prompt()`로 사용자 입력 요청.
- `confirm()`으로 확인 여부 요청.



### 변수와 데이터 타입
- `var`, `let`, `const`로 변수 선언 가능함.
- 숫자, 문자열, 불린, 배열, 객체 등 다양한 자료형을 저장함.
- 동적 타입 언어이므로 변수의 타입이 실행 중에 바뀔 수 있음.



### 연산자
- 산술 연산자: `+`, `-`, `*`, `/`, `%`
- 대입 연산자: `=`, `+=`, `-=` 등
- 비교 연산자: `==`, `!=`, `>`, `<` 등
- 논리 연산자: `&&`, `||`, `!`
- 비트/삼항(조건) 연산자



### 제어 구조
- 조건문: `if`, `if-else`, `switch`
- 반복문: `for`, `while`, `do-while`
- `break`, `continue`로 흐름 제어 가능함



### 함수
- `function` 키워드로 재사용 가능한 코드 블록 정의함
- 매개변수와 반환값 사용 가능함
- 함수를 여러 번 호출해 다양한 동작 구현 가능함



### 스코프(유효 범위)
- 변수는 선언 위치에 따라 전역 또는 지역으로 구분됨
- `let`, `const`는 블록 단위, `var`는 함수 단위 스코프를 가짐



### 내장 함수
- `eval()`: 문자열을 코드로 평가함
- `parseInt()`: 문자열을 정수로 변환함
- `isNaN()`: 숫자가 아닌 값인지 확인함



### 이벤트 처리
- 클릭, 키 입력 등 사용자 행동에 반응함
- HTML 이벤트 속성에 코드 지정하거나, 동적 처리는 `addEventListener` 사용함

</details>

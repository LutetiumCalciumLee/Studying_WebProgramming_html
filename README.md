<details>
<summary>ENG (English Version)</summary>

# Chapter 7. JavaScript Core Objects and Arrays

### Object Concepts
- In JavaScript, an object is a collection of properties (data) and methods (functions).
- Objects represent real-world entities (e.g., a car, a person, a bank account) with unique attributes and behaviors.
- You can create objects using object literals (e.g., `{}`) or the `new Object()` constructor.
- Properties are accessed and modified using dot notation (e.g., `object.property`) or bracket notation (e.g., `object["property"]`).



### Types of JavaScript Objects
- **Core Objects:** Built-in objects available in any JavaScript environment, such as `Array`, `Date`, `String`, and `Math`.
- **HTML DOM Objects:** Represent HTML elements in the document, allowing control over content and appearance.
- **Browser Objects:** Provided by the browser for controlling browser features (e.g., `window`, `navigator`, `location`).



### Working with Core Objects
- **Date Object:** Used to handle date and time information. Create with `new Date()`, and access components like year, month, day, hour, minute, and second using methods such as `getFullYear()`, `getMonth()`, and `getDate()`.
- **String Object:** Represents and manipulates text. Strings are immutable. Common properties and methods include `length`, `charAt()`, `concat()`, `indexOf()`, `slice()`, `substr()`, `toUpperCase()`, `replace()`, `trim()`, and `split()`.
- **Math Object:** Provides mathematical constants and functions. Methods include `Math.sqrt()`, `Math.random()`, `Math.floor()`, and others for calculations and generating random numbers.



### Arrays in JavaScript
- Arrays are used to store multiple values in a single variable.
- You can create arrays using array literals (`[]`) or the `new Array()` constructor.
- Arrays can contain elements of any type, and their size is dynamic—elements can be added or changed at any time.
- Access elements using zero-based indexing (e.g., `array[0]`).
- The `length` property returns the number of elements in the array.
- Arrays have built-in methods such as `concat()`, `join()`, `reverse()`, `slice()`, `sort()`, and `toString()` for manipulation and processing.



### Creating and Using Custom Objects
- JavaScript allows you to define your own object types using either the `new Object()` syntax or object literals.
- You can add properties and methods to these objects to model real-world entities or application-specific data structures.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 7장. 자바스크립트 핵심 객체와 배열

### 객체 개념
- 자바스크립트에서 객체는 속성(데이터)과 메서드(함수)로 이루어진 집합임.
- 객체는 자동차, 사람, 은행 계좌 등 현실 세계의 개체를 속성과 동작으로 표현함.
- 객체는 객체 리터럴(`{}`)이나 `new Object()` 생성자를 사용해 만들 수 있음.
- 속성은 점 표기법(`객체.속성`) 또는 대괄호 표기법(`객체["속성"]`)으로 접근 및 수정함.



### 자바스크립트 객체 종류
- **핵심 객체:** 모든 자바스크립트 환경에서 제공되는 내장 객체(`Array`, `Date`, `String`, `Math` 등).
- **HTML DOM 객체:** 문서 내 HTML 요소를 나타내며, 내용과 모양을 제어함.
- **브라우저 객체:** 브라우저가 제공하는 기능 제어용 객체(`window`, `navigator`, `location` 등).



### 핵심 객체 활용
- **Date 객체:** 날짜와 시간 정보를 다루는 객체임. `new Date()`로 생성하며, `getFullYear()`, `getMonth()`, `getDate()` 등 메서드로 연도, 월, 일, 시, 분, 초를 확인함.
- **String 객체:** 텍스트를 표현하고 조작하는 객체임. 문자열은 불변(immutable)임. 주요 속성과 메서드는 `length`, `charAt()`, `concat()`, `indexOf()`, `slice()`, `substr()`, `toUpperCase()`, `replace()`, `trim()`, `split()` 등이 있음.
- **Math 객체:** 수학 상수와 함수 제공. `Math.sqrt()`, `Math.random()`, `Math.floor()` 등 다양한 계산과 난수 생성에 사용함.



### 자바스크립트 배열
- 배열은 하나의 변수에 여러 값을 저장하는 자료구조임.
- 배열 리터럴(`[]`)이나 `new Array()` 생성자로 만들 수 있음.
- 배열은 다양한 타입의 요소를 담을 수 있고, 크기가 동적으로 변함. 언제든 요소 추가/수정 가능함.
- 0부터 시작하는 인덱스로 요소에 접근함(예: `array[0]`).
- `length` 속성으로 배열의 요소 개수를 확인함.
- `concat()`, `join()`, `reverse()`, `slice()`, `sort()`, `toString()` 등 내장 메서드로 배열을 조작함.



### 사용자 정의 객체 생성 및 활용
- 자바스크립트는 `new Object()`나 객체 리터럴로 직접 객체 타입을 정의할 수 있음.
- 속성과 메서드를 추가해 현실 세계의 개체나 애플리케이션 전용 데이터 구조를 모델링할 수 있음.

</details>

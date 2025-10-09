<details>
<summary>ENG (English Version)</summary>

# Chapter 4. Styling Web Pages with CSS3

**Key Points:**

- **What is CSS3?**  
  CSS3 (Cascading Style Sheets Level 3) is the latest standard for describing the look and formatting of web documents. It enables customization of colors, fonts, spacing, borders, backgrounds, and visual effects.

- **How to Apply CSS3:**  
  CSS3 styles can be added to HTML in three main ways:  
  - Inside a `<style>` tag in the `<head>` section (internal stylesheet)  
  - Directly in an element’s `style` attribute (inline style)  
  - By linking to an external `.css` file using the `<link>` tag or `@import` rule (external stylesheet)

- **Selectors:**  
  CSS uses selectors to target HTML elements for styling. Types include:
  - Tag selectors (e.g., `h3 { color: brown; }`)
  - Class selectors (e.g., `.warning { color: red; }`)
  - ID selectors (e.g., `#list { background: mistyrose; }`)
  - Combinators for parent-child or descendant relationships
  - Attribute selectors (e.g., `input[type=text] { color: red; }`)
  - Pseudo-classes (e.g., `a:hover`, `li:active`, `h3:first-letter`)

- **Core CSS3 Properties:**
  - **Color and Background:** Control text color, background color, and background images, including position, size, and repeat options.
  - **Text Styling:** Adjust alignment, indentation, decoration (underline, overline, line-through), and shadow effects.
  - **Font Control:** Set font family, size, weight, style, and use shorthand properties for concise definitions.
  - **Box Model:** Every HTML element is a rectangular box consisting of content, padding, border, and margin. CSS3 allows precise control over each part, including border styles, widths, colors, and border-radius for rounded corners.
  - **Visual Effects:** Add shadows to text and boxes (`text-shadow`, `box-shadow`), and use images as borders (`border-image`).

- **Inheritance and Cascading:**  
  CSS properties can be inherited from parent to child elements. If multiple styles apply, CSS follows a priority order: browser defaults < external stylesheets < internal styles < inline styles.

- **Units:**  
  CSS3 supports various units for sizing and spacing, such as `px` (pixels), `em` (relative to font size), `%` (percentage), `cm` (centimeters), and more.

- **Cursor Control:**  
  The `cursor` property customizes the mouse pointer when hovering over elements.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 4장. CSS3를 이용한 웹 페이지 스타일링

**핵심 내용:**

- **CSS3란?**  
  CSS3(Cascading Style Sheets Level 3)는 웹 문서의 외관과 서식을 설명하는 최신 표준임. 색상, 글꼴, 간격, 테두리, 배경, 시각 효과 등을 자유롭게 꾸밀 수 있음.

- **CSS3 적용 방법:**  
  CSS3 스타일은 HTML에 다음 세 가지 방식으로 적용 가능함:  
  - `<head>` 내 `<style>` 태그에 직접 작성(내부 스타일시트)  
  - 요소의 `style` 속성에 직접 작성(인라인 스타일)  
  - 외부 `.css` 파일을 `<link>` 태그나 `@import` 규칙으로 연결(외부 스타일시트)

- **선택자 종류:**  
  CSS는 HTML 요소를 선택해 스타일을 적용함. 주요 선택자 종류는 다음과 같음:
  - 태그 선택자 (예: `h3 { color: brown; }`)
  - 클래스 선택자 (예: `.warning { color: red; }`)
  - 아이디 선택자 (예: `#list { background: mistyrose; }`)
  - 조합자 선택자 (부모-자식, 자손 관계)
  - 속성 선택자 (예: `input[type=text] { color: red; }`)
  - 의사 클래스 (예: `a:hover`, `li:active`, `h3:first-letter`)

- **주요 CSS3 속성:**
  - **색상과 배경:** 텍스트 색, 배경 색, 배경 이미지 위치, 크기, 반복 설정 조절.
  - **텍스트 스타일링:** 정렬, 들여쓰기, 장식(밑줄, 윗줄, 취소선), 그림자 효과 적용.
  - **글꼴 제어:** 글꼴 종류, 크기, 두께, 스타일 지정. 축약 속성으로 편리하게 지정.
  - **박스 모델:** 모든 HTML 요소는 내용(content), 안쪽여백(padding), 테두리(border), 바깥여백(margin)으로 구성. 각 부분에 스타일, 크기, 색, 둥근 테두리(border-radius) 설정 가능.
  - **시각 효과:** 텍스트 그림자(text-shadow), 박스 그림자(box-shadow), 이미지 테두리(border-image) 사용.

- **상속과 우선순위:**  
  부모에서 자식 요소로 CSS 속성이 상속됨. 여러 스타일이 적용될 경우 우선순위는 브라우저 기본 < 외부 스타일시트 < 내부 스타일 < 인라인 스타일 순임.

- **단위:**  
  픽셀(px), 글꼴 크기의 상대 단위(em), 백분율(%), 센티미터(cm) 등 다양한 단위를 지원.

- **커서 제어:**  
  `cursor` 속성으로 마우스 포인터 모양을 요소 위에 올릴 때 변경 가능.

</details>

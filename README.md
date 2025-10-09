<details>
<summary>ENG (English Version)</summary>

# Chapter 2. HTML5 Basic Document Contents

### HTML5 Document Structure
- An HTML5 document starts with `<!DOCTYPE html>` to declare the HTML version.
- The `<html>` tag encompasses the entire document, with the `lang` attribute specifying the language.
- Within `<html>`, the `<head>` tag contains meta information, the document title, links to CSS or scripts, and encoding.
- The `<body>` tag contains all content shown in the browser.

### Core Tags and Formatting
- Headings (`<h1>`–`<h6>`), paragraphs (`<p>`), line breaks (`<br>`), and horizontal lines (`<hr>`) shape document structure.
- Formatting tags like `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, and `<sup>` control emphasis or style.

### Block vs. Inline Elements
- **Block elements** (e.g., `<div>`, `<p>`, `<ul>`, `<table>`) start on new lines and expand to fill available width.
- **Inline elements** (e.g., `<span>`, `<a>`, `<img>`, `<strong>`) flow within lines of text.

### Lists
- Ordered (`<ol>`), unordered (`<ul>`), and definition (`<dl>`) lists structure grouped content.
- Lists can be nested for advanced organization.

### Tables
- Use `<table>` with `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, and `<td>` to create data tables.
- Tables can hold images, links, or other elements in their cells.

### Images
- `<img>` embeds images using `src`, `alt`, `width`, and `height` attributes for display and accessibility.

### Hyperlinks
- `<a>` creates links to pages, files, or internal anchors. The `target` attribute controls where links open (such as in a new tab or window).

### Anchors and Internal Navigation
- Anchor links and `id` attributes enable navigation within the same page.

### Special Characters and Symbols
- HTML entities (e.g., `&lt;`, `&gt;`, `&copy;`, `&sum;`) are used to display special characters.

### Metadata and External Resources
- Place `<meta>`, `<title>`, `<link>`, and `<style>` inside `<head>` for encoding, document information, external styles, and additional metadata.

### Media Embedding
- Use `<audio>` and `<video>` for embedded sound or video, supporting various file types and playback controls.
- `<iframe>` embeds external pages or content.

### Frame and Window Relationships
- Framing and the `target` attribute decide where documents open. Window and frame contexts include parent, child, and top hierarchies.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 2장. HTML5 기본 문서 내용

### HTML5 문서 구조
- HTML5 문서는 `<!DOCTYPE html>` 선언으로 시작하여 문서 타입을 명시함.
- `<html>` 태그는 문서의 전체 영역을 감싸며, `lang` 속성으로 언어를 지정함.
- `<html>` 내부의 `<head>`에는 메타데이터, 문서 제목, CSS/스크립트 링크, 인코딩 정보가 위치함.
- `<body>`에는 사용자에게 보여지는 모든 콘텐츠가 작성됨.

### 주요 태그 및 텍스트 서식
- 제목(`<h1>`~`<h6>`), 단락(`<p>`), 줄바꿈(`<br>`), 가로선(`<hr>`) 등으로 문서의 구조를 만듦.
- 진하게(`<b>`, `<strong>`), 기울임(`<i>`, `<em>`), 강조(`<mark>`), 작게(`<small>`), 취소선(`<del>`), 밑줄(`<ins>`), 아래첨자(`<sub>`), 위첨자(`<sup>`) 등 다양한 텍스트 서식 지정이 가능함.

### 블록 요소와 인라인 요소 구분
- **블록 요소:** `<div>`, `<p>`, `<ul>`, `<table>` 등은 항상 새 줄에서 시작하여 가로 너비 전체를 차지함.
- **인라인 요소:** `<span>`, `<a>`, `<img>`, `<strong>` 등은 텍스트의 흐름 속에 함께 배치됨.

### 목록
- 순서 있는 목록(`<ol>`), 순서 없는 목록(`<ul>`), 정의 목록(`<dl>`)을 통해 항목을 나열함.
- 중첩된 목록도 만들 수 있음.

### 표
- `<table>`과 `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>` 태그로 표를 작성함.
- 셀 안에는 이미지, 링크, 다른 요소도 포함될 수 있음.

### 이미지
- `<img>` 태그로 이미지를 삽입하며, `src`, `alt`, `width`, `height` 속성을 사용함.

### 하이퍼링크
- `<a>` 태그는 외부 페이지, 파일, 내부 앵커로의 연결 링크를 생성함. `target` 속성으로 새 창, 같은 창 등 링크의 열린 위치를 설정함.

### 앵커 및 페이지 내부 이동
- `id` 속성을 부여한 요소와 `<a href="#id명">`을 이용해 같은 페이지 내에서 이동이 가능함.

### 특수 문자와 기호
- `&lt;`, `&gt;`, `&copy;`, `&sum;` 등 HTML 엔티티로 특수 문자나 기호를 표시함.

### 메타데이터와 외부 리소스
- `<meta>`, `<title>`, `<link>`, `<style>` 태그는 문서 정보, 외부 스타일, 추가 메타데이터를 위해 `<head>`에 위치함.

### 미디어 임베딩
- `<audio>`, `<video>` 태그로 오디오와 비디오 파일을 삽입함. 다양한 형식과 컨트롤을 지원함.
- `<iframe>` 태그로 외부 페이지나 다른 콘텐츠를 포함할 수 있음.

### 프레임과 창 관계
- `target` 속성으로 링크 문서의 표시 위치를 제어함. 브라우저 창과 프레임은 상위, 하위, 최상위 구조로 연결됨.

</details>

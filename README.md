<details>
<summary>ENG (English Version)</summary>

# Chapter 10. JavaScript BOM (Browser Object Model)

### BOM Overview and Core Objects
- BOM objects (`window`, `navigator`, `location`, `screen`, `history`) control browser features independent of HTML content, lacking international standards with browser variations.
- `window` represents browser/tab windows; created on page load, iframes, or `window.open()`; accessed via `window`, `window.self`, or `self`.

### Window Control Methods
- `window.open(url, name, features)` opens windows with position/size control (`left=10,top=10,width=300,height=400`); names like `_blank`, `_self` control reuse.
- `window.close()` closes current or opened windows; `moveBy()`, `moveTo()`, `resizeBy()`, `resizeTo()` adjust position/size (browser security may restrict).

### Timers and Scrolling
- `setTimeout(func, ms)`/`clearTimeout(id)` for one-time delays; `setInterval(func, ms)`/`clearInterval(id)` for repeated execution; examples include auto-navigation and rotating text.
- `scrollBy(x,y)`, `scrollTo(x,y)` control page scrolling; `print()` triggers print dialog with `onbeforeprint`/`onafterprint` for print-specific formatting.

### Utility Objects
- `location` manages URLs (`href`, `pathname`, `hash`); loads pages via `location.href = "url"` or `location.replace()` (no history entry).
- `navigator` provides browser info (`appName`, `userAgent`, `plugins`); `screen` gives display details (`width`, `height`, `availWidth`); `history` enables `back()`/`forward()` navigation.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 10장. 자바스크립트 BOM (Browser Object Model)

### BOM 개요와 핵심 객체
- HTML과 무관한 브라우저 제어용 BOM 객체(`window`, `navigator`, `location`, `screen`, `history`) 소개, 국제 표준 없어 브라우저별 차이 존재.
- `window` 객체는 브라우저/탭 윈도우를 나타내며, 페이지 로드, iframe, `window.open()` 시 생성, `window`/`self`로 접근.

### 윈도우 제어 메서드
- `window.open(url, 이름, 속성)`으로 새 윈도우 열기, 위치/크기 지정(`left=10,top=10,width=300,height=400`), `_blank`/`_self` 등 이름으로 재사용 제어.
- `window.close()`로 현재/생성된 윈도우 닫기, `moveBy()`/`moveTo()`/`resizeBy()`/`resizeTo()`로 위치/크기 조절(보안 제한 가능).

### 타이머와 스크롤링
- `setTimeout(func, ms)`/`clearTimeout(id)` 일회 실행, `setInterval(func, ms)`/`clearInterval(id)` 반복 실행, 자동 연결/텍스트 회전 예제.
- `scrollBy(x,y)`/`scrollTo(x,y)` 페이지 스크롤 제어, `print()` 인쇄 대화상자, `onbeforeprint`/`onafterprint` 인쇄 전용 포맷팅.

### 유틸리티 객체
- `location`으로 URL 관리(`href`, `pathname`, `hash`), `location.href="url"` 또는 `replace()`로 페이지 로드(히스토리 미생성).
- `navigator` 브라우저 정보(`appName`, `userAgent`, `plugins`), `screen` 디스플레이 정보(`width`, `height`), `history`로 `back()`/`forward()` 이동.

</details>

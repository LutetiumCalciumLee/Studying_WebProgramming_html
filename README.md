# Chapter 3 . HTML5 Document Structuring and Web Forms

### HTML5 Document Structuring with Semantic Tags

- Traditional HTML lacked tags to clearly express document structure, often relying on `<div>` and `<span>`, making it hard to understand the meaning of content.
- HTML5 introduces semantic tags such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`. These tags clearly define the roles of different parts of a web page, improving accessibility and search engine optimization.
- Additional semantic tags like `<aside>`, `<figure>`, `<figcaption>`, `<mark>`, `<time>`, `<progress>`, `<output>`, and `<details>` provide further meaning and structure to both block and inline content.
- Semantic tags do not automatically control layout or appearance; developers use CSS for styling.

---

### Web Forms in HTML5

- Web forms are essential for collecting user input for tasks like login, registration, search, and reservations.
- The `<form>` element wraps all form controls and specifies how data is sent to the server using attributes like `action`, `method`, `enctype`, and `target`.
- HTML5 provides a wide range of input types and controls:
  - Text input: `<input type="text">`, `<textarea>`, `<input type="password">`
  - Selection: `<select>`, `<option>`, `<optgroup>`, `<datalist>`, `<input list="">`
  - Buttons: `<button>`, `<input type="submit">`
  - Specialized inputs: `<input type="email">`, `<input type="tel">`, `<input type="url">`, `<input type="search">`, `<input type="color">`, `<input type="file">`, and various date/time types
  - Number and range: `<input type="number">` (with spin buttons), `<input type="range">` (with sliders)
- The `<label>` tag is used to associate captions with form controls, improving usability and accessibility.
- `<fieldset>` and `<legend>` group related form controls, making long or complex forms more organized and accessible.
- Placeholder attributes and input validation help guide users and ensure correct data entry.
- Certain non-semantic or deprecated tags (like `<font>`, `<center>`, `<big>`) have been removed in HTML5 to promote cleaner, more meaningful markup.

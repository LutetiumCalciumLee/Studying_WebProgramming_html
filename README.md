# Chapter 2 . HTML5 Basic Document Contents

### HTML5 Document Structure

- Explains the standard structure using `<html>`, `<head>`, and `<body>` tags.
- The `<head>` contains metadata, the title, and links to scripts or styles.
- The `<body>` holds all visible content.

---

### Core Tags and Formatting

- Use headings (`<h1>`–`<h6>`), paragraphs (`<p>`), line breaks (`<br>`), and horizontal rules (`<hr>`).
- Text formatting tags include `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, and `<sup>` for structuring and emphasizing text.

---

### Block vs. Inline Elements

- **Block-level tags:** e.g., `<div>`, `<p>`, `<ul>`, `<table>` — start on new lines and occupy the full width.
- **Inline tags:** e.g., `<span>`, `<a>`, `<img>`, `<strong>` — flow within lines of text.

---

### Lists

- Ordered lists (`<ol>`), unordered lists (`<ul>`), and definition lists (`<dl>`) organize items and definitions.
- Supports nested lists for complex structures.

---

### Tables

- Create tables using `<table>`.
- Structural tags: `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, and `<td>`.
- Images can be embedded within tables.

---

### Images

- Use the `<img>` tag and its attributes (`src`, `alt`, `width`, `height`) to insert images and ensure accessibility.

---

### Hyperlinks

- The `<a>` tag creates links to external sites, internal anchors, and downloadable files.
- The `target` attribute controls link behavior (`_blank`, `_self`, `_parent`, `_top`, or named frames).

---

### Anchors and Internal Navigation

- Use `id` attributes and anchor links (`<a href="#section-id">`) for navigation within the same page.

---

### Special Characters and Symbols

- Use HTML entities (e.g., `&lt;`, `&gt;`, `&copy;`, `&sum;`) to display reserved or special symbols.

---

### Metadata and External Resources

- Metadata tags like `<meta>`, `<title>`, `<link>`, and `<style>` define encoding, authorship, SEO, and link external resources.
- These tags are placed within the `<head>`.

---

### Media Embedding

- Use `<audio>` and `<video>` tags to embed media files, supporting multiple formats and playback controls.
- The `<iframe>` tag embeds other web pages or documents.

---

### Frame and Window Relationships

- Frames and the `target` attribute specify where linked documents open.
- Browser windows and frames have hierarchical relationships (`parent`, `child`, `top`).

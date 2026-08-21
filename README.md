## 1. Document Structure Tags
| Tag | माहिती |
|---|---|
| `<!DOCTYPE html>` | HTML5 document असल्याचं सांगतो |
| `<html>` | Root tag, सगळं content यात |
| `<head>` | न दिसणारा metadata भाग |
| `<body>` | दिसणारा actual content |
| `<title>` | Browser tab वरचं title |
| `<meta>` | Charset, viewport, description वगैरे info |
| `<link>` | CSS file किंवा icon जोडायला |
| `<style>` | Internal CSS लिहायला |
| `<script>` | JavaScript जोडायला |
| `<base>` | सगळ्या relative links साठी base URL ठरवतो |

## 2. Text Content Tags
| Tag | माहिती |
|---|---|
| `<h1>` to `<h6>` | Headings, h1 सर्वात मोठं/important |
| `<p>` | Paragraph |
| `<br>` | Line break |
| `<hr>` | Horizontal line |
| `<pre>` | जसच्या तसं spacing/formatting ठेवतो |
| `<blockquote>` | Quote दाखवायला (indent होतो) |
| `<q>` | Short inline quote |
| `<abbr>` | Abbreviation, hover वर full form दिसतं |
| `<address>` | Contact info साठी |
| `` | एखाद्या creative work चा reference |
| `<code>` | Code snippet दाखवायला |
| `<kbd>` | Keyboard input दाखवायला |
| `<samp>` | Program चा output दाखवायला |
| `<var>` | Variable name दाखवायला |
| `<time>` | Date/time दाखवायला (machine-readable) |

## 3. Text Formatting Tags
| Tag | माहिती |
|---|---|
| `<b>` | Bold (फक्त style) |
| `<strong>` | Bold + important meaning |
| `<i>` | Italic (फक्त style) |
| `<em>` | Italic + emphasis meaning |
| `<u>` | Underline |
| `<s>` | Strikethrough (yापुढे relevant नाही असा text) |
| `<del>` | Delete केलेला text |
| `<ins>` | नवीन add केलेला text |
| `<mark>` | Highlight |
| `<small>` | छोटा text |
| `<sub>` | Subscript (H₂O मधलं 2) |
| `<sup>` | Superscript (x² मधलं 2) |
| `<span>` | Inline generic container |

## 4. Lists
| Tag | माहिती |
|---|---|
| `<ul>` | Unordered (bullet) list |
| `<ol>` | Ordered (numbered) list |
| `<li>` | List item |
| `<dl>` | Description list |
| `<dt>` | Description term |
| `<dd>` | Description details |

## 5. Links & Navigation
| Tag | माहिती |
|---|---|
| `<a>` | Hyperlink |
| `<nav>` | Navigation links चा section |

## 6. Images & Media
| Tag | माहिती |
|---|---|
| `<img>` | Image दाखवायला |
| `<figure>` | Image/media + caption ला group करतो |
| `<figcaption>` | Figure ची caption |
| `<audio>` | Audio player |
| `<video>` | Video player |
| `<source>` | Audio/video/picture साठी multiple sources |
| `<track>` | Video साठी subtitles/captions |
| `<picture>` | Responsive images (screen size नुसार) |
| `<map>` | Image वर clickable areas बनवायला |
| `<area>` | Map मधला clickable region |

## 7. Tables
| Tag | माहिती |
|---|---|
| `<table>` | Table container |
| `<thead>` | Table चा header भाग |
| `<tbody>` | Table चा body भाग |
| `<tfoot>` | Table चा footer भाग |
| `<tr>` | Table row |
| `<th>` | Header cell |
| `<td>` | Data cell |
| `<caption>` | Table ची caption |
| `<colgroup>` | Columns group करायला |
| `<col>` | Individual column ला style द्यायला |

## 8. Forms
| Tag | माहिती |
|---|---|
| `<form>` | Form container |
| `<input>` | Text, email, password, checkbox वगैरे input |
| `<textarea>` | Multi-line text input |
| `<button>` | Clickable button |
| `<select>` | Dropdown |
| `<option>` | Dropdown मधला एक choice |
| `<optgroup>` | Options ला group करायला |
| `<label>` | Input ला नाव/label देतो |
| `<fieldset>` | Related form elements ला group करतो |
| `<legend>` | Fieldset ची title |
| `<datalist>` | Input साठी suggestions list |
| `<output>` | Calculation चा result दाखवायला |
| `<progress>` | Progress bar |
| `<meter>` | Fixed range मधली value (जसं battery %) |

## 9. Semantic Layout Tags
| Tag | माहिती |
|---|---|
| `<header>` | Page/section चा header |
| `<footer>` | Page/section चा footer |
| `<main>` | Page चा मुख्य unique content |
| `<section>` | Content चा logical भाग |
| `<article>` | Independent, self-contained content (blog post वगैरे) |
| `<aside>` | Side content (sidebar, ads) |
| `<div>` | Generic block container |

## 10. Embedded Content
| Tag | माहिती |
|---|---|
| `<iframe>` | दुसरा webpage embed करायला |
| `<embed>` | External content embed करायला (plugin content) |
| `<object>` | External resource embed करायला (PDF वगैरे) |
| `<canvas>` | JS ने drawing/games बनवायला |
| `<svg>` | Vector graphics |

## 11. Interactive Elements
| Tag | माहिती |
|---|---|
| `<details>` | Collapsible content (JS शिवाय) |
| `<summary>` | Details चा visible heading |
| `<dialog>` | Popup/modal box |

## 12. Other Useful Tags
| Tag | माहिती |
|---|---|
| `<template>` | Hidden content, JS ने नंतर वापरण्यासाठी |
| `<noscript>` | JS off असेल तर दाखवायचा content |
| `<wbr>` | Word कुठे break करायचा ते सुचवतो |
| `<data>` | Content ला machine-readable value देतो |
| `<bdi>` | Text चा direction वेगळा isolate करतो |
| `<bdo>` | Text ची direction override करतो (RTL/LTR) |

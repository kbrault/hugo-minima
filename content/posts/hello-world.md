---
title: "Hello, world!"
date: 2026-05-17T09:00:00-04:00
---

## 1. Typography & Text Formatting

This is a standard paragraph demonstrating default body text. Modern web design relies on high legibility, balanced line height, and appropriate contrast.

* **Bold text** using `**bold**` or `__bold__`.
* *Italic text* using `*italic*` or `_italic_`.
* ***Bold and italic text*** using `***text***`.
* ~Strikethrough~ using `~strikethrough~` or ~~double strikethrough~~ using `~~text~~`.
* Highlighted text using the <mark>HTML mark tag</mark>.
* Text in <sup>superscript</sup> (`<sup>`) and <sub>subscript</sub> (`<sub>`).

---

## 2. Headings

Headings help structure the document and test visual hierarchy as well as the Table of Contents (TOC).

### Heading Level 3 (H3)
Text under a level 3 heading allows you to verify top and bottom margins.

#### Heading Level 4 (H4)
A more subtle subheading, often used for technical sub-sections.

##### Heading Level 5 (H5)
A low-level typographic heading.

<h6>Heading Level 6 (H6)</h6>
The smallest heading level available.

---

## 3. Lists

### Unordered List
* First item in the list
* Second item with a sub-list:
  * Sub-item A
  * Sub-item B
    * Deep nested item 1
* Third item

### Ordered List
1. Step 1: Initialize the project
2. Step 2: Configure the `config.toml` file
3. Step 3: Deployment:
   1. Build the site (`hugo`)
   2. Transfer files
4. Step 4: Verification

### Task List
- [x] Install Hugo Extended
- [x] Choose a theme
- [ ] Customize CSS / SCSS styles
- [ ] Write the first article

### Definition List (HTML `<dl>`)
Term 1
: Definition for the first term with clear explanations.

Term 2
: Definition for the second term.

---

## 4. Blockquotes & Callouts

### Single Blockquote
> "Simplicity is the ultimate sophistication."  
> — **Leonardo da Vinci**

### Nested Blockquotes
> This is a first-level blockquote.
>> This is a nested blockquote inside the first one.
>
> Back to the first-level blockquote.

---

## 5. Code & Syntax Highlighting

### Inline Code
Use the `printf()` function in Go or declare a variable like `const express = require('express');` in JavaScript.

### Code Block Without Language Specifier

```
Default configuration:
server_name: localhost
port: 8080
debug: true

```

### Python
```python
import os

def check_hugo_env():
    env = os.getenv("HUGO_ENV", "development")
    print(f"Current environment: {env}")

if __name__ == "__main__":
    check_hugo_env()

```

### JavaScript / TypeScript

```typescript
interface User {
  id: number;
  name: string;
  role: 'admin' | 'user';
}

const currentUser: User = {
  id: 1,
  name: "Alice",
  role: "admin"
};

console.log(`Connected user: ${currentUser.name}`);

```

### HTML / CSS

```html
<div class="card card-featured">
  <h2 class="card-title">Card Title</h2>
  <p class="card-text">This is an example of a visual component in CSS.</p>
</div>

<style>
  .card {
    padding: 1.5rem;
    border-radius: 8px;
    background-color: #f4f4f5;
  }
</style>

```

---

## 6. Tables

Tables allow you to check border styles, headers, and text alignment.

| Left Aligned | Center Aligned | Right Aligned | Numeric Value |
| --- | --- | --- | --- |
| Item A | Content 1 | $120.00 | 15 |
| Item B | Content 2 | $1,450.50 | 102 |
| Item C | Content 3 | $45.99 | 8 |
| **Total** | — | **$1,616.49** | **125** |

---

## 7. Media & Images

### Standard Image
![Test Image Caption](https://picsum.photos/800/400 "Hover Title Example")

### Image with Link
[![Clickable Banner](https://picsum.photos/800/200)](https://gohugo.io)

---

## 8. Mathematics & Equations (KaTeX / MathJax)

If your theme supports MathJax or KaTeX, here are rendering examples:

Inline equation: $\lim_{x \to \infty} \frac{1}{x} = 0$

Block equation:

$$f(x) = \int_{-\infty}^{\infty} \hat{f}(\xi)\,e^{2\pi i \xi x}\,d\xi$$

$$A = \begin{pmatrix}
a & b \\
c & d
\end{pmatrix}$$

---

## 9. Native Hugo Shortcodes

Hugo provides built-in shortcodes to embed rich media out of the box.

### `figure` Shortcode

{{< figure src="https://picsum.photos/700/350" alt="Hugo figure example" caption="Figure 1: Example image using Hugo's native figure shortcode." title="Figure Title" >}}
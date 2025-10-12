## Section 4: Learn HTML

### Lecture 2: Emmet, Headings, Lists, Images, and Inline vs Block Elements

---

### 1. Key Idea (English)

This lecture focuses on **writing HTML faster using Emmet**, understanding **headings, paragraphs, lists**, and adding **images and links**. You’ll also learn the difference between **block-level** and **inline elements** and why this matters for webpage layout.

---

### 2. Emmet: Faster HTML Writing

- **Emmet** is a VS Code built-in plugin that lets you generate HTML code quickly using **abbreviations**.
- Example abbreviations:
  - `h1>lorem6` → Creates an `<h1>` tag with 6 words of Lorem Ipsum.
  - `ul>li*3` → Creates an unordered list with 3 list items.
  - `div>ul>li` → Creates nested elements automatically.

**Example: Generate heading and paragraph**

```html
<h1>Lorem ipsum dolor sit amet.</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
```

_Use `Tab` key after typing abbreviation to expand._

---

### 3. Headings and Paragraphs

- HTML has **six levels of headings**: `<h1>` to `<h6>`
- `<h1>` → Most important
- `<h2>` → Less important
- `<p>` → Paragraph of text

**Example:**

```html
<h1>Main Title</h1>
<h2>Sub Title</h2>
<p>This is a paragraph.</p>
```

**Key Concept:** Headings define **content hierarchy**, not font size (CSS controls size).

---

### 4. Lists

- **Unordered List (`<ul>`)** → Items with bullets
- **Ordered List (`<ol>`)** → Items with numbers
- List items use `<li>` tag

**Example:**

```html
<ul>
  <li>Apple</li>
  <li>Orange</li>
</ul>

<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

**Tip:** Use multiplication in Emmet: `li*3` for 3 list items.

---

### 5. Adding Images and Links

- **Image**: `<img src="path" alt="description">`
- **Link**: `<a href="URL">Text</a>`
- **Mail link**: `<a href="mailto:email@example.com">Email Me</a>`
- **Tel link**: `<a href="tel:+1234567890">Call Me</a>`

**Example:**

```html
<img src="images/HC.png" alt="Screenshot" width="300" />
<a href="https://checkcode.com">Go to CheckCode</a>
```

---

### 6. HTML Elements, Tags, and Attributes

- **Element** = `<tag>content</tag>` (includes opening, closing, content)
- **Tag** = Just `<tag>`
- **Attributes** = Properties inside a tag like `src`, `alt`, `href`, `width`, `title`

**Example:**

```html
<h1 title="Main Heading">Welcome</h1>
<img src="image.png" alt="Example Image" width="300" />
```

- `title` → Tooltip text
- `src` → Image source
- `alt` → Image description (for accessibility)

---

### 7. Block vs Inline Elements

| Type        | Behavior                                    | Examples                                         |
| ----------- | ------------------------------------------- | ------------------------------------------------ |
| Block-level | Takes full width, starts on new line        | `<h1>` to `<h6>`, `<p>`, `<div>`, `<ul>`, `<ol>` |
| Inline      | Stays within line, does not take full width | `<a>`, `<img>`, `<strong>`, `<em>`, `<b>`, `<i>` |

**Example:**

```html
<h1>Heading</h1>
<!-- Block -->
<p>This is a <strong>bold</strong> word inline.</p>
<!-- Inline inside block -->
<img src="logo.png" alt="Logo" />
<!-- Inline -->
```

**Tip:** Use browser **Inspect** tool to check element type and spacing.

---

### 8. Inline Text Emphasis

- `<strong>` → Important, bold text (semantic for accessibility)
- `<b>` → Bold (visual only)
- `<em>` → Emphasized text, italic (semantic)
- `<i>` → Italic (visual only)

**Example:**

```html
<p>Pay <strong>attention</strong> to this <em>important</em> part.</p>
```

---

### 9. Hinglish Recall

- Emmet = VS Code shortcut, type abbreviation + Tab
- Headings = `<h1>` to `<h6>`, Paragraph = `<p>`
- Lists = `<ul>` (unordered) & `<ol>` (ordered), with `<li>`
- Images = `<img src="..." alt="...">`
- Links = `<a href="...">Text</a>`
- Elements = Tag + content, Attributes = `src`, `alt`, `href`, `title`
- Block-level = new line, full width; Inline = stays in line
- Inline emphasis = `<strong>`/`<em>` for importance, `<b>`/`<i>` for visual only

---

### ✅ Quick Summary

- Emmet = Faster HTML coding
- Headings define **importance**, not size
- Lists = Ordered & Unordered
- Images and links need correct **paths**
- Elements = Tags + content; Attributes add properties
- Block-level = Full width, Inline = within line
- Use `<strong>` & `<em>` for semantic emphasis, `<b>` & `<i>` for visuals

---

## ⏭️ Next Lecture

➡️ Forms, Inputs, and Advanced HTML Attributes → Learn how to capture user data and make interactive webpages.

## Section 4: Learn HTML

### Lecture 1: What is HTML

---

### 1. Key Idea

HTML (**HyperText Markup Language**) is the foundation of every web page. It defines the **structure** of content on the web using **tags**. These tags tell the browser what each piece of content means — for example, headings, paragraphs, images, links, and more.

---

### 2. Origin and Purpose

- HTML was created so that researchers could share **documents** (like research papers) with headings, paragraphs, and tables over the web.
- It uses **tags** to mark up different parts of a document, so browsers know how to display them.
- Most tags work as **containers** — they start with an **opening tag** (e.g., `<h1>`) and end with a **closing tag** (e.g., `</h1>`).

**Example:**

```html
<h1>Hello World</h1>
```

---

### 3. Structure of an HTML Document

Every HTML document follows a fixed structure that ensures consistent behavior across browsers (Chrome, Firefox, Safari, etc.).

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

**Breakdown:**

- `<!DOCTYPE html>` → Tells the browser this is an HTML5 document.
- `<html>` → The root tag for all HTML content.
- `<head>` → Contains **metadata** (data about the webpage) such as the title, favicon, charset, etc.
- `<body>` → Contains **visible content** shown on the browser.

---

### 4. Head vs Body

| Section  | Purpose                             | Example Content                     |
| -------- | ----------------------------------- | ----------------------------------- |
| `<head>` | Metadata, title, SEO, links, styles | `<title>My Website</title>`         |
| `<body>` | Visible content                     | `<h1>Welcome</h1>`, `<p>Hello!</p>` |

---

### 5. Creating HTML Files

1. Open VS Code and create a folder (e.g., `HTML`).
2. Inside it, create your first file: `index.html`.
3. Type `!` and press `Tab` → VS Code auto-generates **boilerplate HTML** (thanks to **Emmet**).
4. This includes `doctype`, `<html>`, `<head>`, and `<body>` automatically.

**Why `index.html`?**

> Web servers automatically pick `index.html` as the default homepage.

---

### 6. Using Live Server

- Install **Live Server** extension in VS Code.
- Right-click your HTML file → choose **Open with Live Server**.
- It opens the page in your browser and refreshes automatically whenever you save.

---

### 7. Example Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello from Hitesh!</h1>
    <p>This is my first HTML document.</p>
  </body>
</html>
```

Output: The browser shows a white page with **Hello from Hitesh!** as a heading and a paragraph below it.

---

### 8. Hinglish Recall

- HTML = **HyperText Markup Language** → Web ka structure.
- Scientist logon ne HTML banaya tha taaki research papers online share kar sakein.
- Har tag ek **container** hota hai – start hota hai `<h1>` se, end hota hai `</h1>` se.
- HTML document ke do main parts hote hain: **head** aur **body**.
- Head mein metadata, title, favicon hota hai.
- Body mein jo user ko dikhana hai wo hota hai.
- File ka naam `index.html` rakhte hain kyunki server usse default page samajhta hai.
- Live Server se instantly browser mein changes dikhte hain.

---

### ✅ Quick Summary

- HTML = Structure of a webpage.
- Every page = `<!DOCTYPE html>` + `<html>` + `<head>` + `<body>`.
- Tags mostly come in pairs: opening + closing.
- Head → metadata, Body → visible content.
- Use Emmet shortcut (`!` + Tab) for boilerplate.
- Use Live Server to preview instantly.

---

## ⏭️ Next Lecture

➡️ Emmet, Headings, and Block vs Inline Elements → Learn how to write HTML faster and

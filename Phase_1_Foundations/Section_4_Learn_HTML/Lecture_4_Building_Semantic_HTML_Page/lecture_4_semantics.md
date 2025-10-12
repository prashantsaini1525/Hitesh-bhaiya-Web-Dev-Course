## Section 4: Learn HTML

### Lecture: Semantic Structure and Accessibility

---

### 🧠 Key Idea

Now that you’ve learned HTML basics (tags, lists, tables, forms), it’s time to **build a full web page** using **semantic HTML** — making your structure meaningful, accessible, and screen-reader friendly.

---

### 📘 What Are Semantic Tags?

Semantic tags describe **the meaning of the content** inside them. Earlier, developers used only `<div>` everywhere, which made pages unreadable for assistive tech. HTML5 introduced tags like `<header>`, `<main>`, `<article>`, `<footer>` — each having a clear purpose.

**Example Structure:**

```
<header> → Navigation / Branding
<nav> → Menu links
<main> → Page content
<article> → Independent pieces (like blog posts)
<section> → Thematic grouping inside article/main
<footer> → Contact info, copyright
```

---

### 🧩 Basic Website Layout

Most websites follow this structure:

| Area    | Tag        | Description                      |
| ------- | ---------- | -------------------------------- |
| Top Bar | `<header>` | Site title, logo, or heading     |
| Menu    | `<nav>`    | Navigation links                 |
| Content | `<main>`   | Core part of the site            |
| Sidebar | `<aside>`  | Optional side content            |
| Bottom  | `<footer>` | Copyright, address, social links |

This isn’t mandatory, but using it improves **accessibility**, **SEO**, and **readability**.

---

### 🏗️ Let’s Build It Step-by-Step

#### 1️⃣ Start the HTML File

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gym Workout</title>
  </head>
  <body></body>
</html>
```

#### 2️⃣ Add a Header

```html
<header>
  <hgroup>
    <h1>Learn to Create Websites</h1>
    <h2>with Hitesh — Build Your Own Projects</h2>
  </hgroup>
</header>
```

> 💡 Use `<hgroup>` to logically combine related headings (rarely used but valid).

#### 3️⃣ Add Navigation

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About Us</a></li>
    <li><a href="#">Contact Us</a></li>
  </ul>
</nav>
```

> 🔗 `<nav>` defines navigation links. Often placed **inside** `<header>`.

#### 4️⃣ Main Content Area

```html
<main>
  <article>
    <hgroup>
      <h1>Welcome to Our Gym Page</h1>
      <h2>Your Fitness Journey Begins Here</h2>
    </hgroup>

    <time datetime="2024-08-02">August 2, 2024</time>

    <section>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quia.
      </p>
    </section>

    <section>
      <p>Here’s some JavaScript code we use:</p>
      <code>console.log('Hitesh, how does it look?');</code>
    </section>
  </article>
</main>
```

> 🕒 Use `<time>` for dates/timestamps. `<code>` tag is perfect for snippets.

#### 5️⃣ Footer and Address

```html
<footer>
  <address>
    <a href="mailto:info@gymworkout.com">info@gymworkout.com</a>
  </address>
  <p>&copy; 2024 ChaiCode</p>
</footer>
```

> © symbol created using `&copy;` (UTF-8 encoded). Always mention `<meta charset="UTF-8">` in the head.

---

### 🧰 Extra Tools Mentioned

- **Prettier Extension** → Auto-formats your code in VS Code.
  - Install `Prettier - Code Formatter`
  - Go to _Settings → Default Formatter → esbenp.prettier-vscode_
  - Enable: _Format on Save_ ✅

---

### 💬 Hinglish Recall

- Pehle sab kuch `<div>` se hota tha — ab semantics se structure clear hota hai.
- `<header>`, `<nav>`, `<main>`, `<footer>` sirf containers hain (structure ke liye, style ke liye nahi).
- Accessibility aur SEO dono improve hote hain semantic HTML se.
- `<time>` aur `<code>` jaise tags bhi semantics mein aate hain.
- UTF-8 encoding → special characters (©, ™, ®) ke liye zaroori.

---

### ✅ Quick Summary

| Concept           | Purpose                                              |
| ----------------- | ---------------------------------------------------- |
| Semantic Tags     | Make structure meaningful for users & screen readers |
| Prettier          | Auto-format HTML beautifully                         |
| Global Attributes | `id`, `class`, `title` used across all tags          |
| Accessibility     | Helps screen readers navigate                        |
| UTF-8             | Handles special symbols correctly                    |

---

## ⏭️ Next Lecture

➡️ ARIA Labels and Accessibility Enhancements → We’ll explore how ARIA roles make semantic HTML even more inclusive. HTML structure.

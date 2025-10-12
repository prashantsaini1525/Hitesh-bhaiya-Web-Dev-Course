# Lecture: CSS Basics(Inline, Internal & External)

## 🎯 **Objective**

Learn the **three main ways** to style web pages with CSS: inline, internal, and external stylesheets. Understand how CSS selects and styles elements using selectors, IDs, and classes.

---

## 🧠 **Key Concepts & Flow**

### 💡 CSS = Selecting + Styling

- The **whole job** of CSS: **Select** an element → **Style** the element.
- CSS = _Cascading Style Sheet_ → “Cascading” means styles **flow down** from parent to child.

### 🎨 Design Priorities (Pro Tips from Hitesh)

| Rank | Element        | Importance                                                          |
| ---- | -------------- | ------------------------------------------------------------------- |
| 🥇 1 | **Fonts**      | Most important — defines the whole website’s vibe.                  |
| 🥈 2 | **Images**     | Optimized, well-placed visuals boost aesthetics.                    |
| 🥉 3 | **Components** | Buttons, cards, lists — look good _after_ fonts & images are right. |

> 🧩 So remember: Good fonts + good images → 70% of great design already done!

---

## 🧩 **Step 1: Inline Styling**

👉 Styling inside the HTML tag using the `style` attribute.

```html
<h1 style="color: orange;">Hello CSS!</h1>
```

✅ Used for **quick experiments**.
❌ Not recommended for large projects (messy & hard to maintain).

---

## 🧩 **Step 2: Internal Styling**

👉 Add `<style>` inside the `<head>` tag.

```html
<style>
  h2 {
    color: brown;
  }
</style>
```

✅ Great for **small demo pages** or isolated testing.
❌ Doesn’t scale well for multiple pages.

You can also **target multiple elements** using commas:

```css
h2,
p {
  color: brown;
}
```

---

## 🧩 **Step 3: External Stylesheet**

👉 Create a new file named `style.css` and link it in HTML.

```html
<link rel="stylesheet" href="style.css" />
```

**style.css:**

```css
p {
  font-weight: bold;
}
```

✅ Clean, reusable, and **industry standard**.

---

## 🎯 **Selectors: Element, Class & ID**

| Selector Type | Example                        | Use Case                          |
| ------------- | ------------------------------ | --------------------------------- |
| **Element**   | `p { color: brown; }`          | Targets all `<p>` tags            |
| **Class**     | `.brownText { color: brown; }` | Reusable across multiple elements |
| **ID**        | `#mainTitle { color: red; }`   | Unique to one element only        |

💬 **Rule:** Use **class** for reusable styling. Use **ID** for unique elements only.

```html
<h2 class="brownText">Heading</h2>
<p class="brownText">Paragraph</p>
```

```css
.brownText {
  color: brown;
}
```

---

## ⚙️ **Specificity Basics (Priority Rules)**

| Priority            | Selector Type             |
| ------------------- | ------------------------- |
| 🥇 Inline style     | `<h1 style="color:red;">` |
| 🥈 ID selector      | `#main {}`                |
| 🥉 Class selector   | `.title {}`               |
| 🪶 Element selector | `p {}`                    |

> Inline styles **override** everything. IDs beat classes. Classes beat tags.

---

## 🧩 **Styling Properties Practiced**

```css
p {
  font-weight: bold;
  font-size: 25px;
  margin: 0 auto;
  padding: 100px;
}
```

🪄 **Try changing:**

- `font-size: 25px;` → `font-size: 1.5rem;`
- `margin: 0 auto;` → centers the content
- `padding: 100px;` → creates spacing inside the element

---

## 🧩 **Common Mistakes to Avoid**

- Forgetting to link your CSS file → _no styling will appear!_
- Using too many inline styles → _impossible to maintain!_
- Confusing `id` (`#`) with `class` (`.`)

---

## 🔁 **Recap**

✅ CSS = Select → Style
✅ 3 Styling Methods → Inline, Internal, External
✅ Selectors → Element, Class, ID
✅ Specificity → Inline > ID > Class > Tag
✅ Practice spacing, color, and text properties

---

## 🧩 **Mini Challenge (Try in VS Code)**

Create a page with:

- 1 heading, 1 subheading, 1 paragraph
- Style them **each in a different way** (inline, internal, external)

---

## 🧠 **Hinglish Recap**

> CSS ka main kaam simple hai — element ko **select karo aur style lagao**.
> Teen tareeke: Inline (seedha tag me), Internal (head ke andar), External (alag file me).
> Classes reuse hoti hain, IDs unique hoti hain.
> Aur haan — **font aur image** decide karte hain ki website sundar lagegi ya nahi 😎

---

## ⏭️ Next Lecture

➡️ Building a web project - Login page**

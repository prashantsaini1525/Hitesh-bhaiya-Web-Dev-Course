# Lecture: Build a custom coming soon template Project

## 🎯 Objective

Build a custom “Coming Soon” landing page using HTML & CSS — learning structure, layout, gradients, flexbox centering, forms, buttons, shadows, transitions, and Google Fonts.

---

## 🧠 Key Concepts & Flow

1. Real-world project: simple freelance-style landing page.
2. HTML structure: `container → content → image + h1 + paragraph + form`.
3. Form setup: email input + submit button, with ID `notify-form`.
4. CSS basics: reset margin/padding, font-family, height 100%.
5. Background: linear-gradient(angle, color1, color2).
6. Flexbox layout: `display: flex`, `justify-content: center`, `align-items: center`.
7. Content styling: centered text, rgba background, padding, rounded corners.
8. Responsive width: `max-width` 400px.
9. Form/input styling: flex column, padding, subtle border, rounded corners.
10. Button styling: color, hover effects, transitions, cursor pointer, shadow.
11. Box shadow: subtle 3D look.
12. Google Fonts: custom typography for modern look.

---

## 🪄 Real-life Analogy

The page is like a “store shutter” with a glowing “Opening Soon!” board — minimal, clean, and builds curiosity.

---

## 🧩 Examples (Illustrative)

**HTML:**

```html
<div class="container">
  <div class="content">
    <img src="images/cup-logo.png" class="logo" alt="Chai Logo" />
    <h1>Coming Soon</h1>
    <p>We are working hard to bring something amazing. Stay tuned!</p>
    <form id="notify-form">
      <input type="email" placeholder="Enter your email" required />
      <button>Notify Me</button>
    </form>
  </div>
</div>
```

---

**CSS:**

```css
body {
  margin: 0;
  padding: 0;
  font-family: "Arial", sans-serif;
}
.container {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(135deg, #6c63ff, #896cff);
}
.content {
  background: rgba(255, 255, 255, 0.9);
  text-align: center;
  padding: 2rem;
  border-radius: 10px;
  max-width: 400px;
}
.logo {
  width: 150px;
  object-fit: contain;
}
button {
  background: #6c63ff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
button:hover {
  background: #574b90;
}
```

---

## ⚙️ Pro Tips / Mistakes to Avoid

- Always set `max-width` for responsive design.
- Use Flexbox for proper centering.
- rgba() for transparency.
- Keep hover transitions short (0.2-0.3s).
- Subtle box shadows, don’t overdo.
- Test hover + focus states on form elements.

---

## 🧠 Hinglish Recap

Ye mini landing page “Coming Soon” show karta hai. HTML se structure, CSS se gradient, flex centering, hover aur shadow effects. Bas JS add karo aur ready for real world.

---

## 🧾 Short Notes (Interview Version)

- Project: Coming Soon Landing Page
- Tech: HTML5, CSS3 (Flexbox, Gradient, Transition)
- Features: Centered layout, responsive width, email form, hover effects
- Key learning: Real-world CSS, box-shadow, linear-gradient
- Bonus: Google Fonts for UI polish

---

## 🔁 Recap Summary

✅ Built a real-world landing page
✅ Learned Flexbox centering, gradients, rgba(), responsive design
✅ Practiced button hover + transition
✅ Added polish: shadows & fonts

---

## ⏭️ Next Lecture

➡️ Flexbox Masterclass (deeper dive into layout & alignment)

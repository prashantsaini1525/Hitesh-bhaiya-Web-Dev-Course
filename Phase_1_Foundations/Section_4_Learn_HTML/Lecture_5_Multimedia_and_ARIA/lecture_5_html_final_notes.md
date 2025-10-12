## Section 4: Learn HTML

### Lecture: HTML — Final Lecture Notes

---

## 🏁 Overview

This lecture wraps up the **HTML section** — a huge milestone! The goal here is to ensure you’re _comfortable and confident_ with HTML fundamentals before jumping into CSS, JavaScript, and beyond.

HTML isn’t about memorizing every tag — it’s about _understanding structure, semantics, and accessibility_. You’ll master the rest through practice and projects.

---

## 🎯 Key Takeaways

### 1. **HTML Learning Recap**

- You’ve covered HTML structure, tags, forms, tables, and semantics.
- If something feels unclear — it’s normal! Revisit docs, code more, and keep experimenting.
- Mastery happens through repetition, not cramming.

---

### 2. **Working with Media in HTML**

#### 🖼️ Adding Images

```html
<img src="images/hc.png" alt="Profile photo" width="200" title="Hitesh" />
```

- `src` → path to the image file.
- `alt` → fallback text if the image doesn’t load.
- `title` → text shown on hover.
- Common formats: `.png`, `.jpeg`, `.svg`, `.webp` — each with different compression & quality benefits.

#### 🖼️ Using the `<figure>` and `<figcaption>` Tags

```html
<figure>
  <img src="images/hc.png" alt="Profile photo" width="200" />
  <figcaption>Hitesh Choudhary</figcaption>
</figure>
```

- `<figure>` wraps media and its description as a **semantic unit**.
- `<figcaption>` provides a caption that’s connected to the media.
- Helps with **accessibility and structure**.

---

### 3. **Embedding Video Content**

```html
<video src="images/demo.mp4" width="400" controls></video>
```

- `controls` → enables play/pause UI.
- `width` → resizes video.
- You can add attributes like `autoplay`, `loop`, and `muted`.

#### 🎛️ Customizing Video Controls

```html
<video
  src="demo.mp4"
  controls
  controlslist="nodownload nofullscreen noremoteplayback"
></video>
```

- The `controlslist` attribute limits default controls (e.g., remove download or fullscreen).
- Some customizations require **JavaScript** to work properly.

---

### 4. **Adding Audio Content**

```html
<audio src="music.mp3" controls></audio>
```

- Similar to video — you can include audio playback controls.
- Works well for podcasts, notifications, and background music.

---

### 5. **ARIA and Accessibility**

- **ARIA** = _Accessible Rich Internet Applications_.
- Adds attributes that help assistive technologies (like screen readers) understand your site.

#### Examples:

```html
<div role="navigation"></div>
<div
  role="progressbar"
  aria-valuenow="50"
  aria-valuemin="0"
  aria-valuemax="100"
></div>
```

- `role` defines the purpose of an element.
- `aria-*` attributes communicate state and structure.

📘 Use ARIA mainly in **government, financial, or inclusive web apps** where accessibility is critical.

---

### 6. **Documentation You Should Use**

- **[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)** → Deep and detailed documentation.
- **[W3Schools](https://www.w3schools.com/html/)** → Simplified examples for quick reference.

🧠 Pro Tip: MDN is your long-term go-to. W3Schools is good for beginners.

---

### 7. **Practice and Exploration**

- Practice through coding exercises and mini HTML projects.
- Focus on keyboard shortcuts and editor familiarity.
- Don’t memorize — _build more_.

---

## 💡 Summary

- ✅ You’ve officially completed the **HTML section** 🎉
- You understand **structure**, **semantics**, and **accessibility**.
- You can confidently handle **images, videos, audio**, and **ARIA basics**.
- Next: Move into **CSS** — where your pages start to _look alive_!

> 💬 _“HTML gives your site bones. CSS adds the skin and JavaScript gives it a brain.”_

---

## ⏭️ Next Lecture

➡️ HTML QUIZ

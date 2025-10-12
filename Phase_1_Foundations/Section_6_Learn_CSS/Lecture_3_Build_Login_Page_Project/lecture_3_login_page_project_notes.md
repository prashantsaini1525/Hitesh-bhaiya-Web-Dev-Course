# Lecture: Building a web project - Login page

## 🎯 **Objective**

Build a simple login page using HTML and CSS. Learn how to structure content, apply Flexbox for centering, and style forms, buttons, and cards.

---

## 🧠 **Key Concepts & Flow**

### 💡 Project-based Learning

- **Faster learning** happens when you **build real projects**.
- Start simple: HTML content → CSS styling → Flexbox centering → Interactive elements.
- Don’t worry if you understand 10–15% now; confidence grows with practice.

### 🧱 Layout Plan

- **Background:** Dark
- **Card:** Centered, slightly rounded corners
- **Form:** Email, Password input fields, Login button
- **Styling:** Spacing, colors, font, hover effects

---

## 🧩 **Step 1: HTML Content**

```html
<div class="card">
  <h2>Login</h2>
  <form>
    <input type="email" placeholder="Email" />
    <input type="password" placeholder="Password" />
    <button type="submit">Login</button>
  </form>
</div>
```

✅ Create **div.card**, form with inputs, and a button.

---

## 🧩 **Step 2: Body & Flexbox Centering**

```css
body {
  margin: 0;
  padding: 0;
  height: 100vh; /* viewport height */
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #1a1a1a;
  font-family: Arial, Helvetica, sans-serif;
}
```

✅ Flexbox centers **.card** horizontally & vertically.

---

## 🧩 **Step 3: Styling the Card**

```css
.card {
  background-color: #2c2c2c;
  padding: 30px;
  border-radius: 10px;
  width: 300px;
  text-align: center;
}
```

✅ Rounded corners & padding give breathing room.

---

## 🧩 **Step 4: Styling Inputs**

```css
input {
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
  border-radius: 5px;
  border: none;
  background-color: #3a3a3a;
  color: white;
}
input::placeholder {
  color: #aaa;
}
```

✅ Inner spacing (padding) & margin bottom to separate fields.

---

## 🧩 **Step 5: Styling Button**

```css
button {
  width: 100%;
  padding: 10px;
  border-radius: 8px;
  border: none;
  background-color: #007bff;
  color: white;
  cursor: pointer;
  transition: background-color 0.3s;
}
button:hover {
  background-color: #0056b3;
}
```

✅ Hover effect adds interactivity.

---

## 🧠 **Hinglish Recap**

> Yeh project ka main goal hai ki tum **HTML aur CSS use karke ek real login page build karo**.
>
> Body ko flexbox se center karna sikho, inputs aur button ko style karo.
>
> Card ke liye padding, border-radius aur background color apply karo.
>
> Button hover effect aur input styling se design aur interactive lagega.
>
> Ye confidence deta hai ki **tum CSS aur Flexbox ke basics real-world projects me apply kar sakte ho 😎**.

---

## 🧩 **Assignment**

1. Change login page to **greenish theme** (dark background, card with green variations).
2. Create a **signup page**: First Name, Last Name, Email, Password, Signup button.
3. Share screenshot on Discord/Twitter/LinkedIn.

---

## ⏭️ Next Lecture

➡️ Masterclass on CSS selectors**

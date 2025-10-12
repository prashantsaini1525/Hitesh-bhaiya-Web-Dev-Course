# Section 3 – Basics of Web Development

## Lecture: How Web Applications Work (Flow Overview)

**Notes (Professional):**

- Before diving into coding (HTML, CSS, JS), it’s important to understand how web applications work.
- **Main Components:**

  - **Database** → stores data (e.g., user info, products, etc.)
  - **Server** → processes requests, interacts with database, sends responses
  - **Browser/Client** → user’s computer + browser (Chrome, Firefox, etc.)
  - **Technologies:**
    - HTML5 → structure of webpage
    - CSS3 → styling and layout
    - JavaScript → functionality and interactivity

- **Flow of a Web Application:**

  1. User makes a **request** (e.g., open homepage, login, signup).
  2. Server receives request and decides:
     - If data needed → checks **database**.
     - If public page → directly sends response.
  3. Server sends **response** to browser in layers:
     - Step 1: HTML → structure
     - Step 2: CSS → design
     - Step 3: JavaScript → interactivity & dynamic features
  4. Browser renders content and user interacts with the application.

- **Examples:**

  - Login page → server verifies details with DB.
  - Homepage → server sends HTML + CSS + JS.

- **Key Insight:**
  - Frontend engineers work mainly with HTML, CSS, JS (browser side).
  - Backend engineers work on server + database.
  - Both parts communicate through requests & responses.

---

**Hinglish Notes (Quick Recall):**

- Web app = Client (browser) ↔ Server ↔ Database.
- Request bhejta hai browser → Server check karta hai DB se → Response aata hai.
- Response steps:
  - Pehle HTML (structure)
  - Phir CSS (design)
  - Last mein JS (functionality)
- Frontend = Browser ka kaam (HTML, CSS, JS)
- Backend = Server + Database

---

✅ Big Picture: Har web app isi cycle pe chalta hai → Request → Server → DB → Response → Browser.

---

## ⏭️ Next Lecture

➡️ Frontend backend and APIs

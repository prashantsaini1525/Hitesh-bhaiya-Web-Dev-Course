## Section 4: Learn HTML

### Lecture 3: Tables and Forms

---

### 1. Key Idea (English)

HTML is primarily used for **displaying data** and **collecting user input**. This lecture focuses on:

- **Tables** – for structured, tabular data.
- **Forms** – for taking input from users, including text, emails, passwords, checkboxes, radio buttons, and dropdowns.

---

### 2. Tabular Data (Tables)

- Tables help organize data in **rows** and **columns**.
- HTML uses `<table>` for the table, `<tr>` for table rows, `<th>` for table headings, and `<td>` for table data.

**Example:**

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Email</th>
    <th>Date of Birth</th>
  </tr>
  <tr>
    <td>Hitesh</td>
    <td>hiteshmail.com</td>
    <td>02/02/2024</td>
  </tr>
  <tr>
    <td>Mister H</td>
    <td>h@hathesh.com</td>
    <td>05/05/2024</td>
  </tr>
</table>
```

- Tables can be styled later with **CSS**.
- Missing data will result in blank cells.

---

### 3. Forms (Collecting User Input)

- Forms allow users to input **text, emails, passwords, files, colors, dates, checkboxes, radio buttons, and more**.
- Basic structure:

```html
<form>
  <!-- Input fields here -->
</form>
```

**Creating a simple login form:**

```html
<form>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" />

  <label for="password">Password:</label>
  <input
    type="password"
    id="password"
    name="password"
    placeholder="Enter your password"
  />

  <button type="submit">Login</button>
</form>
```

---

### 4. Input Types

| Input Type      | Purpose                   |
| --------------- | ------------------------- |
| text            | Plain text input          |
| email           | Email address validation  |
| password        | Hidden text for passwords |
| checkbox        | Select multiple options   |
| radio           | Select one option         |
| select          | Dropdown options          |
| textarea        | Multi-line text input     |
| month/date/time | Pickers for date/time     |
| color           | Color selection           |
| file            | File upload               |

**Example of dropdown:**

```html
<label for="games">Choose a game:</label>
<select id="games">
  <option value="cricket">Cricket</option>
  <option value="baseball">Baseball</option>
</select>
```

---

### 5. Placeholder Attribute

- The `placeholder` attribute provides **hint text** inside an input field.

```html
<input type="text" placeholder="Enter your name" />
```

- Disappears when user types.

---

### 6. Key Takeaways

- HTML handles **displaying** (tables) and **collecting** (forms) data.
- Tables = `<table>`, `<tr>`, `<th>`, `<td>`.
- Forms = `<form>` + `<input>` + `<label>` + `<button>`.
- Input types validate user input and provide specific functionality.
- Attributes like `placeholder`, `name`, and `for` help improve usability.
- Learning HTML involves **practice** and **exploring MDN docs** for new tags as needed.

---

### 7. Hinglish Recall

- Tables se data rows aur columns mein dikhate hain.
- `<table>` → table, `<tr>` → row, `<th>` → heading, `<td>` → data.
- Forms se user ka data collect karte hain: email, password, checkbox, radio, select.
- Placeholder = input field ka hint text.
- Input types help users input correctly.
- Explore tags on **MDN docs** to learn as needed.

---

### ✅ Quick Summary

- Tables = display structured data.
- Forms = collect user input.
- Input types and placeholders improve form usability.
- HTML allows beginners to create functional tables and forms before styling.

---

## ⏭️ Next Lecture

➡️ Advanced HTML Attributes & Semantic Elements → Learn more useful tags and improve HTML structure.

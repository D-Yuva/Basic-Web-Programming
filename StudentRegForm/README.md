# 📝 Student Registration Form

This is a simple HTML, CSS, and JavaScript-based **Student Registration Form** that validates user inputs before submission. It ensures all required fields are filled with appropriate values and provides real-time feedback using inline error messages.

---

## 📌 Features

- Input validation for:
  - First name and Last name
  - Email format
  - Gender selection (radio buttons)
  - Course selection (checkboxes)
  - Country selection (dropdown)
  - Motivation/Comments field
- Error messages displayed inline
- Clean tabular layout
- Form submission success message (`alert("Registered")`)

---

## 🛠️ Technologies Used

### ✅ HTML5
- Semantic tags: `<form>`, `<input>`, `<select>`, `<textarea>`, etc.
- Table layout using `<table>`, `<tr>`, `<th>`, `<td>`
- Form controls: text, email, radio, checkbox, select, textarea
- `<button type="button">` to handle custom submission logic

### 🎨 CSS
- Inline `<style>` used for styling
- Custom `.error` class to show validation messages in red
- Table styling using `border-collapse`, padding, and border properties

### ⚙️ JavaScript
- Client-side form validation via the `ValidateForm()` function
- DOM manipulation using:
  - `document.getElementById()`
  - `document.querySelector()`
  - `document.querySelectorAll()`
- Regex pattern check for validating email address
- Dynamic error handling using inline `<div>` elements

---

## 📂 Project Structure

```plaintext
student-form/
│
├── index.html      # Main file with form, styling, and JavaScript
└── README.md       # This file (project documentation)


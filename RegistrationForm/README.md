# 📝 Registration Form with JavaScript Validation

This project is a simple HTML registration form that uses **JavaScript** for **client-side validation**. It collects user data such as name, sex, eye color, personal attributes, and a description of athletic ability.

## 💻 Tech Stack Used

- **HTML5** – For structuring the form
- **CSS3** – For basic styling of the table and error messages
- **JavaScript (Vanilla)** – For form validation logic

---

## 📋 Features

- Structured form layout using HTML `<table>`
- Various input types used:
  - Text input
  - Radio buttons
  - Dropdown `<select>`
  - Checkboxes
  - Textarea
- Inline error messages for:
  - Name
  - Sex
  - Eye color
  - Athletic ability
- JavaScript-based validation on button click

---

## 📦 Files Overview

### `index.html`

Contains the full structure of the form and embedded JavaScript for validation.

### HTML Elements Used:

- `<form>`: Wraps the input elements
- `<table>`: Used to organize the form layout
- `<input>`: Used for:
  - `type="text"` – Name field
  - `type="radio"` – Sex selection
  - `type="checkbox"` – Attributes
  - `type="button"` – Submit button
- `<select>`: For eye color selection
- `<textarea>`: For athletic ability description
- `<div>`: For displaying validation error messages
- `<label>`: For form accessibility and user guidance

---

## 🎨 CSS Styling

CSS is embedded within the `<style>` tag and includes:

- Styling for the table, borders, and padding
- `.error` class for displaying red-colored validation messages
- `.submit-row` for centering the submit button

---

## 🧠 JavaScript Logic

All validation is handled within the `validateForm()` function:

### Function: `validateForm()`

Performs the following:

1. **Resets** all previous error messages.
2. **Retrieves** values from form fields.
3. **Checks** for:
   - Empty name
   - Unchecked radio (sex)
   - Unselected dropdown (eye color)
   - Empty textarea (athletic ability)
4. **Displays** inline error messages where validation fails.
5. If all validations pass, shows an alert saying: `Form submitted!`

---

## 🛠️ Functions & DOM Methods Used

- `document.getElementById()` – For accessing inputs and error divs
- `document.querySelector()` – For selecting the checked radio button
- `innerText` – For setting error messages
- `trim()` – To remove whitespace
- `alert()` – To notify on successful form submission

---

## 🚀 How to Use

1. Open `index.html` in any modern browser.
2. Fill out the form.
3. Click on the **"Enter info"** button.
4. If any required fields are missing, error messages will appear.
5. If all fields are filled correctly, you'll see a success alert.

---

## 📌 Notes

- This form only performs **client-side validation**.
- For a complete production-ready system, **server-side validation** should also be implemented.
- The form does not submit anywhere (uses `type="button"` to avoid actual form submission).

---

## 📷 Screenshot

![Registration Form UI](screenshot-placeholder.png)

> (Add an actual screenshot of your form in place of this placeholder for visual reference)

---

## 📂 Future Enhancements

- Add server-side validation using PHP/Node/Flask
- Store submitted data
- Add password/email fields with validation
- Responsive design with Flexbox or Grid

---

## 📃 License

This project is open-source and free to use.


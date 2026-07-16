# Student Registration Form

A clean, responsive, and modern Student Details Form built using vanilla web technologies. The interface features a beautiful, soft, light sky-blue theme with custom client-side validation using modern JavaScript standards.

## 📁 Project Structure

The project files are organized cleanly across dedicated template and asset folders inside the root directory:

```text
├── index.html     # HTML5 Form layout structure
├── style.css      # Custom sky-blue styling and animations
└── script.js      # Form validation and interactivity
```

## ✨ Features

- **Sky-Blue Design Palette:** Soft background colors (`#e6f4f8`), bright focus borders (`#63b3ed`), and smooth button interactions provide a highly professional user experience.
- **Custom Form Validation:** Overrides native browser behavior using the HTML5 `novalidate` attribute to deliver consistent, unified error prompts.
- **Dynamic UX Feedback:** Error messages appear instantly on submission and fade away dynamically as the user modifies fields.
- **Success Summary Panel:** Displays a personalized confirmation dialogue detailing the registered student's name and selected course upon successful parsing.

## 🛠️ Tech Stack & Concepts Used

### 1. HTML5 & CSS3
- Semantic layout form handling with radio buttons, native date selectors, and dropdown dropdown listings.
- Advanced focus states, shadow cards (`box-shadow`), and responsive layout management using modern layout spacing.

### 2. JavaScript (ES6+)
This project cleanly splits event responsibilities utilizing two core types of functional expressions:
- **Anonymous Function (`function(event) {}`):** Attached to live `'input'` triggers. It listens dynamically across form blocks and drops error elements instantly as users type.
- **Arrow Function (`(e) => {}`):** Attached to the form's `'submit'` handling. It intercept default actions using `e.preventDefault()`, executes regular expression tests on emails, verifies missing inputs, and populates the success summary block.

## 🚀 How to Run Locally

1. Clone or download this repository to your desktop machine.
2. Ensure your directory names match the file tree listed above (`jay/template/` and `jay/asset/`).
3. Open the `template` folder.
4. Double-click the `index.html` file to launch the form inside any modern web browser (Chrome, Firefox, Safari, Edge).

## 📊 Form Validation Rules Applied

- **Full Name:** Cannot be submitted blank or trailing whitespace.
- **Email Address:** Checked against a standard validation expression matching structure queries (`user@domain.com`).
- **Date of Birth:** Must have a valid date picked.
- **Gender:** Requires one radio option selected.
- **Enrolled Course:** Requires selection of an available program option.

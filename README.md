<div align="center">

# 🖥️ INIT'26 — Registration Terminal

A retro developer-terminal registration interface built for **Team OSS**'s flagship recruitment drive, **INIT'26**. Designed with an IDE/code-editor aesthetic, monospace typography, and syntax-inspired form structures.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green)

</div>

---

## 🎮 Overview

INIT'26 Registration Terminal reimagines a standard sign-up form as a code editor — split-pane "workstation" layout, sidebar tabs, macOS-style window controls, and terminal status indicators. Every field reads like a variable declaration, giving applicants for Team OSS's recruitment drive a themed, developer-flavored registration experience.

## ✨ Features

- 🖥️ **Developer IDE Aesthetic** — styled with macOS-inspired window controls, simulated sidebar tabs, and terminal status indicators
- 🧩 **Syntax-Themed Form Fields** — input labels are modeled after variable declarations (e.g., `"Full_name": String`) enclosed in code braces `{ ... }`
- 🗂️ **Multi-Domain Selection** — supports recruitment applications across disciplines including:
  - Frontend
  - Backend
  - App Development
  - Artificial Intelligence & Machine Learning (AIML)
  - UI/UX & Graphic Design
  - Video Editing
- 📱 **Responsive Layout** — automatically shifts from a split-pane workstation view on desktop to a streamlined stacked layout on mobile screens
- ✅ **Accessible & Validated** — HTML5 constraint validation built into all primary applicant fields

## 🚀 Getting Started

### Prerequisites

Just a web browser. No installation, no build step, no server required.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/init26-registration-terminal.git

# Navigate into the project directory
cd init26-registration-terminal

# Open the page directly
open FORM.html        # macOS
start FORM.html         # Windows
xdg-open FORM.html       # Linux
```

Or serve it with any static file server:

```bash
npx serve .
```

Then visit the local address it prints (e.g. `http://localhost:3000`).

## 📁 Repository Structure

```
├── FORM.html        # Main registration page structure
├── FORM.css         # Terminal styling, themes & responsiveness
├── FORM.js          # Form validation & submission scripting
├── osslogo.png      # Team OSS official emblem
├── back.jpg         # Spider-web themed graphic asset
└── background.png   # Web pattern backdrop
```

## 🧠 How It Works

1. Applicants land on a split-pane "workstation" view — a sidebar mimicking editor tabs alongside the main registration form.
2. Each form field is labeled like a code variable declaration (e.g. `"Full_name": String`), reinforcing the IDE theme.
3. Applicants select their domain of interest (Frontend, Backend, App Dev, AIML, UI/UX & Design, or Video Editing) from the multi-domain selector.
4. Built-in HTML5 validation ensures required fields are filled correctly before submission.
5. `FORM.js` handles form submission behavior client-side.
6. On smaller screens, the split-pane layout collapses into a single stacked column for readability.

## 🛠️ Tech Stack

| Layer       | Technology                                                              |
|-------------|---------------------------------------------------------------------------|
| Structure   | HTML5 — semantic markup for sidebar navigation, forms, and footer links   |
| Styling     | CSS3 — Flexbox, subtle grid background patterns, box-shadow accents, and media queries |
| Typography  | [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) via Google Fonts |
| Scripting   | JavaScript (`FORM.js`) — client-side form handling and submission behavior |

## 🗺️ Possible Improvements

- [ ] Connect form submission to a backend or form service (e.g. Formspree, Google Sheets API)
- [ ] Add client-side validation feedback beyond native HTML5 messages
- [ ] Add a confirmation screen or email receipt after successful registration
- [ ] Add dark/light theme toggle
- [ ] Add animated terminal "typing" intro on page load

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/init26-registration-terminal/issues) or open a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
Built for Team OSS — INIT'26 🕸️
</div>

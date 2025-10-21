# muiti-page-final
# Stage 1 - Multi-Page Portfolio Project 🌐

This project builds on **Stage 0**, where I created a single Profile Card.  
In **Stage 1**, I expanded that into a small multi-page web application with:
- A **Home page** (Profile Card)
- An **About Me page**
- A **Contact Us page** with form validation

All pages are fully responsive, accessible, and connected via a simple navigation bar.

---



## 📄 Pages Overview

### 🏠 Home Page (`index.html`)
- Displays a profile card with name, role, bio, and social links.
- Navigation bar links to **About Me** and **Contact Us**.
- Responsive layout with a clean, modern design.

### 👤 About Me Page (`about.html`)
- Contains reflective sections:
  - **Bio** – Short introduction about me.
  - **Goals** – My aims for this program.
  - **Areas of Low Confidence** – Honest self-reflection areas.
  - **Note to Future Self** – Encouragement and motivation.
  - **Extra Thoughts** – Any additional reflections.
- Fully semantic structure (`<main>`, `<section>`, `<h2>`, `<p>`).

### 💌 Contact Us Page (`contact.html`)
- Includes a simple form with validation rules:
  - **Full Name**, **Email**, **Subject**, **Message** (all required).
  - Email must follow `name@example.com` format.
  - Message must be at least 10 characters.
- Displays success message on valid submission.
- Accessible labels and `aria-describedby` for errors.
- Navigation links appear neatly under the "Send Message" button.

---

## 🧠 Accessibility Features
- All inputs have `<label>` elements.
- Error messages linked with `aria-describedby`.
- Fully keyboard-navigable.
- Semantic HTML used throughout (`main`, `section`, `nav`, `footer`).

---

## 📱 Responsiveness
- Mobile-first layout using CSS Flexbox.
- Adjusts gracefully across mobile, tablet, and desktop.
- Uses `@media` queries for small screen optimization.

---

## 🧩 Technologies Used
- **HTML5** for structure  
- **CSS3** for styling and responsiveness  
- **JavaScript** for form validation and interactivity  

---

## ⚙️ Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/sossa0233/stage1-portfolio.git

# Frontend Mentor - Social Links Profile Solution  

This is a solution to the [Social Links Profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

---

## 📑 Table of contents
- [Overview](#-overview)  
  - [The challenge](#the-challenge)  
  - [Screenshot](#screenshot)  
  - [Links](#links)  
- [My process](#-my-process)  
  - [Built with](#built-with)  
  - [What I learned](#what-i-learned)  

---

## 🔎 Overview

### The challenge
Users should be able to:
- See hover and focus states for all interactive elements on the page  
- View the optimal layout depending on their device’s screen size  

### Screenshot
<img width="1904" height="967" alt="image" src="https://github.com/user-attachments/assets/bd15a4ac-e7ab-4920-bb4c-21af92d5bd7e" />


### Links
- Solution URL: [GitHub Repo](https://github.com/Sanjeev2007/social-links-profile)  
- Live Site URL: [Live Demo](https://sanjeev2007.github.io/social-links-profile/)  

---

## ⚙️ My process  

I approached this project with a **desktop-first workflow**.  

1. Built the layout for desktop screens first, using `vh`-based widths (`.box { width: 40vh; }` and `.element { width: 30vh; }`).  
2. Used `<br>` tags for spacing between elements.  
3. Added a `@media (max-width: 430px)` query to handle mobile view.  
4. Focused on hover states and a dark theme with green accent color.  

---

### 🛠 Built with
- Semantic HTML5 (basic structure)  
- CSS custom properties  
- Flexbox  
- Desktop-first workflow with `max-width` media query  
- Hover & focus states  

---

### 📚 What I learned
- How to apply a desktop-first workflow and then adjust for mobile.  
- Practiced using `vh` units for card widths (instead of `%` or `px`).  
- Learned how to use media queries like `@media (max-width: 430px)` to change layout for smaller screens.  

Code sample from my project:
```css
.element:hover,
.element:focus-visible {
  cursor: pointer;
  background-color: hsl(75, 94%, 57%);
  color: hsl(0, 0%, 8%);
  outline: none;
}

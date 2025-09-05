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
  - [Continued development](#continued-development)  
- [Author](#-author)  

---

## 🔎 Overview

### The challenge
Users should be able to:
- See hover and focus states for all interactive elements on the page  
- View the optimal layout depending on their device’s screen size  

### Screenshot
![Screenshot of my solution](./assets/images/screenshot.png)  
<img width="1905" height="966" alt="image" src="https://github.com/user-attachments/assets/e0d1a191-3e99-4867-84f1-1a812c00d27b" />

 

### Links
- Solution URL: [GitHub Repo](https://github.com/Sanjeev2007/social-links-profile)  
- Live Site URL: [Live Demo](https://Sanjeev2007.github.io/social-links-profile/)  
  

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

## LEVAN NATCHKEBIA

---

### Contact Details

---

- **Location:** Tbilisi, Georgia
- **Mob:** +995 568 61 67 87
- **Email:** levani.nachkebia@gmail.com
- **Telegram:** Levan Natchkebia
- **LinkedIn:** [Levan Natchkebia](https://www.linkedin.com/in/levan-natchkebia-65b861242/)
- **GitHub:** [LevanNatchkebia ](https://github.com/LevanNatchkebia)

---

**About Myself:**
I am Levan jr. Front-end developer.I am enthusiastic about kickstarting my career in web development.
With a solid foundation in HTML5, CSS3, JavaScript, I am eager to apply my skills to create visually
appealing and responsive websites. I have also started exploring React, React Router, and Redux for
building more interactive user interfaces. My familiarity with C++ and SQL provides a well-rounded
understanding of programming and data management. I am eager to join a supportive team where I can
learn and grow as a developer while contributing my passion and dedication to web projects.

---

## **Education:**

- **Tbilisi Medical Academy:**
  Specialization: Doctor Of Medicine (MD);

---

**Courses**

- **RSSchool** :
  JavaScript/Front-End Course EN 2023Q4

- **SkllWIll**:
  Front-End Development (React.JS)

- **Cisco**:
  Javascript Essential 1

-  **GITA (New Horizon)**:
  Blockchain and Business Fundamental

- **IT Step Academy**:
  Graphic Design (Illustrator)

---

**Languages:**

- Georgian: Native;
- English: C1;
- German: B1;

---

**Skills:**

- CSS
- HTML
- JavaScript
- Git, GitHub
- React.js
- Figma
- WordPRess
- C++ basics
- Markdown
- C# .Net Basics
- SQL 
- Communication Skills
- Provlem Solving 
- Team Working

---

**Code Example:**
**Vanilla.JS**
---

const inputField = document.querySelector('.search-field');
const placeholderTexts = [
    "სახელი , გვარი",
    "პოზიცია",
];

let currentTextIndex = 0;
let currentIndex = 0;

function typeAndBackspacePlaceholder() {
    const currentText = placeholderTexts[currentTextIndex];
    if (currentIndex < currentText.length) {
        const currentPlaceholder = inputField.getAttribute('placeholder');
        inputField.setAttribute('placeholder', currentPlaceholder + currentText.charAt(currentIndex));
        currentIndex++;
        setTimeout(typeAndBackspacePlaceholder, 120); 
    } else {
        erasePlaceholder(currentText);
    }
}

function erasePlaceholder(text) {
    if (text.length > 0) {
        const newText = text.substring(0, text.length - 1);
        inputField.setAttribute('placeholder', newText);
        setTimeout(() => erasePlaceholder(newText), 50); 
    } else {
        currentTextIndex = (currentTextIndex + 1) % placeholderTexts.length;
        currentIndex = 0;
        setTimeout(typeAndBackspacePlaceholder, 500); 
    }
}

typeAndBackspacePlaceholder();

---
**Experience:**
- Front-End Developer in RICO GROUP

  
**Projects:**

- [Responsive Markup Page](https://levannatchkebia.github.io/Type-Master/)
- [Online Car Shop](https://github.com/LevanNatchkebia/CPP-OnlineStore)
- [Roman Calculator](https://github.com/LevanNatchkebia/Roman-Calculator)
- [Portfolio](https://levannatchkebia.wordpress.com/)

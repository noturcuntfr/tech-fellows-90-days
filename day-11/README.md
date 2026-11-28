# Day 11 – Cascade, Specificity, Inheritance and Colors

**Program:** Tech Fellows – Full Stack Development Internship  
**Day:** 11  
**Topic:** CSS Cascade, Specificity, Inheritance and Colors  
**Status:** Completed

## 📌 About This Task

This task focuses on understanding important CSS concepts, including inheritance, specificity, source order, different color formats, transparency, and CSS variables.

The goal was to understand how CSS rules work, how browsers decide which styles to apply, and how to use colors effectively in web design.

## 🎯 Learning Objectives

- Understand how CSS inheritance works.
- Learn how CSS specificity determines which rule takes priority.
- Understand how source order affects CSS styling.
- Explore different CSS color formats.
- Create different shades using HSL.
- Understand the difference between `rgba()` and `opacity`.
- Learn how to create and use CSS variables.
- Identify and fix common CSS errors.

## 📂 Project Structure

```text
daily-practice/
└── day-11/
    ├── index.html
    ├── css/
    │   └── style.css
    └── README.md
```

## 📝 Tasks Completed

### Task 1 – Inheritance
- Created an HTML page with a heading, three paragraphs, and an unordered list.
- Applied text color and font family to the body.
- Observed which CSS properties are inherited.
- Tested border inheritance.
- Used `color: inherit` to make a link inherit its paragraph's text color.

### Task 2 – Specificity Battle
- Tested element, class, and ID selectors.
- Compared their priority in CSS.
- Added a combined selector (`p.note`).
- Tested the effect of `!important`.
- Documented the expected and actual results using CSS comments.

### Task 3 – Source Order
- Created a 150px × 150px box.
- Applied two different background colors using the same class selector.
- Changed the order of CSS rules to understand which declaration wins.

### Task 4 – Color Formats
Created six boxes using different CSS color formats:
- Named color
- HEX
- 3-digit HEX
- RGB
- RGBA
- HSL

### Task 5 – HSL Shades
- Created five blue-colored boxes using HSL.
- Experimented with different lightness values: 20%, 35%, 50%, 65%, and 80%.
- Displayed the lightness percentage inside each box.

### Task 6 – Transparency
- Placed text over a colored background.
- Used `rgba()` to create a semi-transparent background.
- Compared it with the `opacity` property.
- Observed how opacity affects both the background and its child content.

### Task 7 – CSS Variables
- Defined four CSS variables inside `:root`.
- Used variables for the body, heading, and button.
- Added a hover effect to the button using the accent color.
- Changed the primary color to observe how CSS variables update the design.

### Task 8 – Debug Challenge
- Identified and corrected six CSS mistakes.
- Fixed incorrect selectors, color values, property names, RGB values, and text alignment.
- Added CSS comments explaining the mistakes and their corrections.

## 🛠️ Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- Git and GitHub

## 📚 Key Learnings

Through this task, I learned how CSS inheritance, specificity, and source order work together to determine the final appearance of a webpage.

I also gained practical experience with different color formats, transparency, HSL lightness, and reusable CSS variables.

The debugging challenge helped me improve my ability to identify and fix common CSS errors.

## 📤 Submission Details

- **Project Folder:** `daily-practice/day-11/`
- **Files:** `index.html`, `css/style.css`, and `README.md`

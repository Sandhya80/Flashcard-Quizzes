# Flashcard Quizzes

A modern, interactive flashcard app for learning JavaScript, HTML5, and CSS3. Features include multiple-choice quizzes, category filtering, a countdown timer, dark/light mode, and full mobile responsiveness with accessible color palettes.

---

## Table of Contents

- [Demo](#demo)
- [Deployed App](#deployed-app)
- [File Structure](#file-structure)
- [Accessibility and SEO](#accessibility-and-seo)
- [Performance and Best Practices](#performance-and-best-practices)
- [Key Features](#key-features)
- [JavaScript Methodologies Used](#javascript-methodologies-used)
- [Color Palettes](#color-palettes)
- [Getting Started](#getting-started)
- [User Instructions](#user-instructions)
- [Customization](#customization)
- [License](#license)
- [Contact](#contact)

---

## Demo

![Flashcard Quizzes Demo](imgs/LiveDemo.gif)

---

## Deployed App

You can try the Flashcard Quizzes app live here:  
[https://sandhya80.github.io/Flashcard-Quizzes/](https://sandhya80.github.io/Flashcard-Quizzes/)

---

## File Structure

```plaintext
flashcard-quizzes/
├── [index.html](http://_vscodecontentref_/0)         # Main HTML file
├── [style.css](http://_vscodecontentref_/1)          # App styling
├── [script.js](http://_vscodecontentref_/2)          # App logic and interactivity
├── [favicon.ico](http://_vscodecontentref_/3)        # App icon 
└── [README.md](http://_vscodecontentref_/4)
```

---

## Accessibility and SEO

Flashcard Quizzes is built with accessibility and SEO best practices in mind:

- **Semantic HTML:**  
  Proper use of HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.) to structure the content meaningfully.

- **ARIA Roles and Attributes:**  
  Appropriate ARIA roles and attributes are used to enhance accessibility for assistive technologies (e.g., `aria-live` for announcements, `role="button"` for clickable elements).

- **Keyboard Navigation:**  
  The app is fully navigable using a keyboard, with logical tab order and focus management.

- **Color Contrast:**  
  Text and interactive elements have sufficient color contrast ratios to ensure readability for users with visual impairments.

- **Alt Text for Images:**  
  Descriptive alt text is provided for all meaningful images and icons.

- **Responsive Design:**  
  The layout adapts gracefully to different screen sizes and orientations, ensuring usability on mobile devices.

- **SEO-Friendly Structure:**  
  The HTML is structured to be crawlable and indexable by search engines, with proper use of headings, links, and metadata.

**Accessibility and SEO Test Results for Mobile and Desktop:**  
![Accessibility and SEO for Mobile](imgs/accessibilitySeoScore_mb.PNG)  
![Accessibility and SEO for Desktop](imgs/accessibilitySeoScore_desk.PNG)

---

## Performance and Best Practices

To ensure fast load times and a smooth user experience, Flashcard Quizzes follows these performance and best practices:

- **Optimized Assets:**  
  Images and other assets are optimized for the web to reduce file size and improve loading speed.

- **Minified CSS and JavaScript:**  
  CSS and JavaScript files are minified to decrease their size and reduce the number of HTTP requests.

- **Browser Caching:**  
  Leveraging browser caching for static assets to improve repeat visit loading times.

- **Responsive Images:**  
  Using responsive image techniques (e.g., `srcset`) to serve appropriately sized images for different devices.

- **Accessibility Best Practices:**  
  Following WCAG 2.1 guidelines to ensure the app is accessible to users with disabilities.

- **SEO Best Practices:**  
  Implementing on-page SEO best practices, including meta tags, title tags, and structured data markup.

**Performance and Best Practices Test Results:**  
![Performance Example](imgs/performBestPracScore.PNG)

---

## Key Features

- Multiple-choice flashcards for JavaScript, HTML5, and CSS3
- Add, edit, and delete flashcards
- Category filtering and card shuffling
- Score tracking with reset option
- **Countdown timer with set/reset and time-up alert**
- Responsive and modern UI (container is always 80% of viewport width)
- Data persistence with localStorage
- **Dark Mode / Light Mode toggle for comfortable viewing**
- **Modern, accessible color palettes for both light and dark themes**
- Accessible and mobile-friendly design

---

## JavaScript Methodologies Used

Flashcard Quizzes leverages modern JavaScript methodologies and best practices to ensure a robust, maintainable, and interactive user experience:

- **Modular Code Structure:**  
  Functions are organized by responsibility (rendering, event handling, data management) for clarity and maintainability.

- **DOM Manipulation:**  
  The app dynamically updates the DOM to display questions, choices, scores, and feedback using methods like `document.getElementById`, `createElement`, and event listeners.

- **Event-Driven Programming:**  
  User interactions (button clicks, form submissions, category changes) are handled using event listeners to provide real-time feedback and interactivity.

- **State Management:**  
  The app maintains state variables (such as current question, score, filtered cards, selected category, and timer) to track user progress and update the UI accordingly.

- **Local Storage:**  
  User data (flashcards and score) is persisted using `localStorage`, allowing users to retain their progress and custom cards across sessions.

- **Array Methods:**  
  Modern array methods like `.filter()`, `.map()`, `.forEach()`, and `.sort()` are used for efficient data manipulation (e.g., filtering by category, shuffling cards, generating choices).

- **Form Handling and Validation:**  
  Input forms for adding and editing flashcards include validation to ensure data integrity before updating the flashcard set.

- **Responsive Feedback:**  
  The UI provides immediate feedback for correct/incorrect answers, quiz completion, and score updates.

- **Progressive Enhancement:**  
  The app is designed to work seamlessly on all modern browsers and devices, with graceful fallbacks for unsupported features.

---

## Color Palettes

- **Light Mode:**  
  - Background: Soft white (`#fff`), accent backgrounds (`#b4ece0`, `#f0f4ff`)
  - Text: Dark gray/black (`#232323`)
  - Buttons/inputs: Subtle grays and accent colors

- **Dark Mode:**  
  - Background: Deep gray (`#232323`), accent backgrounds (`#2d2d3a`)
  - Text: Light gray/white (`#f1f1f1`)
  - Buttons/inputs: Muted darks with clear contrast

All color choices are designed for readability and comfort, day or night.

---

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/flashcard-quizzes.git
   cd flashcard-quizzes
   ```

2. **Open `index.html` in your browser.**

_No build steps or dependencies required._

---

## User Instructions

- **Answer Questions:** Click on the correct answer from the multiple choices.
- **Flip Card:** View the answer using the "Flip" button.
- **Navigate:** Use "Next" and "Previous" to move between cards.
- **Add/Edit/Delete:** Use the provided forms and buttons to manage flashcards.
- **Filter:** Select a category to focus on specific topics.
- **Shuffle:** Randomise the order of flashcards.
- **Score:** Track your score and reset it anytime.
- **Timer:** Set a countdown timer for your quiz session. When time is up, you'll get an alert.
- **Theme:** Use the toggle button to switch between Dark Mode and Light Mode.

---

## Customization

- **Add More Flashcards:** Edit `script.js` and add more questions/answers to the flashcards array.
- **Change Styles:** Modify `style.css` for custom colours and layout.
- **Expand Categories:** Add new categories and update the category dropdown in `index.html`.
- **Adjust Timer:** You can change the timer's default behavior or alert in `script.js`.
- **Tweak Color Palettes:** Update the CSS variables or color values in `style.css` for your own look.

---

## License

This project is licensed under the MIT License.

---

## Contact

For questions, suggestions, or feedback, please contact:  
**Sandhya H**  
Email: [sandhyaharsh@gmail.com](mailto:sandhyaharsh@gmail.com)  
GitHub: [sandhya80](https://github.com/sandhya80)

---

Happy learning and enjoy practicing with your customized Flashcard Quizzes app!

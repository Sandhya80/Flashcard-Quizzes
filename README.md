# Flashcard Quizzes

A simple, interactive flashcard quiz app for learning JavaScript, HTML5, and CSS3 concepts. Users can test their knowledge, add/edit/delete flashcards, filter by category, track their score, set a countdown timer, and switch between Dark Mode and Light Mode for comfortable studying at any time. The app is fully responsive, uses modern color palettes for both light and dark modes, and works great on all devices.

---

## Table of Contents

- [Key Features](#key-features)
- [Demo](#demo)
- [Deployed App](#deployed-app)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [User Instructions](#user-instructions)
- [Customization](#customization)
- [JavaScript Methodologies Used](#javascript-methodologies-used)
- [Color Palettes](#color-palettes)
- [Toggle Feature (Dark Mode / Light Mode)](#toggle-feature-dark-mode--light-mode)
- [Contributing](#contributing)
- [License](#license)

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

## Demo

![Flashcard Quizzes Demo](./demo.gif)

---

## Deployed App

You can try the Flashcard Quizzes app live here:  
[https://sandhya80.github.io/Flashcard-Quizzes/](https://sandhya80.github.io/Flashcard-Quizzes/)

---

## File Structure

```plaintext
flashcard-quizzes/
├── index.html         # Main HTML file
├── style.css          # App styling
├── script.js          # App logic and interactivity
├── favicon.ico        # App icon 
└── README.md
```

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

## Toggle Feature (Dark Mode / Light Mode)

Flashcard Quizzes includes a convenient Dark Mode/Light Mode toggle. Users can switch between dark and light themes at any time using the toggle button at the top of the app. The app remembers your preference for future visits, providing a comfortable experience whether you're studying during the day or at night.

---

### Demo of Toggle Feature

You can see the Dark Mode/Light Mode toggle in action below:

![Dark Mode Toggle Demo](togglebtn.gif)

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

---

## License

MIT License

---

Customise it your way and enjoy learning with **Flashcard Quizzes**!

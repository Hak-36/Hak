# SportRecall: The Ultimate Memory Retention Game ⚽🏏

A fast-paced, high-stakes sports trivia game built entirely with native web technologies. The game tests both your reading comprehension and long-term memory retention across football and cricket trivia.

## 🎮 The Gameplay Loop

1. **Read & Progress:** You are presented with a detailed paragraph about a football or cricket concept.
2. **The Catch:** As you advance to the next paragraph, the questions begin targeting *previous* paragraphs you've already read.
3. **No Safety Net:** You cannot navigate backward to re-read. 
4. **Sudden Death:** Get a single question wrong, and it's **Game Over**. Survive through 10 consecutive rounds to achieve a Perfect Recall victory.

---

## 🚀 Features

- **Progressive Memory Tax:** Questions unanchor from the current screen, forcing players to rely on their actual retention of earlier text blocks.
- **Sudden Death Mechanics:** Zero tolerance for mistakes—one wrong answer instantly ends the run.
- **Dynamic Content Engine:** Curated 5-line text blocks focusing on specific football tactics, iconic cricket positions, stadium rules, and legendary trivia.
- **Responsive Sports UI:** A clean, modern aesthetic utilizing custom CSS styling optimized for both desktop and mobile sports fans.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structure for paragraphs, interactive multiple-choice options, and score tracking.
- **CSS3:** Modern layout system (Flexbox/Grid), sports-themed color palettes, custom typography, and dynamic "Game Over / Victory" modal overlays.
- **Vanilla JavaScript:** State management handles the 10-round logic, randomized question-to-paragraph mapping, score tracking, and click event handlers.

---

## 📂 Project Structure

```text
├── index.html          # Main application structure & layout
├── css/
│   └── style.css       # Layout, typography, and game state styling
└── js/
    ├── app.js          # Core game loop, event listeners, and state management
    └── data.js         # The database containing paragraphs, questions, and answers

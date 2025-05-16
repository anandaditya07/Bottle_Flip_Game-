# 🧪 Bottle Flip Game

A fun and interactive browser game where you try to flip a juice bottle by holding and releasing with perfect timing. Get the strength just right to land a successful flip — too weak or too strong and the bottle breaks!

## 🚀 Features

- Animated bottle flip based on user click strength.
- Dynamic strength bar with visual color feedback.
- Score and high score tracking.
- Restart game with a "New Game" button.
- Fully responsive layout for desktop and mobile.

---

## 📁 Files Used

### `index.html`
- Main structure of the webpage.
- Links to `style.css` and `script.js`.
- Contains:
  - Game title and container.
  - Bottle image (`juice.png`) and broken state image (`broken-bottle.png`).
  - Strength bar and real-time strength percentage.
  - Score display and "New Game" button.

### `style.css`
- Handles all UI styling.
- Designs:
  - Game layout and alignment.
  - Strength bar with color transitions (yellow, green, red).
  - Bottle and broken bottle styles.
  - Responsive styles for smaller screens.
  - Custom progress bar visuals.

### `script.js`
- Adds interactivity and logic.
- Key functionality:
  - Strength bar animation based on mouse press duration.
  - Bottle spinning effect tied to strength.
  - Flip success or failure logic.
  - Score updating and difficulty increase with each success.
  - Dynamic color and text update of the strength bar.

### `juice.png`
- Image of the bottle used for flipping.
- Applied as the background of the `.bottle` div via CSS.

### `broken-bottle.png`
- Image shown when the bottle flip fails.
- Initially hidden; displayed on incorrect strength release.

---

## 📸 Preview

The game UI includes:
- A centered game panel.
- A bottle in the center.
- A horizontal progress bar representing strength.
- Score displays.
- Restart button.

---

## 🛠 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/bottle-flip-game.git

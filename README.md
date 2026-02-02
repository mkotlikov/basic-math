# 🧮 Basic Math: Fun & Scientific Learning

A premium, kid-friendly single-page application (SPA) designed to help children master basic arithmetic through **Scientific Spaced Repetition**.

## 🚀 Key Features

-   🌐 **All-in-One Operations**: Practice Addition, Subtraction, Multiplication (up to 12x12), and Division.
-   🧠 **Scientific Spaced Repetition**: Uses a Pimsleur-inspired "Memory Queue." Incorrect answers are strategically re-scheduled to reappear after 2 other questions, optimizing the transition from short-term to long-term memory.
-   🎮 **Interactive UI**: Vibrant, glassmorphic design featuring instant visual feedback (Green/Red) and delightful animations.
-   ⚡ **Speed Training**: Real-time "Answers Per Minute" (APM) tracking to encourage fluency and quick recall.
-   🏆 **High Scores**: Persistently tracks your "Top Speed" using browser storage to keep kids motivated.
-   🎛️ **Customizable Practice**: Dynamic toggle switches allow users to enable or disable specific operation types (+, −, ×, ÷) on the fly.

## 🛠️ Technical Stack

-   **Frontend**: Pure HTML5, CSS3 (Modern Flexbox/Grid), and Vanilla JavaScript.
-   **Architecture**: Zero dependencies. Fully self-contained in a single file for maximum portability and offline use.
-   **Persistence**: Uses `localStorage` to save user preferences (operation modes) and performance metrics (Top Speed).
-   **Responsive**: Mobile-first design that looks stunning on tablets and desktops.

## 🧠 The Spaced Repetition Logic

Unlike simple random question generators, **Basic Math** tracks every mistake. When a child misses a question:
1.  The correct answer is immediately highlighted.
2.  The question is added to a **Hidden Memory Queue**.
3.  The app waits for **exactly 2 questions** to pass before showing the missed problem again.
4.  If the child gets it right on the second try, it's moved back into the random pool. If missed again, the cycle repeats.

## 📖 How to Use

1.  Clone this repository.
2.  Open `index.html` in any modern web browser.
3.  Choose your operations using the top toggle buttons.
4.  Start answering!

---
*Built with ❤️ for better learning.*

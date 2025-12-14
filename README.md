# Number Guesser

Simple guessing game: predict a random number (1–10) within limited attempts. Demonstrates basic game loop logic & user feedback.

## 🚀 Features

- Random number generation each round
- Attempts countdown
- High / Low hints
- Win / lose dialogs via SweetAlert2

## 📂 Project Structure

```text
number-guesser/
├── index.html
├── css/
│   └── tailwind.css (generated)
├── js/
│   └── app.js
└── README.md
```

## 🛠️ Tech Stack

- HTML / Tailwind (pre-built CSS)
- Vanilla JavaScript
- SweetAlert2

## ⚙️ Setup

Open `index.html` directly. (Tailwind CSS already present.)

## 🧩 Usage

1. Enter a number (1–10)
2. Click Guess
3. Read feedback (High / Low / Win)
4. Continue until attempts reset or you win

## 🧱 Architecture

- Single script controlling state: `numberToGuess`, `attempts`
- Function `genRandomNumber()` for new round

## 🗄️ Data / Storage

- No persistence (session-only variables)

## 🔧 Scripts

None.

## 🧪 Testing

Manual: boundary values 1 & 10, repeated guesses.

## 📦 Deployment

Static.

## 📝 Notes

- Input not validated for range (negative / >10 possible). Could add guard.
- Could track statistics (win rate) in localStorage.

## 📄 License

MIT

## Learning Outcomes

- Randomization & state reset
- Conditional feedback logic
- External dialog library integration

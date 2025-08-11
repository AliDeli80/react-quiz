# 🎯 React Quiz App

A simple quiz application built with **React**, using **useReducer** for state management and a local JSON file for quiz data.

---

## 🚀 Features

- 🧠 State management using **React useReducer**
- 📂 Loads quiz questions from a local JSON file
- 📊 Shows score at the end of the quiz
- 🔄 Restart quiz option

---

## 🛠 Tech Stack

- **React** (Hooks + useReducer)
- **JavaScript (ES6+)**
- **CSS** for styling
- Local **JSON** file for quiz data

---

## 📦 Installation & Setup

Clone the repository and run it locally:

```bash
git clone https://github.com/AliDeli80/react-quiz.git
cd react-quiz
npm install
npm start
```
Then open http://localhost:3000 in your browser.

---

## 📖 How It Works
1- The app loads quiz questions from a local JSON file in the public folder.

2- State transitions (start quiz, answer question, next question, show results) are handled with useReducer.

3- Users select answers and receive points for correct answers.

4- At the end, the score is displayed with a restart option.

---

## 📂 Project Structure
```plaintext
react-quiz/
├── public/
│   └── questions.json     # Local quiz data
├── src/
│   ├── components/        # UI Components
│   ├── reducer.js         # useReducer logic
│   ├── App.js             # Main App component
│   ├── index.css          # Styles
│   └── index.js           # Entry point
└── package.json
```

---

## 📸 Screenshots
**1- Start Screen** – Where the quiz begins

<img width="1920" height="870" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/3db08ebb-5a99-43b3-9461-9dbb3e887452" />

**2- Question Screen** – Displaying the current question and options

<img width="1920" height="866" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/3544d3d7-5759-431d-b1fb-7535ec5acf83" />

**3- Answer Selection Screen** – User selecting an option

<img width="1920" height="864" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/e7a88268-4399-4ffd-b3de-8617b63f9871" />

**4- Result Screen** – Final score and restart option

<img width="1920" height="869" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/203fd074-1add-4d0d-990d-007e513d8d8a" />

---

## 🌟 Possible Improvements
- Make the app responsive for mobile devices

- Randomize question order

- Save scores to localStorage

- Add animations for better UX

- Fetch questions from an external API

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author
Ali Delgoshaei


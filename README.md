# Quiz_Master
# 🎓 Quiz Master

**Quiz Master** is a command-line Python application designed to create and play interactive quizzes. It leverages **Object-Oriented Programming (OOP)** principles to ensure a clean, modular, and extensible codebase.

---

## 🧠 Features

- Create custom quizzes with multiple questions
- Support for multiple-choice or true/false questions
- Score tracking system
- Option to review results at the end
- Easy to extend with new question types or formats

---

## 🚀 Technologies Used

- **Python 3**
- Object-Oriented Programming (OOP)

---

## 📂 Project Structure

quiz_master/
│
├── quiz.py # Main logic for quiz flow
├── question.py # Question class definition
├── question_bank.py # Holds list of quiz questions
├── main.py # Entry point of the application
└── README.md

yaml
Copy
Edit

---

## 👨‍💻 How It Works

- The `Question` class stores the question text and correct answer.
- The `Quiz` class manages the quiz logic — fetching questions, checking answers, and tracking scores.
- Users answer one question at a time and get immediate feedback.
- Final score and summary are shown at the end.

---

## 📦 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/quiz-master.git
   cd quiz-master

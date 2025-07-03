# 🧠 Big Five Personality Quiz  
A terminal-based psychological quiz application created for an Object-Oriented Programming course.

---

## 📘 Overview

This program administers the **Big Five Personality Test**, a widely used psychological model for understanding five key dimensions of personality:

- 🟣 **Openness to Experience**  
- 🔵 **Conscientiousness**  
- 🟢 **Extraversion**  
- 🟡 **Agreeableness**  
- 🔴 **Neuroticism**

After taking the 50-question quiz, users receive visual feedback through **bar graphs and a pie chart**, as well as a saved profile summarizing their results.

---

## 🔄 Process

This program was originally scoped to demonstrate object-oriented design by creating structured user personas and quiz logic. However, our team expanded its functionality to include:

- **Input validation**
- **Visual result generation**
- **Persistent file storage**

The project reflects foundational concepts in Python programming, data handling, and user-centric design — all within a terminal-based environment.

---

## 🚀 How to Run

> 📌 Make sure Python 3 is installed, along with `matplotlib`.

### 🖥️ Steps:
1. **Clone or download** this repository.
2. **Navigate to the directory** in your terminal.
3. **Run the script** with:

python BigFiveQuiz.py

## 📝 How It Works

The program prompts the user to input:

- 👤 **Name** (`str`)  
- 🎂 **Age** (`int`)  
- ⚧️ **Gender** (`str`)  

---

🧠 Users then answer **50 questions**, with **10 questions per personality trait**, using a scale from **1 (Strongly Disagree)** to **5 (Strongly Agree)**.

🚫 If the input is not between 1–5, the user is asked to re-enter their response.

---

After completing the quiz:

- 📊 **Bar graphs** show response distributions for each trait  
- 🥧 **Pie chart** visualizes overall trait percentages  
- 🗂️ **Results are saved** to `bigfive_output.txt`

---

## ✨ Features

- ✅ Terminal-based interactive quiz  
- ✅ Input validation with custom error messages  
- ✅ Bar and pie chart visualizations using `matplotlib`  
- ✅ Object-Oriented design patterns and reusable methods  
- ✅ Auto-save of user results to a local file

---

## 🛠️ Technologies Used

- 🐍 Python 3  
- 🗃️ `json` for storing question data  
- 📊 `matplotlib` for data visualization  
- 🧱 Object-Oriented Programming principles (classes, methods, magic methods)  

---

## ⚠️ Disclaimer

This project was created for **educational purposes** and is **not** a clinically validated personality assessment tool.

---

## Attributions Table:

| **Function/ Method**    | **Author**     | **Techniques Used**          |
| ----------------------- |:--------------:| ----------------------------:|
| DisplayGraph()          | Afraah Goshu   | Tuple Unpacking              |
| DisplayGraph()          | Afraah Goshu   | Optional Parameters          |
| saveUserProfile()       | Garrett        | With Statement               |
| UserProfile str()       | Garrett        | F string                    |
| DisplayPie()            | Eveana         | Data vis with pyplot         |
| BigFive str()           | Eveana         | Magic method                 |
| calculate_score()       | CJ             | Use of a key function        |
| main()                  | CJ             | List comprehension           |
| BigFive init()          | Arielle        | Use of json.load             |
| startQuiz()             | Arielle        | Conditional expression       |

# 🎮 Streamlit Number Guessing Game
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🧩 Overview
The **Number Guessing Game** is a simple and interactive web app built using **Streamlit**.  
It challenges users to guess a randomly generated number between **1 and 100**, giving feedback after each attempt — “Too High”, “Too Low”, or “Correct!”.  
When the correct number is guessed, the app displays the total attempts and allows users to play again instantly. 🎯

## 🚀 Features
- 🎲 Random number generated between **1 and 100**  
- 🔢 User inputs guesses via number input box  
- 💬 Feedback after each attempt  
- 🔁 “Play Again” button to restart the game  
- 🧠 Maintains game state using `st.session_state`  
- 🌐 Runs in your browser using Streamlit  

## 🛠️ Tech Stack
| Component | Description |
|------------|--------------|
| **Language** | Python |
| **Framework** | Streamlit |
| **Library Used** | `random`, `streamlit` |
| **Interface** | Web-based (interactive UI) |

## 📂 Project Structure
StreamlitNumberGuess/
│
├── app.py # Main Streamlit application file
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## ⚙️ Installation & Setup
1️⃣ Clone this repository
git clone https://github.com/yourusername/streamlit-number-guessing-game.git
cd streamlit-number-guessing-game

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   

3️⃣ Install dependencies
pip install streamlit

4️⃣ Run the app
streamlit run app.py

After running the above command, your browser will open automatically at:
arduino
http://localhost:8501

🕹️ How to Play
The game randomly chooses a number between 1 and 100.
Enter your guess in the input box.
The app will tell you if your guess is Too High, Too Low, or Correct.
Once you guess correctly, you’ll see your total number of attempts.
Click Play Again to restart the game anytime!

🧠 Key Python Concepts
1)st.session_state for game memory
2)random.randint() for number generation
3)Conditional logic for comparison
4)Streamlit UI elements (st.number_input, st.button, st.write)

📸 Example UI
🎮 Streamlit Number Guessing Game
--------------------------------
Welcome to the Guessing Game! Guess a number between 1 and 100.
[Enter your guess: 45]
[Submit Guess]
Too low! Try again.
Attempts: 2

👩‍💻 Author
S. Sanjana
🎓 B.Tech Information Technology
💬 “Simple ideas make fun apps!”

🏷️ License
This project is licensed under the MIT License – free for educational and personal use.

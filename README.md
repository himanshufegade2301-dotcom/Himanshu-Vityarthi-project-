# Himanshu-Vityarthi-project-
# 🎯 Quiz Game in Python

A simple **Command-Line Quiz Game** built using Python.
The game tests the player's basic knowledge of computer-related concepts such as **CPU, GPU, RAM, ROM, and input devices**.

## 📌 Features

* 👤 Takes the player's name
* ▶️ Asks the player whether they want to play
* ❓ Contains 5 computer-related questions
* ✅ Checks answers automatically
* 📊 Calculates the player's score
* 📈 Displays the final percentage
* 💻 Simple and beginner-friendly Python project

## 🛠️ Technologies Used

* **Python 3**
* Python `input()` and `print()`
* Conditional statements (`if-else`)
* String methods (`lower()`)
* Variables
* Basic arithmetic

## 📂 Project Structure

```text
QuizGame/
│
├── QuizGame.py
└── README.md
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/QuizGame.git
```

### 2. Open the Project Folder

```bash
cd QuizGame
```

### 3. Run the Python Program

```bash
python QuizGame.py
```

## 🎮 How to Play

1. Run the program.
2. Enter `yes` when asked if you want to play.
3. Enter your name.
4. Answer each question.
5. The program will tell you whether your answer is correct or wrong.
6. At the end, your total score and percentage will be displayed.

## ❓ Questions Included

The game currently asks questions about:

1. **CPU** – Central Processing Unit
2. **GPU** – Graphical Processing Unit
3. **RAM** – Random Access Memory
4. **ROM** – Read Only Memory
5. **Mouse** – Input device or output device

## 📊 Scoring

Each correct answer gives the player **1 point**.

There are **5 questions**, so:

```text
Maximum Score = 5
```

The percentage is calculated using:

```text
Percentage = (Score / 5) × 100
```

## 💡 Example

```text
Welcome To My Quiz Game
Interesting Game to Play

Do you want to play the game?
yes

Enter Your Name: Himanshu

Let's Start the Game :) Himanshu

What is CPU stands for?
central processing unit

Correct

What is GPU stands for?
graphical processing unit

Correct

...

You got the 5 correct answers
You got the 100.0 correct answers
```

## 🎓 Learning Outcomes

This project helps beginners understand:

* Python input and output
* `if-else` statements
* String comparison
* Variables and data types
* Score calculation
* Basic command-line application development

## 🔮 Future Improvements

Possible improvements for the project:

* Add more questions
* Add multiple-choice options
* Randomize questions
* Add difficulty levels
* Add a timer
* Store high scores
* Add a graphical user interface (GUI)
* Use a question database

* code :
   print(" Welcome To My Quiz Game \n Interesting Game to Play")
Player = input(" Do you want to play the game? \n" )
if Player.lower() != 'yes':
    print("Good Bye")
    quit()  

name_player = input("Enter Your Name: ")

print("Let's Start the Game :) ",name_player)

score = 0

answer = input(' What is CPU stands for? \n ')
if answer.lower() == 'central processing unit':
    print("Correct")
    score += 1
else:
    print('Wrong')
 
answer = input(' What is GPU stands for? \n ')
if answer.lower() == 'graphical processing unit':
    print("Correct")
    score += 1
else:
    print('Wrong')

answer = input(' What is RAM stands for? \n ')
if answer.lower() == 'random access memory':
    print("Correct")
    score += 1
else:
    print('Wrong')

answer = input(' What is ROM stands for? \n ')
if answer.lower() == 'read only memory':
    print("Correct")
    score += 1
else:
    print('Wrong')

answer = input(' Mouse is an input device or output device? \n ')
if answer.lower() == 'input device':
    print("Correct")
    score += 1
else:
    print('Wrong')
    
print("You got the " + str(score)+ " correct answers")
print("You got the " + str((score/5) *100)+ " correct answers")

## 👨‍💻 Author

**Himanshu Fegade**

If you found this project useful, consider ⭐ starring the repository!

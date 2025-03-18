# XOXO-game
# Tic-Tac-Toe with AI (Minimax Algorithm)

## 🎮 About the Project
This is a **Tic-Tac-Toe game** with an AI opponent that plays optimally using the **Minimax Algorithm**. The player competes against the AI in a command-line interface (CLI).

## 🚀 Features
- 🏆 **Player vs. AI Mode**
- 🤖 **AI uses the Minimax algorithm for optimal moves**
- 🖥️ **Runs in the console (CLI-based)**
- 🔄 **Automatic game loop until a win or draw**

## 🛠 Technologies Used
- **Python** (Standard Library)

## 📜 How to Play
1. **Run the script** using Python.
2. **Enter a number (1-9)** to place your move.
3. The AI (`O`) will make an optimal move.
4. The game continues until a **win** or **draw**.

## 📥 Installation
### **1. Clone the repository**
```sh
git clone https://github.com/your-username/tic-tac-toe-ai.git
cd tic-tac-toe-ai
```
### **2. Run the game**
```sh
python tic_tac_toe.py
```

## 📝 Game Rules
- The board consists of 9 positions (1-9).
- Players take turns placing `X` and `O`.
- The first player to align **3 marks in a row, column, or diagonal wins**.
- If the board is full and no one wins, it's a **draw**.

## 🔍 Minimax Algorithm Explained
- **AI evaluates all possible moves** and their future outcomes.
- Scores:
  - **+1** → AI (`O`) wins
  - **-1** → Player (`X`) wins
  - **0** → Draw
- AI selects the **best possible move** using the **Minimax algorithm**.

## 📌 Example Gameplay
```
You are 'X' and AI is 'O'.

 1 | 2 | 3 
---|---|---
 4 | 5 | 6 
---|---|---
 7 | 8 | 9 

Enter position (1-9): 5
```

## 🎯 Future Improvements
✅ Add difficulty levels (Easy, Medium, Hard)
✅ Create a GUI version using Tkinter or Pygame
✅ Implement a 2-player mode

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! Feel free to fork the repo and submit improvements.

---
🚀 **Enjoy playing Tic-Tac-Toe with AI!** 🤖

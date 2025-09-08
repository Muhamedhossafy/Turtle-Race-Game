# Turtle Race Game - Python Project

## 🎯 Project Overview

**Turtle Race Game** is an interactive Python game built with the Turtle graphics library. Players can place bets on which colored turtle will win a randomized race across the screen. This project demonstrates core programming concepts while providing an entertaining gaming experience.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Turtle](https://img.shields.io/badge/Turtle-Graphics-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎮 Game Preview

### 🏁 Race Start
![Race Start](https://via.placeholder.com/600x400/000000/FFFFFF/?text=Turtle+Race+Start)
*Three colored turtles at the starting line ready to race*

### 🏆 Winner Announcement
![Winner Screen](https://via.placeholder.com/600x400/006400/FFFFFF/?text=You+Win!)
*Green victory screen when player guesses correctly*

### 😞 Loss Screen
![Loss Screen](https://via.placeholder.com/600x400/C71585/FFFFFF/?text=You+Lose!)
*Pink loss screen when player's turtle doesn't win*

## 📁 Project Structure

```
turtle-race-game/
├── turtle_race.py      # Main game file
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
```

## 🛠️ Technologies Used

- **Python 3** - Core programming language
- **Turtle Graphics** - Python's built-in drawing library
- **Random Module** - For generating random movement patterns

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your system

### Installation & Execution

1. Clone or download the project files
2. Navigate to the project directory
3. Run the game:
   ```bash
   python turtle_race.py
   ```

### How to Play

1. The game will prompt you to bet on a turtle color (red, blue, or green)
2. Watch as the turtles race with random speeds
3. See if your chosen turtle wins!
4. Click anywhere on the screen to exit the game

## 💻 Code Explanation

The game works as follows:

1. **Setup**: Creates a graphical window and three turtle objects
2. **User Input**: Prompts the player to bet on a winning color
3. **Race Logic**: Moves each turtle forward by random increments
4. **Win Detection**: Checks which turtle reaches the finish line first
5. **Result Display**: Shows colored screen based on win/loss outcome

Key functions:
- `race_turtles()`: Controls the main race loop
- `display_result()`: Shows win/loss message with appropriate colors

## 🌟 Features

- **Simple Interface**: Easy-to-understand graphical display
- **Randomized Gameplay**: Every race has different outcomes
- **Visual Feedback**: Color-coded results screen
- **Educational Value**: Great for learning Python basics

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

Possible enhancements:
- Add more turtles with different colors
- Implement difficulty levels
- Add sound effects
- Create a scoring system

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

If you have any questions or suggestions, feel free to reach out!

---

🐢 **Enjoy the race!** 🏁

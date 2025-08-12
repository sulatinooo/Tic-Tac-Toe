# Unbeatable Tic Tac Toe AI 🎮

An interactive web-based Tic Tac Toe game featuring an unbeatable AI opponent powered by the Minimax algorithm. Try your best - you won't win against the optimal mode!

**[🎯 Play Live Demo](https://your-username.github.io/tic-tac-toe-minimax/)**

![Tic Tac Toe Game Screenshot](https://via.placeholder.com/600x400?text=Game+Screenshot)
<!-- Replace with actual screenshot after deployment -->

## ✨ Features

- **Unbeatable AI**: Implements Minimax algorithm for optimal play
- **Two Difficulty Modes**: 
  - Unbeatable (Minimax algorithm)
  - Random (for casual play)
- **Smart Optimizations**: Immediate win detection for faster AI responses
- **Persistent Stats**: Tracks wins, draws, and losses across sessions
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Modern UI**: Glassmorphism design with smooth animations
- **Player Choice**: Option to go first or second

## 🤖 Algorithm Details

The AI uses the **Minimax algorithm** with game tree exploration to evaluate all possible future game states and choose the optimal move.

### How it Works:
1. **Recursive Evaluation**: Explores all possible game outcomes from current position
2. **Score Assignment**: 
   - Win for AI: +1
   - Win for Human: -1  
   - Draw: 0
3. **Optimal Selection**: AI maximizes its score while assuming human minimizes it
4. **Performance Optimization**: Checks for immediate winning moves before running full minimax

### Algorithm Complexity:
- **Time Complexity**: O(b^m) where b is branching factor and m is maximum depth
- **Space Complexity**: O(bm) for recursion stack
- **Maximum Game Tree Nodes**: 9! = 362,880 (pruned significantly in practice)

## 🚀 Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Algorithm**: Minimax with optimal play strategy
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Storage**: LocalStorage API for statistics persistence

## 💻 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/tic-tac-toe-minimax.git
cd tic-tac-toe-minimax
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or simply drag the `index.html` file into your browser.

## 🎮 How to Play

1. Choose your difficulty mode (Unbeatable or Random)
2. Click any empty cell to make your move (you play as 'O')
3. The AI responds automatically (plays as 'X')
4. Try to get three in a row - horizontally, vertically, or diagonally
5. Click "New Game" to reset or "Switch First Player" to let AI start

**Pro tip**: In Unbeatable mode, the best you can achieve is a draw!

## 📊 Project Structure

```
tic-tac-toe-minimax/
│
├── index.html          # Main game file with embedded CSS and JavaScript
├── README.md          # Project documentation
└── screenshots/       # Game screenshots (optional)
    └── game.png
```

## 🧠 Learning Outcomes

Building this project helped me understand:
- Game theory and decision trees
- Recursive algorithms and backtracking
- Time/space complexity optimization
- DOM manipulation and event handling
- CSS animations and responsive design
- State management in JavaScript

## 🔄 Original Implementation

This web version is based on my original C++ implementation, which featured:
- 2D array board representation
- Console-based gameplay
- Same Minimax algorithm logic
- Random selection among equally optimal moves

The JavaScript version maintains the same unbeatable AI strategy while adding an interactive web interface.

## 🚦 Future Enhancements

- [ ] Add Alpha-Beta pruning for performance optimization
- [ ] Implement difficulty levels with depth-limited search
- [ ] Add multiplayer mode (local/online)
- [ ] Create AI vs AI demonstration mode
- [ ] Add move history and replay functionality
- [ ] Implement different board sizes (4x4, 5x5)
- [ ] Add sound effects and enhanced animations

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/tic-tac-toe-minimax/issues).

## 👤 Author

**Your Name**

- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your Name](https://linkedin.com/in/your-profile)
- Portfolio: [yourwebsite.com](https://yourwebsite.com)

## 🌟 Acknowledgments

- Inspired by classic game theory and AI algorithms
- Built as part of my journey to secure a CS internship
- Thanks to [Anthropic's Claude](https://www.anthropic.com) for helping translate C++ to JavaScript

---

**Challenge**: Can you beat the AI in Unbeatable mode? (Spoiler: You can't! 😄)
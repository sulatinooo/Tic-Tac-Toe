# Unbeatable Tic Tac Toe AI 

An interactive web-based Tic Tac Toe game featuring an unbeatable AI opponent powered by the Minimax algorithm.

**[ Play: ](https://sulatinooo.github.io/Tic-Tac-Toe/)**

##  Features


- **Unbeatable AI**: Implements Minimax algorithm for optimal play
- **Two Difficulty Modes**: 
  - Unbeatable (Minimax algorithm)
  - Random (for casual play)
- **Smart Optimizations**: Immediate win detection for faster AI responses
- **Persistent Stats**: Tracks wins, draws, and losses across sessions
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Modern UI**: Glassmorphism design with smooth animations
- **Player Choice**: Option to go first or second

##  Algorithm Details

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

##  Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Algorithm**: Minimax with optimal play strategy
- **Styling**: CSS Grid, Flexbox, CSS Animations
- **Storage**: LocalStorage API for statistics persistence

##  How to Play

1. Choose your difficulty mode (Unbeatable or Random)
2. Click any empty cell to make your move (you play as 'O')
3. The AI responds automatically (plays as 'X')
4. Try to get three in a row - horizontally, vertically, or diagonally
5. Click "New Game" to reset or "Switch First Player" to let AI start

**Pro tip**: In Unbeatable mode, the best you can achieve is a draw!


##  What I learned:

Building this project helped me understand:
- Game theory and decision trees
- Recursive algorithms and backtracking
- Time/space complexity optimization
- DOM manipulation and event handling
- CSS animations and responsive design
- State management in JavaScript

##  Original Implementation

This web version is based on my original C++ implementation, which featured:
- 2D array board representation
- Console-based gameplay
- Same Minimax algorithm logic
- Random selection among equally optimal moves

The JavaScript version maintains the same unbeatable AI strategy while adding an interactive web interface.


##  Author

**Your Name**

- GitHub: [@sulatinooo](https://github.com/sulatinooo)
- LinkedIn: [Sultan Almotiri](https://www.linkedin.com/in/sultan-abdullah-almotiri/)

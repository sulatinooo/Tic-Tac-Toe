Unbeatable Tic Tac Toe AI 
An interactive web-based Tic Tac Toe game featuring an unbeatable AI opponent powered by the Minimax algorithm. Try your best - you won't win against the optimal mode!
 Features:

Unbeatable AI: Implements Minimax algorithm for optimal play
Two Difficulty Modes:

Unbeatable (Minimax algorithm)
Random (for casual play)


Smart Optimizations: Immediate win detection for faster AI responses
Persistent Stats: Tracks wins, draws, and losses across sessions
Responsive Design: Works seamlessly on desktop, tablet, and mobile
Modern UI: Glassmorphism design with smooth animations
Player Choice: Option to go first or second

 Algorithm Details
The AI uses the Minimax algorithm with game tree exploration to evaluate all possible future game states and choose the optimal move.
How it Works:

Recursive Evaluation: Explores all possible game outcomes from current position
Score Assignment:

Win for AI: +1
Win for Human: -1
Draw: 0


Optimal Selection: AI maximizes its score while assuming human minimizes it
Performance Optimization: Checks for immediate winning moves before running full minimax

Algorithm Complexity:

Time Complexity: O(b^m) where b is branching factor and m is maximum depth
Space Complexity: O(bm) for recursion stack
Maximum Game Tree Nodes: 9! = 362,880 (pruned significantly in practice)

 Technologies Used

Frontend: HTML5, CSS3, Vanilla JavaScript
Algorithm: Minimax with optimal play strategy
Styling: CSS Grid, Flexbox, CSS Animations
Storage: LocalStorage API for statistics persistence

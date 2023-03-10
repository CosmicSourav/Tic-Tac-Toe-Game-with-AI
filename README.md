# Tic-Tac-Toe-Game-with-AI
Developed this Tic Tac Toe game with the help of AI (GUI version) using minimax and alpha beta pruning algorithm. This AI will never lose.

The minimax algorithm is a simple way to determine the best move in games like tic-tac-toe, where players can win, lose, or draw. It works by assuming that each player is trying to maximize their chances of winning, while minimizing their opponent's chances. Late in the game, it is easy to see which move is best, but earlier on, the algorithm must work backwards from the end of the game to determine the best move.

Alpha-beta pruning is a modification of the minimax algorithm that reduces the number of nodes that need to be evaluated, allowing for faster and deeper searches. It does this by maintaining two values, alpha and beta, which represent the maximum score that the maximizing player can achieve and the minimum score that the minimizing player can achieve, respectively. As the algorithm progresses, it cuts off branches of the game tree that are unnecessary because there is already a better move available. If the minimum score that the minimizing player can achieve becomes less than the maximum score that the maximizing player can achieve, the parent node should not choose that branch, as it will make the score worse. Therefore, the algorithm does not explore those branches, saving time and computational resources.

Minimax Algorithm Visualisation
![minimax_vis](https://user-images.githubusercontent.com/25551233/224433838-0973f936-fe81-4692-a6e8-857a69636878.png)

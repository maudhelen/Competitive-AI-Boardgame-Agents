# AI: Reasoning & Problem Solving: Application of Agents in Multiplayer Competitive Boardgames

This repository is dedicated to the exploration of AI techniques in the realm of competitive multiplayer board games. It showcases the implementation of AI agents in three classic games: Domineering, Checkers, and Brisca, each employing unique strategies and algorithms to demonstrate the capabilities of AI in game theory and decision-making.

## Domineering
In the Domineering game implementation, AI agents are programmed to strategically place tiles on a grid, blocking the opponent's moves while maximizing their own playing space. The AI uses advanced algorithms to predict and counter the opponent's moves, making it a challenging and competitive game.

## Checkers
The Checkers implementation explores several AI strategies, including MiniMax and Monte Carlo Tree Search (MCTS). These algorithms are optimized for performance, providing a deep insight into the decision-making process of AI in a classic game of Checkers. The AI agents are capable of making strategic moves, capturing opponent pieces, and planning ahead for multiple scenarios.

## Brisca
In Brisca, the AI agents are designed to play the card game with a focus on both offensive and defensive strategies. The implementation includes utility agents that prioritize high-value cards and make strategic decisions to maximize point gains or minimize losses. The AI's decision-making process in Brisca demonstrates a balance between risk-taking and cautious play.

### Concepts tried
1. Utility agent focused on defense. Trying to keep high value card to itself and throwing away only low value.
2. Utility agent focused on attack. Trying to put on the table high value cards to maximize our point gain
3. Combination of the above two. First starting strong, and then focusing on defense.
4. MiniMax. We had some doubts about it in the beginning, because obviously the minimax that we studied in class was aimed at players interchanging turns. However, in the end we decided to give it a try and remake it to suit this game.
side note: In the end we decided to only go with the defense option, because MiniMax lost a quite a few times agains it. 

## Technologies Used
- Python
- Jupyter Notebook
- Various AI algorithms (MiniMax, MCTS, Utility-based agents)

## How to Use
- Clone the repository and navigate to the respective game directories.
- Open the Jupyter notebooks to view the implementation details and run the AI agents.
- Each game folder contains specific instructions and details about the AI strategies used.



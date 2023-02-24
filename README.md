## Dice Game

This repository contains a simple implementation of a dice game in Python. 

### How to Play

1. Run the `dice_game.py` script using the command `python dice_game.py`.
2. You will be prompted to enter the number of players and the number of rounds to play.
3. Each player will take turns rolling two dice.
4. If the sum of the two dice is even, the player's score for that round is the sum of the dice. If the sum is odd, the player's score for that round is 0.
5. After all rounds have been played, the player with the highest total score wins.

### Example

$ python dice_game.py
Enter the number of players: 2
Enter the number of rounds: 3

Round 1:
Player 1 rolls 2 and 5 (total = 7)
Player 2 rolls 3 and 3 (total = 6)

Round 2:
Player 1 rolls 1 and 6 (total = 7)
Player 2 rolls 2 and 2 (total = 4)

Round 3:
Player 1 rolls 4 and 4 (total = 8)
Player 2 rolls 5 and 3 (total = 0)

Final Scores:
Player 1: 22
Player 2: 10

Player 1 wins!



### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- This project was inspired by a similar project in the book "Python for Kids" by Jason R. Briggs.

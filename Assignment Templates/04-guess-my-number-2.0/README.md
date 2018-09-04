# 04-guess-my-number-2.0

Modify the Guess My Number game so that the player has a limited number of guesses. If the player fails to guess in time, the program should display an appropriately chastising message.

Must include:<br>
1. correct file naming convention
2. proper header
3. working code
    * limited number of tries
    * player told the total amount of tires they get
    * player informed of the number of tries they have left after each turn
    * if player looses, tell them what the number was
    * wait for the user before exiting the program

## Example Output
```
Welcome to the Guess My Number game 2.0!
I'm thinking of a number between 1 and 100.
You have 6 tries to guess my number.

Take a guess: 50
That's not my number, you need to guess Lower...
You have 5 tries left.
Guess again: 25
That's not my number, you need to guess Higher...
You have 4 tries left.
...
Guess again: 43
That's my number! 43 You guess it!
OR...
You ran out of tries, too bad.
My number was 43.

Press the enter key to exit.
```

## Rubric
Category | Earned | Possible
 ------ | :----: | ------:
correct file name| |1
proper heading| |1
player told total number of tries| |1
tries remaining displayed| |2
code uses limited number of tries| |2
losing number told| |2
wait for user to exit| |1
Total| |10

# 14-trivia-challenge-2.0

You'll be making improvements to the trivia_challenge.py game. Modify the trivia.txt file to add a point value for each question. Modify the game so that the player's score is the total of all the point values of the questions answered correctly. Also add a way for the game to maintain the top three high scores and players in the highscores.txt file. The program should record the player's name and score only if the player makes the list, ordered by score. Limit the player to entering in their initials (3 characters only), and have the program store them in uppercase.

Must include:<br>
1. correct file naming convention
2. proper header
3. wait for the user before exiting the program
4. working code
    * question point values in trivia.txt
    * player score calculated correctly
    * ask for player name if they made the high score list
    * limit 3 chars and uppercase player name
    * high score works
##Project Hints
* Make sure your read and understand the basic program before you start modifying it.
* I found it easiest to add the point value after the explanation of the correct answer.
* You'll want a nested list where each main element is the (score, name), so that it sorts by name.
* Displaying high scores always shows the highest first.

## Rubric
Category | Earned | Possible
 ------ | :----: | ------:
correct file name & heading & wait to exit| |1
question point values| |1
player score calculated correctly| |2
ask for player name if make list| |2
limit 3 chars and uppercase| |2
can save high scores| |2
Total| |10

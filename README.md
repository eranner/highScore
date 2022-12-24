# highScore
Two ways to keep track of score. The first is straight up vanilla  JavaScript utilizing localStorage to keep track of memory in case the browser is refreshed.
You put in an amount of teams, this will generate using JavaScript the team boxes.
You set a point total(meaning how much each correct answer would be worth)
You set a bonus total(meaning if all answers were correct you add a bonus)

Once in the team box, you can enter a team name.

There is a 'plus' button and a 'minus' button. Tap on the plus for every correct answer and on the minus if you hit the plus too many times.
Tap on the 'bonus' button to add a bonus if it is earned

To clear out the information, click on the 'Clear Scores" button and this will empty out localStorage.

If you accidentally refresh browser, re-input the amount of teams you had and the information will be stored.

## highSchore PHP
The PHP version of High Score is much simpler. You input your team names on the first page and all of your team boxes are generated on the next page.
Instead of the 'plus' and 'minus' buttons, you instead enter the amount in the provided form and the 'update score' button to add the previous number to the score.

If a mistake is made, enter a negative number to bring the score back to where it should be.

To clear the scores out, tap the 'clear all scores' button.

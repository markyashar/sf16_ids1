## Pair Problem (uses Probability too!)

### Monty Hall Problem

Youtube: https://www.youtube.com/watch?v=FzwQu5X5plU

The *Monty Hall Problem* is a famous problem in probability that you may have come across before.  It often confuses people, and part of the confusion stems from ambiguity about Monty's decision process.

The situation is as follows:  There are 3 doors and behind one of them is something "good" (a new car, a prize, a prince or princess, etc.) and the other 2 are "bad" (empty, a goat, lions that tear you to shreds).  You are trying to pick the good door, but initially have no information whatsoever.  Meanwhile, "Monty" (the game show host, moderator, etc) knows what is behind each of the doors.

You choose a door, but before it is opened, Monty chooses a door that a) you did not pick, and b) is bad, and opens it for you, revealing that it is bad.  Important point - Monty knows what is behind all the doors and always will reveal to you an unchosen bad door.  Since there are two bad doors, and you only choose one door, at least one bad door will be unchosen.

Now Monty offers you a choice: Stay with the door you originally chose, or switch to the third door (that you did not initially choose and that he did not reveal).  Which is the better move: Staying or Switching?

For this pair program, we ask you to simulate this game 10,000 times and see empirically which strategy is better.  You need to generate which door has the prize, which door Monty shows you, and whether Staying or Switching was the right move.  Did you get the answer you expect?  Discuss with your partner and others why this answer makes sense (or not)!

Extra Credit: Try simulating now where there are *n* doors.  There is still only one prize, and Monty still shows you an unchosen bad door.  But when you switch, you randomly choose from the unseen and unchosen doors.
This is code for my tic tac toe game. 
I optimized it to allow you to be able to play player vs. player as well as computer vs. player. 
At the very beginning it gives you the option to choose between the two options. 
What you will notice is that I used a variety of while, if & else loops to get the conditions right and get the favorable results. 
Since a typical Tic Tac Toe game consists of 9 spots, and computer logic start counting from 0, I took the thinking out of the game
and allowed for the players to be able to pick between 1-9 instead of 0-8. 
How i got the computer to pick between 0-8 (computer logic) and 0-9 on the board is by using choic = rand() %9 modulo operator. 
What this function does is allows the computer to pick any integer and divide it by 9. The remainder of this integer divided by 9 is the
result that gets picked to go up on the board. ex: 21 / 9 = 2 remainder of 3. That number 3 would be what the computer chooses to go on the board. 

If you take a look at my computer choice loop, here I use a "do" loop. I choose this loop because unlike a "while" loop, the "do" loop
runs the program once then checks to see if the conditions still apply. I did this because had I opened up this function with the while loop,'
it would not act as a "post-test" like the "do" loop does. That way, it allows the computer vs. Player version of the game to continue until 
there are no longer spaces available to see who wins. 

Well that's pretty much it folks! Thank you for stopping by and checking out my code!

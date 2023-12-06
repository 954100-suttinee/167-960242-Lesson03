## [Lesson03](../readme.md) > Exercise03:

1. Open class [Main](../src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code to call Lesson.run() method from `exercise03`.
  
2. Create a ChoHan Game machine for multiple players by modifying [ChoHanGame](../src/main/java/org/dii/oop/exercise03/ChoHanGame.java) class in package `main.java.org.dii.oop.exercise03`.
   * add the two following static variables to [ChoHanGame](../src/main/java/org/dii/oop/exercise03/ChoHanGame.java) class. 


```
   static public int numPlayers = 0; // store the number of players.
   static public int total = 0 ; // store the total amount the machine has.
```

   * find the locations where you need to update this two static variables.
   * Check the overall and try to run it. [Lesson](../src/main/java/org/dii/oop/exercise03/Lesson.java) will call the run method in ChoHanGame.
The output should look like the following example.

```
What is your name ? Gus
Hello Gus Goodluck!
Enter wager: 5
Enter 'e ' for even; anything else for odd: e
You rolled a 8
You won! Winnings so far: 5
Play again? 'y ' or 'Y ' for 'Yes ': y
Enter wager: 10
Enter 'e ' for even; anything else for odd: o
You rolled a 4
You lost! Winnings so far: 5
Play again? 'y ' or 'Y ' for 'Yes ': y
Enter wager: 10
Enter 'e ' for even; anything else for odd: e
You rolled a 4
You won! Winnings so far: 5
Play again? 'y ' or 'Y ' for 'Yes ': n
You won $5
Thanks for playing
What is your name? Glynda
Hello Glynda Goodluck!
Enter wager: 1
Enter 'e ' for even; anything else for odd: e
You rolled a 5
You lost! Winnings so far: 1
Play again? 'y ' or 'Y ' for 'Yes ': y
Enter wager: 10
Enter 'e ' for even; anything else for odd: e
You rolled a 5
You lost! Winnings so far: 11
Play again? 'y' or 'Y ' for 'Yes ': n
You lost $11
Thanks for playing
What is your name? DONE
Number of players : 2
Casino 's winnings : 6
```
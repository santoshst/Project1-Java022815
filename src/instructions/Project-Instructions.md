#Project 1
##5 Problems from Project Euler and CoderByte

For this weekly assignment, you will be working through a set of problems from Project Euler (http://projecteuler.net) or CoderByte (http://coderbyte.com).
Each problem will build upon one of the concepts covered in class. Collaboration is encouraged, and full understanding of the underlying concepts is required.

These problems will not be formally graded, but you might be asked to share your solutions with the class.

-------------


###Name Scores of an alphabetized list

Use the `names.txt` file, a 46K text file containing over five-thousand first names found in the `resources` directory. 

**Part 1:**Begin by sorting the list into alphabetical order. Save this new file as `p1aNames.txt` in the `answers` directory.

**Part 2:** Using `p1aNames.txt`, take the alphabetical value for each name, and multiply this value by its alphabetical position in the list to obtain a name score.
For example, when the list is sorted into alphabetical order, COLIN, which is worth 3 + 15 + 12 + 9 + 14 = 53, is the 938th name in the list. So, COLIN would obtain a score of 938 × 53 = 49714.
Save the list of all name scores as `p1bNames.txt`.

**Part 3:**What is the total of all the name scores in the file? Print out this total to the console in your `.java` file.

**Save your `.java` file in the `answers` directory as `p1.java`.**

---------------------


###Large sums

Use the `longnums.txt` file in the `resources` directory for this problem.

**Part 1:** Build an array of the 100 numbers (each 50 digits long) contained in `longnum.txt`, and sort them according to size (smallest numbers first). Save this file as `p2a.txt` in the `answers` directory.

**Part 2:** Find the first 10 digits of the sum of all 100 numbers, and print the answer to the console.

**Save your `.java` file in the `answers` directory as `p2.java`.**

------------------------


###Poker Hands

In poker, a hand consists of five cards and are ranked, from lowest to highest, in the following way:

+ **High Card**: Highest value card.
+ **One Pair**: Two cards of the same value.
+ **Two Pairs**: Two different pairs.
+ **Three-of-a-kind**: Three cards of the same value.
+ **Straight**: All cards are consecutive values.
+ **Flush**: All cards of the same suit.
+ **Full House**: Three of a kind and a pair.
+ **Four-of-a-kind**: Four cards of the same value.
+ **Straight Flush**: Four cards of the same value.
+ **Royal Flush**: Four cards of the same value.

The cards are valued in the order:
2, 3, 4, 5, 6, 7, 8, 9, 10, Jack, Queen, King, Ace.

If two players have the same ranked hands then the rank made up of the highest value wins; for example, a pair of eights beats a pair of fives (see example 1 below). But if two ranks tie, for example, both players have a pair of queens, then highest cards in each hand are compared (see example 4 below); if the highest cards tie then the next highest cards are compared, and so on.

As an example, consider the five hands dealt to two players in the file `pokerhands.png` in the `resources` directory:


![poker hands](https://raw.githubusercontent.com/Claim-Academy/Project1-Java022815/master/src/resources/pokerhands.png)


**Part 1:** The file `poker.txt` in the `resources` directory. contains one-thousand random hands dealt to two players. Each line of the file contains ten cards (separated by a single space): the first five are Player 1's cards and the last five are Player 2's cards. You can assume that all hands are valid (no invalid characters or repeated cards), each player's hand is in no specific order, and in each hand there is a clear winner.
How many hands does player 1 win? Print the answer to the console and **save your class in the `answers` directory as `p3a.java`.**

**Part 2:** Imagine that there was a third player. Generate a possible hand for the third player given a standard deck with no Jokers, and given that no duplicate cards exist in the deck, and given the cards that Players 1 and 2 already have in their hands (i.e. each new hand should be generated from decks that do not contain the cards held in Player 1's or Player 2's hands). **Add Player 3's cards to `poker.txt`, and save the new file as `pokernew.txt` in the `answers` directory. Save your code for this section as `p3b.java`.**

**Part 3:** If we look at `pokernew.txt` instead of `poker.txt`, how many hands does player1 win now? Modify `p3a.java` from Part 1 to ask the user for an input (ask if there are 2 or 3 players in the game). Print the number of games Player 1 wins in each situation to the console. **Save this modified code as `p3c.java` in the `answers` directory.**

------------------------------

###Consecutive Numbers


**Part 1:** Build your own array of all of the prime numbers up to 100, and store that array in a text file `primearray.txt` in the `answers` directory. **Save your code as `p4a.java` in the `answers` directory**.

**Part 2:** Have the class ` Consecutive` take an array of integers from `primearr.txt` and return the minimum number of integers needed to make the contents of the array consecutive from the lowest number to the highest number. For example: If `arr` contains `[4, 8, 6]` then the output should be 2, because two numbers need to be added to the array (5 and 7) to make it a consecutive array of numbers from 4 to 8. Print out the answers for arrays of the first 5 primes, the first 10 primes, the first 50 primes, and the first 100 prime numbers on separate lines.
**Save your code as `p4b.java` in the `answers` directory.**

--------------------------------







# Lab-04

Update this README to include your team name and team members. Don't forget to record all your answers to lab 04 here.
Lab-04-Team-10

1. Olivia Daw 
2. Benyamin Shahmohammadi 
3. Yun-Ting Lin 
4. Michael Shirley

Exercise 1 
====
1. List three data types used in this program? Number, list, string 
2. List any value variables or reference variables in this program? Letter, computerLetter, turn 
3.Give an example of a sequence in this program.
while not (letter == 'X' or letter == 'O'):
  print('Do you want to be X or O?')
  letter = input().upper()
  
the first element in the list is the player’s letter, the second is the computer's letter.
 if letter == 'X':
  return ['X', 'O']
 else:
  return ['O', 'X']
4.ve an example of a condition in this program.
def whoGoesFirst():
 Randomly choose the player who goes first.
 if random.randint(0, 1) == 0:
  return 'computer'
 else:
  return 'player'
5. S
6. S
7. Give an example of a function that has at least one parameter in this program. And, briefly explain what the function is trying to achieve? Example is: def chooseRandomMoveFromList(board, movesList):, Purpose: Returns a valid move from the passed list on the passed board and Returns None if there is no valid move.
8. The isWinner Function. It searches each possible winning combination to determine if the game is over. It is called in the While True loop
9. It doesnt change it, both of the logical paths depend on the same condition. If the loop breaks the game is over, if isGamePlaying is false, then its over also
10. While True starts a loop without a variable as a condition and continues until the loop is broken inside itself. You parse a type into a conditional loop which depends on the type, since it is parsed a type instead of a variable You cant change the conditional unless you break it inside.

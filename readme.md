Guessing Game
=============

The project provides the basic overview for creating a number guessing game.

Learning Objectives
-------------------

After completing this lab, students will be able to:

1. Use loops to repeat block of code
2. Nest conditionals within loops to alter repeated behavior

Requirements
------------

The program should begin by asking the user if they would like to guess a number or think of a number to be guessed.

If the user chooses to guess a number, a random number between 1 and 31 should be generated for the user to guess. The user should then be prompted for guesses. The system should respond offering a clue as to whether the unknown number is higher or lower than the guess and then request a new guess. This process should continue until a number is guessed successfully.


Here's an example run showing the user guessing the computers number:

```
Would you like to:
1) Guess my number
2) Pick a number for me to guess
Enter selection: 1

Great! You'll try to guess my number between 1 and 31.
What is my number? 7
My number is higher.
What is my number? 25
My number is lower.
What is my number? 17
My number is higher.
What is my number? 21
My number is higher.
What is my number? 22
You got it right in 5 guesses!
```

If the user would like to have their number guessed, the program should supply a guess and ask if it is too high or too low. The user should then be prompted with  options to select if their number is correct, higher, or lower than the guess. If the guess is correct, the program should terminate with a useful message of some kind. If the guess is incorrect the, guessing process should repeat.

Here's an example run showing the computer guessing the user's number. The user selected 13.

```
Would you like to:
1) Guess my number
2) Pick a number for me to guess
Enter selection:2

Alright! I'll try to guess your number.
Make sure you pick a number between 1 and 31

My guess is 24
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:2

My guess is 8
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:1

My guess is 16
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:2

My guess is 12
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:1

My guess is 14
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:2

My guess is 13
How did I do?
1) My number is higher
2) My number is lower
3) That's my number
Make selection:3

That took me 6 guesses.
Thanks for playing with me!
```

In both game formats, the number of guesses used should be displayed.

Helpful Python Features
-----------------------

You will likely want to use all of the following:

- Loop (`for` or `while`)
- Branching (`if`, `elif`, `else`)
- Imports and built-in functions
    - `random.randint` to get a random number
    - `print` to display output
    - `input` to get input
    - `int` for converting strings to integers
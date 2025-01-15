# Ugly trivia kata

Goal: learn how to improve legacy code by using acceptance testing

# Instructions

## Step 0 - run the application

Choose a programming langugae then follow the Instructions in the README
to make sure you can run the application.

## Step 1 - golden master

You will have to :
* Make sure the production code can run in a deterministic manner,
* Capture messages printed to the console.

Try and do this without changing the production code too much.

Once the run of the game is deterministic, you can write a test.

It should compare the actual output with an expected output (stored in a text file).

In case a bug is introduced in the pcoduction code, the test should fail, showing
the lines that have changed.

## Step 2

Measure coverage and try to improve it.

## Step 3

Start cleaning the code, adding unit tests when you can.


# Credits

Inspired by :

https://kata-log.rocks/ugly-trivia-kata

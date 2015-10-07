This is an old game played with pencil and paper that was later implemented on computer.
The task is for the program to create a four digit random number from the digits 1 to 9, without duplication. The program should ask for guesses to this number, reject guesses that are malformed, then print the score for the guess.
The score is computed as:

* The player wins if the guess is the same as the randomly chosen number, and the program ends.
* A score of one bull is accumulated for each digit in the guess that equals the corresponding digit in the randomly chosen initial number.
* A score of one cow is accumulated for each digit in the guess that also appears in the randomly chosen number, but in the wrong position.

Source: http://rosettacode.org/wiki/Bulls_and_cows
# algorithm_practice

Algorithm that read a sentence, which ends with a point, character by character, and to determine find:

1. The length of the sentence (the number of characters).
2. The number of words in the sentence (assuming that the words are separated by a single space).
3. The number of vowels in the sentence.
   /_========================= Variables==============================_/
   // First figure out method to factor lenght of sentence (the number of characters)
   // Declare variables for the:
   // Word counter as word_counter to count the word in the sentence,
   // Character counter as char_counter to count the character
   // Vowel counter as vowel_counter to count the vowel in the statement
   // Space counter to count the space in the sentence

// Read the statement for checking (with "Read")

//use while loop to go through the statement for checking
// WHILE (i < sentence.length ) DO
// the algorithm start by reading the statement, after reading it
// While loop will iterate the lenght of the statement as long as is lessthan i

/_IF (sentence[i] = " ") THEN
space_counter = space_counter + 1
ELSE
char_counter = char_counter + 1
END_IF_/
// IF condition above will check
// if lenght of sentence (sentence.length) is lessthan i, then the IF condition will execute,
// in the IF condition, if sentence array index value is empty space, space counter will increment
// else character counter will increment it will iterate untill i >= sentence.length then it stop

// ==========================================================================================

// Switch statement to check for vowels vowels character in a statement
The expression is evaluated once.
The Read sentence (sentence[i]) of the expression is compared with the values of each case(to find a,e,i,o,u).
If there is a match, the associated block of code will be executed with increment vowel_counter by 1 in every iteration.
If there is no match, the default code block is executed.
This step will continue till the last character of the statement.

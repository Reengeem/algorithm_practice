# algorithm_practice

Algorithm that read a sentence, which ends with a point, character by character, and to determine find:

1. The length of the sentence (the number of characters).
2. The number of words in the sentence (assuming that the words are separated by a single space).
3. The number of vowels in the sentence.
   /============================ Variables==============================\_/
   First figure out method to factor lenght of sentence (the number of characters)
   // Declare variables for the at line 7:
   1. Word counter as word_counter to count the word in the sentence,
   2. Character counter as char_counter to count the character
   3. Vowel counter as vowel_counter to count the vowel in the statement
   4. Space counter to count the space in the sentence

// Read the statement for checking (with "Read")

1. use while loop to go through the statement for checking at line 15
2. WHILE (i < sentence.length ) DO
3. The algorithm start by reading the statement, after reading it
4. While loop will iterate the lenght of the statement as long as is lessthan i at line 15

/_IF (sentence[i] = " ") THEN
space_counter = space_counter + 1
ELSE
char_counter = char_counter + 1
END_IF_/ 5. IF condition above will check if lenght of sentence (sentence.length) is lessthan i in line 18, then the IF condition will execute by incrementing space_counter by 1 at line 19, 6. in the IF condition, if sentence array index value is empty space, space counter will increment
// else character counter will increment at line 21, it will iterate untill i >= sentence.length then it stop

// ==========================================================================================

 <!--------- Switch statement to check for vowels vowels character in a statement ---------->

1. The Read sentence (sentence[i]) of the expression is compared with the values of each case(to find a,e,i,o,u).
2. If there is a match in any case from line 32 to line 36, the associated block of code will be executed with increment vowel_counter by 1 in every iteration.
3. If there is no match, the default code block is executed at line 37.
   This step will continue till the last character of the statement.

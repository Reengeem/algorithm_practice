ALGORITHM TO CHECK IF A WORD IS PALLINDROME

1. first a fucntion is created that will reverse a word from the last element to the first, taking the last element to be the first till the word.length = 0 using a FOR loop at line 30 and 31.
2. each element is concatenated with string type variable declared as testString, it will contcatenate in each iteration untill word.lenghth <= 0.
3. the reverse_string function will return the tsetSring with the reversed word.

4. The function reverse_Stringe is called at line to reverse the Read(word).
5. the IF condition in line 8 to 10 check if word contains a single character of an empty space, if yes then it will read the WOR IS Palindrome and END_IF, else it will move to the next if.
6. The next IF at line 13 compare the ending character in each word against the other if they are equal.
7. if the word.length and reverse_word.length are equal then the IF condition at line 15 compare the reversed string againts each other to check if the word is a palindrome.
8. if word = reverse_stringe then it will write "it is a palindrome" else it is not a palindrome.

INSERTION SORT START HERE
HOW THE ALGORITHM WORK

1. Four integer variaables are declared (i, j, n, temp : INTEGER) in line 13.
2. the user is prompted to give n size of array to be sorted betweeen 1 and z ( z is the size of the array which can any valid size).
3. Line 25 is a FOR loop that read the array element.
4. the array is the divided into sorted and unsorted array
5. From line 31 The second element in the array is temporary removed as array key.
6. The loop will check if the key that was removed from j+1 is bigger than item to the left of the selected item loop through till then last item
7. check if the item removed from the temporary storage is smaller than the current jth item.
8. if the key is lessthan the selected item, then the first item that was selected will be swap with the temporay storage.
9. then the first and second element are now sort,the array will increment j++.
10. The third array will now be considered as the temporary storage where the item is now the new key, the process will continue until the last array item is sorted.

<!-- Insertion sort ends here -->

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

Read the statement for checking (with "Read")

1. use while loop to go through the statement for checking at line 15
2. WHILE (i < sentence.length ) DO
3. The algorithm start by reading the statement, after reading it
4. While loop will iterate the lenght of the statement as long as is lessthan i at line 15

<!-- IF (sentence[i] = " ") THEN
space_counter = space_counter + 1
ELSE
char_counter = char_counter + 1
END_IF -->

5. IF condition above will check if lenght of sentence (sentence.length) is lessthan i in line 18, then the IF condition will execute by incrementing space_counter by 1 at line 19, 6. in the IF condition, if sentence array index value is empty space, space counter will increment else character counter will increment at line 21, it will iterate untill i >= sentence.length then it stop

6. Line 50 write the count character with Write(char_counter);
7. Line 51 write the count the word with Write(word_counter);
8. Line 52 write the count vowel with Write(vowel_counter);

// ==========================================================================================

 <!--------- Switch statement to check for vowels vowels character in a statement ---------->

1. The Read sentence (sentence[i]) of the expression is compared with the values of each case(to find a,e,i,o,u).
2. If there is a match in any case from line 32 to line 36, the associated block of code will be executed with increment vowel_counter by 1 in every iteration.
3. If there is no match, the default code block is executed at line 37.
   This step will continue till the last character of the statement.

<!--===================================== Checkpoint Introduction to Data Structures and Procedural programming * -->

Funtion to get the distinct value in a two array element

1. line 4 is creation of function to get array element to get array element from user.
2. line 7 is a declaration of vaariable.
3. line 3 is declaration of array of n size.
4. line 11 to 16 is a loop that will allow the user to enter mulitple array element to the array.

function to find the distinct value

1.  funtion is created as find_distinct with y,z,set1 and set2 as the parameters, then integer variable are declared in line 25,
2.  the two arrays are declared and y and z size in line 26 and 27.
3.  line 30 is loop to get the distinct value from both arrays where first item in set1[i] will be compared with items in set2[i] to find if they are equal, it will iterate until j = z-1 in the nested loop, then i=1++.
4.  The IF in line 36 is to ccheck the distinct between set1[1] and set2[i].

5.  the sum varible in line 37 get the distinct value from the loop.

6.  The function will RETURN the sum.

7.  line 58 prompt the user to enter the size off the arrra n.
8.  line 63 and 74 call the function to get elements of the first and array and set it to a and b variables.

9.  line 76 call the function check_distinct to check to distinct and sum them
10. line 80 write the sum of the dictinct value.

<!-- ============Finish Algorithm to find disticnt value between two variables======== -->

<!-- Dot product Algorithm -->

FUNCTION TO GET DOT PRODUCT

1. Function is created to get the value of both vector
2. IF condition is use to compare the size of array, if is equal then v1[i] will be multiply with v2[i] to get the product, and sum with ps to get the sum of the product.
3. the condition will iterate till i = v1.lenght-1

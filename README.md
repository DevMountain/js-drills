# js-drills

This repo contains a plethora of Javascript problems for extra practice. We recommend that you first complete all the algorithm scripting (basic, intermediate, and advanced) in the [pre-course materials](http://precourse.devmounta.in/) and then go through these if you still want additional practice. By completing both the pre-course materials and the drills here, you can claim the title of "Javascript Ninja". :punch:

## Functions

1. Write a JavaScript function that reverses a number.
	* Example x = 32243;
	* Expected Output : 34223	

2. Write a JavaScript function that checks whether a passed string is palindrome or not.
A palindrome is word, phrase, or sequence that reads the same backward as forward, e.g., `madam` or `nurses run`. Make sure to take care of spaces and capital letters.

3. Write a JavaScript function that generates all combinations of a string.
	* Example string : 'dog' 
	* Expected Output : d,do,dog,o,og,g 

4. Write a JavaScript function that returns a passed string with letters in alphabetical order.
	* Example string : 'webmaster' 
	* Expected Output : 'abeemrstw'

5. Write a JavaScript function that accepts a string as a parameter and converts the first letter of each word of the string in upper case.
	* Example string : 'the quick brown fox' 
	* Expected Output : 'The Quick Brown Fox'

6. Write a JavaScript function that accepts a string as a parameter and find the longest word within the string.
	* Example string : 'Web Development Tutorial' 
	* Expected Output : 'Development'

7. Write a JavaScript function that accepts a string as a parameter and counts the number of vowels within the string.
  * Note : As the letter 'y' can be regarded as both a vowel and a consonant, we do not count 'y' as vowel here. 
  * Example string : 'The quick brown fox' 
  * Expected Output : 5

8. Write a JavaScript function that accepts a number as a parameter and check the number is prime or not.
	* Note : A prime number (or a prime) is a natural number greater than 1 that has no positive divisors other than 1 and itself.

9. Write a JavaScript function which accepts an argument and returns the type.
	* Note : There are six possible values that typeof returns: object, boolean, function, number, string, and undefined.

10. Write a JavaScript function which will take an array of numbers and find the second lowest and second greatest numbers, respectively.
  * Sample array : [1,2,3,4,5]
  * Expected Output : 2,4 

11. Write a JavaScript function to compute the factors of a positive integer.

12. Write a JavaScript function to convert an amount to coins.
	* Sample function : amountToCoins(46, [25, 10, 5, 2, 1])
	* Here 46 is the amount. and 25, 10, 5, 2, 1 are coins. 
	* Output : 25, 10, 10, 1.

13. Write a JavaScript function to extract unique characters from a string.
	* Example string : "thequickbrownfoxjumpsoverthelazydog"
	* Expected Output : "thequickbrownfxjmpsvlazydg".

14. Write a JavaScript function to get the number of occurrences of each letter in specified string.

15. Write a JavaScript function that takes in an array and a number and returns only the elements larger than the specified number.

16. Write a JavaScript function to get all possible subsets with a fixed length (for example 2) combinations in an array.
	* Sample array : [1, 2, 3] and subset length is 2 
	* Expected output : [[2, 1], [3, 1], [3, 2], [3, 2, 1]].

17. Write a JavaScript function that accepts two arguments, a string and a letter and the function will count the number of occurrences of the specified letter within the string.
	* Sample arguments : 'w3resource.com', 'o' 
	* Expected output : 2 

18. Write a JavaScript function to find the first non-repeated character.
  * Sample arguments : 'abacddbec' 
  * Expected output : 'e' 

19. Write a JavaScript function to apply a Bubble Sort algorithm. 
Note : According to wikipedia "Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that works by repeatedly stepping through the list to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order". 
  * Sample array : [12, 345, 4, 546, 122, 84, 98, 64, 9, 1, 3223, 455, 23, 234, 213]
  * Expected output : [3223, 546, 455, 345, 234, 213, 122, 98, 84, 64, 23, 12, 9, 4, 1]

20. Write a JavaScript function that accept a list of country names as input and returns the longest country name as output. 
  * Sample function : Longest_Country_Name(["Australia", "Germany", "United States of America"])
  * Expected output : "United States of America"

21. Write a JavaScript function to find the longest substring in a given a string without repeating characters.

22. Write a JavaScript program to pass a 'JavaScript function' as parameter.

23. Write a JavaScript function to get the function name.

## Conditional Statements and Loops

1. Write a function that accept two integers and displays the larger.

2. Write a function using a conditional statement to find the sign of product of three numbers. Display an alert box with the specified sign.
	* Sample numbers : 3, -7, 2 
	* Output : The sign is - 

3. Write a function using a conditional statement to sort three numbers. Display an alert box to show the result.
	* Sample numbers : 0, -1, 4 
	* Output : 4, 0, -1 

4. Write a function with a conditional statement to find the largest of five numbers. Display an alert box to show the result.
	* Sample numbers : -5, -2, -6, 0, -1 
	* Output : 0 

5. Write a for loop that will iterate from 0 to 15. For each iteration, it will check if the current number is odd or even, and display a message to the screen.
	* Sample Output : 
		* "0 is even" 
		* "1 is odd" 
		* "2 is even" 

6. Write a function which computes the average marks of the following students Then, this average is used to determine the corresponding grade.

    ```
    | Student Name  | Marks |
    | David         |  80   |
    | Vinoth        |  77   |
    | Divya         |  88   |
    | Ishitha       |  95   |
    | Thomas        |  68   |
    ```

  ```
  The grades are computed as follows:
  | Range | Grade |
  |  <60  |   F   |
  |  <70  |   D   |
  |  <80  |   D   |
  |  <90  |   B   |
  | <100  |   A   |
  ```

7. Write a function which iterates the integers from 1 to 100. For multiples of three console.log "Fizz" instead of the number and for the multiples of five console.log "Buzz". For numbers which are multiples of both three and five console.log "FizzBuzz".

8. Write a function to construct the following pattern, using a nested for loop.
  ```javascript
  *  
  * *  
  * * *  
  * * * *  
  * * * * *  
  ```

9. Write a function to compute the greatest common divisor (GCD) of two positive integers.

10. Write a function to sum the multiples of 3 and 5 under 1000.

## Strings

1. Write a JavaScript function to check whether an `input` is a string or not.
	* Test Data :
	```javascript
	console.log(is_string('w3resource')); 
	true
	console.log(is_string([1, 2, 4, 0]));
	false
	```

2. Write a JavaScript function to check whether a string is blank or not.
	* Test Data :
	```javascript
	console.log(is_Blank('')); 
	console.log(is_Blank('abc'));
	true 
	false
	```

3. Write a JavaScript function to split a string and convert it into an array of words.
	* Test Data :
	```javascript
	console.log(string_to_array("Robin Singh"));
	["Robin", "Singh"]
	```

4. Write a JavaScript function to remove specified number of characters from a string.
	* Test Data :
	```javascript
	console.log(truncate_string("Robin Singh",4));
	"Robi"
	```

5. Write a JavaScript function to parameterize a string.
	* Test Data :
	```javascript
	console.log(string_parameterize("Robin Singh from USA."));
	"robin-singh-from-usa"
	```

6. Write a JavaScript function to capitalize the first letter of a string.
	* Test Data :
	```javascript
	console.log(capitalize('js string exercises'));
	"Js string exercises"
	```

7. Write a JavaScript function to capitalize the first letter of each word in a string.
	* Test Data :
	```javascript
	console.log(capitalize_Words('js string exercises'));
	"Js String Exercises"
	```

8. Write a JavaScript function that takes a string which has lower and upper case letters as a parameter and converts upper case letters to lower case, and lower case letters to upper case.
	* Test Data :
	```javascript
	console.log(swapcase('AaBbc'));
	"aAbBC"
	```

9. Write a JavaScript function to concatenates a given string n times (default is 1).
	* Test Data :
	```javascript
	console.log(repeat('Ha!')); 
	console.log(repeat('Ha!',2)); 
	console.log(repeat('Ha!',3));
	"Ha!" 
	"Ha!Ha!" 
	"Ha!Ha!Ha!"
	```

10. Write a JavaScript function to humanized number (Formats a number to a human-readable string.) with the correct suffix such as 1st, 2nd, 3rd or 4th.
	* Test Data :
	```javascript
	console.log(humanize_format()); 
	console.log(humanize_format(1)); 
	console.log(humanize_format(8)); 
	console.log(humanize_format(301)); 
	console.log(humanize_format(402)); 
	"1st" 
	"8th" 
	"301st" 
	"402nd"
	```

11. Write a JavaScript function to truncates a string if it is longer than the specified number of characters. Truncated strings will end with a translatable ellipsis sequence ("…") (by default) or specified characters.
	* Test Data :
	```javascript
	console.log(text_truncate('We are doing JS string exercises.')) 
	console.log(text_truncate('We are doing JS string exercises.',19))
	console.log(text_truncate('We are doing JS string exercises.',15,'!!'))
	"We are doing JS string exercises." 
	"We are doing JS ..." 
	"We are doing !!"
	```

12. Write a JavaScript function to chop a string into chunks of a given length.
	* Test Data :
	```javascript
	console.log(string_chop('w3resource')); 
	console.log(string_chop('w3resource',2)); 
	console.log(string_chop('w3resource',3));
	["w3resource"] 
	["w3", "re", "so", "ur", "ce"] 
	["w3r", "eso", "urc", "e"]
	```

13. Write a JavaScript function to count the occurrence of a substring in a string.
	* Test Data :
	```javascript
	console.log(count("The quick brown fox jumps over the lazy dog", 'the'));
	Output :
	2
	console.log(count("The quick brown fox jumps over the lazy dog", 'fox',false));
	Output :
	1
	```

14. Write a JavaScript function to truncate a string to a certain number of words.
	* Test Data :
	```javascript
	console.log(truncate('The quick brown fox jumps over the lazy dog', 4));
	Output : 
	"The quick brown fox"
	```

15. Write a JavaScript function to alphabetize a given string.
Alphabetize string : An individual string can be alphabetized. This rearranges the letters so they are sorted A to Z.
	* Test Data :
	```javascript
	console.log(alphabetize_string('United States'));
	Output : 
	"SUadeeinsttt"
	```

16. Write a JavaScript function to find a word within a string.
	* Test Data :
	```javascript
	console.log(search_word('The quick brown fox', 'fox')); 
	console.log(search_word('aa, bb, cc, dd, aa', 'aa'));
	Output : 
	"'fox' was found 1 times." 
	"'aa' was found 2 times."
	```

17. Write a JavaScript function to convert a string to title case.
	* Test Data :
	```javascript
	console.log(sentenceCase('PHP exercises. python exercises.')); 
	"Php Exercises. Python Exercises."
	```

18. Write a JavaScript function to remove HTML/XML tags from string.
	* Test Data :
	```javascript
	console.log(strip_html_tags('<p><strong><em>PHP Exercises</em></strong></p>'));
	"PHP Exercises"
	```

19. Write a JavaScript function to create a case-insensitive search.
	* Test Data :
	```javascript
	console.log(case_insensitive_search('JavaScript Exercises', 'exercises')); 
	"Matched"
	console.log(case_insensitive_search('JavaScript Exercises', 'Exercises')); 
	"Matched"
	console.log(case_insensitive_search('JavaScript Exercises', 'Exercisess')); 
	"Not Matched"
	```

20. Write a JavaScript function to Uncapitalize  the first character of a string.
	* Test Data :
	```javascript
	console.log(Uncapitalize('Js string exercises'));
	"js string exercises"
	```

21. Write a JavaScript function to Uncapitalize the first letter of each word of a string.
	* Test Data :
	```javascript
	console.log(unCapitalize_Words('Js String Exercises'));
	"js string exercises"
	```

22. Write a JavaScript function to capitalize each word in the string.
	* Test Data :
	```javascript
	console.log(capitalizeWords('js string exercises'));
	"JS STRING EXERCISES"
	```

23. Write a JavaScript function to uncapitalize each word in the string.
	* Test Data :
	```javascript
	console.log(unCapitalizeWords('JS STRING EXERCISES'));
	"js string exercises"
	```

24. Write a JavaScript function to test whether the character at the provided (character) index is upper case.
	* Test Data :
	```javascript
	console.log(isUpperCaseAt('Js STRING EXERCISES', 1));
	false
	```

25. Write a JavaScript function to test whether a string ends with a specified string.
	* Test Data :
	```javascript
	console.log(endsWith('JS string exercises', 'exercises'));
	true
	```
  
## Arrays

1. Write a JavaScript function to get the first element of an array. Passing a parameter 'n' will return the first 'n' elements of the array. 
	* Test Data : 
	```javascript
	console.log(first([7, 9, 0, -2])); 
	console.log(first([],3));
	console.log(first([7, 9, 0, -2],3));
	console.log(first([7, 9, 0, -2],6));
	console.log(first([7, 9, 0, -2],-3));
	7
	[] 
	[7, 9, 0] 
	[7, 9, 0, -2] 
	[] 
	```

2. Write a JavaScript function to get the last element of an array. Passing an optional parameter 'n' will return the last 'n' elements of the array.
	* Test Data : 
	```javascript
	console.log(last([7, 9, 0, -2])); 
	console.log(last([7, 9, 0, -2],3)); 
	console.log(last([7, 9, 0, -2],6));
	-2 
	[9, 0, -2] 
	[7, 9, 0, -2]
	```

3. Write a simple JavaScript function to join all elements of the following array into a string. 
	* Sample array : myColor = ["Red", "Green", "White", "Black"];
	* Expected Output : "Red,Green,White,Black"

4. Write a JavaScript function which accept a number as input and insert dashes (-) between each two even numbers. For example if you accept 025468 the output should be 0-254-6-8.

5. Write a JavaScript function to sort the items of an array.
	* Sample array : var arr1 = [ 3, 8, 7, 6, 5, -4, 3, 2, 1 ];
	* Sample Output : -4,-3,1,2,3,5,6,7,8

6. Write a JavaScript function to find the most frequent item of an array.
	* Sample array : var arr1=[3, 'a', 'a', 'a', 2, 3, 'a', 3, 'a', 2, 4, 9, 3];
	* Sample Output : a ( 5 times ) 

7. Write a JavaScript function which accept a string as input and swap the case of each character. For example if you input 'The Quick Brown Fox' the output should be 'tHE qUICK bROWN fOX'.

8. Write a JavaScript function which prints the elements of the following array. 
Note : Use nested for loops.
	* Sample array : var a = [[1, 2, 1, 24], [8, 11, 9, 4], [7, 0, 7, 27], [7, 4, 28, 14], [3, 10, 26, 7]];
	* Sample Output : 
	```javascript
	"row 0" 
	" 1" 
	" 2" 
	" 1"
	" 24"
	"row 1" 
	...
	```

9. Write a JavaScript function to compute the sum and product of an array of integers.

10. Write a JavaScript function to remove duplicate items from an array (ignore case sensitivity).

11. Write a JavaScript function to display the colors in the following way:
	* Sample data: 
	```javascript
	color = ["Blue ", "Green", "Red", "Orange", "Violet", "Indigo", "Yellow "];
	o = ["th","st","nd","rd"]
	```
	* Sample Output:
	```javascript
	"1st choice is Blue ."
	"2nd choice is Green."
	"3rd choice is Red."
	...
	```

12. Find the leap years in a given range of years.

13. Write a JavaScript function to shuffle an array.

14. There are two arrays with individual values, write a JavaScript function to compute the sum of each individual index value from the given arrays. 
	* Sample data : array1 = [1,0,2,3,4]; array2 = [3,5,6,7,8,13];
	* Expected Output : [4, 5, 8, 10, 12, 13] 

15. Write a JavaScript function to find duplicate values in a JavaScript array.

16. Write a JavaScript function to flatten a nested (any depth) array. If you pass shallow, the array will only be flattened a single level. 
	* Sample Data :
	```javascript
	console.log(flatten([1, [2], [3, [[4]]],[5,6]])); 
	[1, 2, 3, 4, 5, 6]
	console.log(flatten([1, [2], [3, [[4]]],[5,6]], true)); 
	[1, 2, 3, [[4]], 5, 6]
	```

17. Write a JavaScript function to compute the union of two arrays. 
	* Sample Data :
	```javascript
	console.log(union([1, 2, 3], [100, 2, 1, 10]));
	[1, 2, 3, 10, 100]
	```

18. Write a JavaScript function to find the difference of two arrays. 
	* Test Data :
	```javascript
	console.log(difference([1, 2, 3], [100, 2, 1, 10])); 
	["3", "10", "100"]
	console.log(difference([1, 2, 3, 4, 5], [1, [2], [3, [[4]]],[5,6]])); 
	["6"]
	```

19. Write a JavaScript function to remove. 'null', '0', '""', 'false', 'undefined' and 'NaN' values from an array. 
	* Sample array : [NaN, 0, 15, false, -22, '',undefined, 47, null]
	* Expected result : [15, -22, 47]

20. Write a JavaScript function to sort the following array of objects by title value.
	* Sample object :
	```javascript
	var library = [ 
	   { author: 'Bill Gates', title: 'The Road Ahead', libraryID: 1254},
	   { author: 'Steve Jobs', title: 'Walter Isaacson', libraryID: 4264},
	   { author: 'Suzanne Collins', title: 'Mockingjay: The Final Book of The Hunger Games', libraryID: 3245}
	   ];
	   ```
	* Expected result :
	```javascript
	[{
	  author: "Suzanne Collins",
	  libraryID: 3245,
	  title: "Mockingjay: The Final Book of The Hunger Games"
	}, [object Object] {
	  author: "Bill Gates",
	  libraryID: 1254,
	  title: "The Road Ahead"
	}, [object Object] {
	  author: "Steve Jobs",
	  libraryID: 4264,
	  title: "Walter Isaacson"
	}]
	```

21. Write a JavaScript function to find a pair of elements (indices of the two numbers) from an given array whose sum equals a specific target number.
  * Input: numbers= [10,20,10,40,50,60,70], target=50
  * Output: 3, 4

22. Write a JavaScript function to merge two arrays and removes all duplicates elements. 
	* Test data :
	```javascript
	var array1 = [1, 2, 3]; 
	var array2 = [2, 30, 1]; 
	console.log(merge_array(array1, array2));
	[3, 2, 30, 1]
	```

23. Write a JavaScript function to remove a specific element from an array. 
	* Test data :
	```javascript
	console.log(remove_array_element([2, 5, 9, 6], 5));
	[2, 9, 6]
	```

24. Write a JavaScript function to determine if an array contains a specific element.

25. Write a JavaScript function to get nth largest element from an unsorted array. 
	* Test Data :
	```javascript
	console.log(nthlargest([ 43, 56, 23, 89, 88, 90, 99, 652], 4));
	89
	```

26. Write a JavaScript function to create a specified number of elements with pre-filled numeric value array. 
	* Test Data :
	```javascript
	console.log(array_filled(6, 0)); 
	[0, 0, 0, 0, 0, 0]
	console.log(array_filled(4, 11));
	[11, 11, 11, 11]
	```

27. Write a JavaScript function to move an array element from one position to another. 
	* Test Data :
	```javascript
	console.log(move([10, 20, 30, 40, 50], 0, 2));
	[20, 30, 10, 40, 50]
	console.log(move([10, 20, 30, 40, 50], -1, -2));
	[10, 20, 30, 50, 40]
	```
  
## Objects

1. Write a JavaScript function to list the properties of a JavaScript object.
	* Sample object : 
	```javascript
	var student = { 
	name : "David Rayy", 
	sclass : "VI", 
	rollno : 12 };
	```
	* Sample Output : name,sclass,rollno

2. Write a JavaScript function to delete the rollno property from the following object. Also print the object before or after deleting the property.
	* Sample object : 
	```javascript
	var student = { 
	name : "David Rayy", 
	sclass : "VI", 
	rollno : 12 };
	```

3. Write a JavaScript function to get the length of an JavaScript object.
	* Sample object : 
	```javascript
	var student = { 
	name : "David Rayy", 
	sclass : "VI", 
	rollno : 12 };
	```

4. Write a JavaScript function to calculate the area and perimeter of a circle.
	* Note : Create two methods to calculate the area and perimeter. The radius of the circle will be supplied by the user. 

5. Write a JavaScript function to print all the methods in an JavaScript object.
	* Test Data :
	```javascript
	console.log(all_properties(Array));
	["length", "name", "arguments", "caller", "prototype", "isArray", "observe", "unobserve"]
	```

6. Write a JavaScript function to retrieve all the names of object's own and inherited properties.

7. Write a JavaScript function to retrieve all the values of an object's properties.

8. Write a JavaScript function to convert an object into a list of `[key, value]` pairs.

9. Write a JavaScript function to get a copy of the object where the keys have become the values and the values the keys.

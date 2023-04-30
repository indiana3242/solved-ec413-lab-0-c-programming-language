Download Link: https://assignmentchef.com/product/solved-ec413-lab-0-c-programming-language
<br>
<h2>1.1       Problem 1</h2>

Write a C program that accepts an integer from standard input and prints it out as an unsigned binary number. Assume the input integer is 32 bits long. All 32 bits of the integer should be printed (including leading zeros).

Example input, output pairs:

<ul>

 <li>1 → 00000000000000000000000000000001</li>

 <li>74 → 00000000000000000000000001001010</li>

 <li>1042 → 00000000000000000000010000010010</li>

</ul>

<h2>1.2       Problem 2</h2>

Write a C program that accepts a string from standard input representing a signed 16 bit integer and returns the base10 value of the input.

Example input, output pairs:

<ul>

 <li>00100010 11010111 → 8919</li>

 <li>11111111 11110001 → -15</li>

 <li>11111100 00000000 → -1024</li>

</ul>

<h2>1.3       Problem 3</h2>

Write a C program that accepts an 16 bit hex number from standard input and returns unsigned decimal number.

Example input, output pairs:

<ul>

 <li>ABAD → 43949</li>

 <li>9AD7 → 39639</li>

 <li>1234 → 4660</li>

</ul>

<h2>1.4       Problem 4</h2>

Write a C Program that accepts an unsigned integer <em>n </em>from standard input and outputs the <em>n</em>-th Fibonacci’s number.

Example input, output pairs:

<ul>

 <li>0 → 0</li>

 <li>1 → 1</li>

 <li>2 → 1</li>

 <li>3 → 2</li>

 <li>4 → 3</li>

 <li>8 → 21</li>

 <li>17 → 1597</li>

</ul>

<h2>1.5       Problem 5</h2>

Write a program that accepts an unsigned integer <em>n </em>through standard input. This argument determines the size of an array. Next, accept <em>n </em>more unsigned integers from standard input to fill the array. Sort the array ascending using the algorithm of choice. Afterwards, implement a filter function that accepts one argument and builds another array that contains only the elements greater than the given number. The argument of filter function should be passed as the last standard input of your program. Print the filtered array to the output. Example input, output pairs:

<ul>

 <li>5 1 5 8 7 2 5 → 7 8 // Accepts 5 inputs [1, 5, 8, 7, 2], sorts the array and returns the numbers greater than five SEPARATED WITH A SPACE.</li>

 <li>6 4 5 7 1 3 4 3 → 4 4 5 7 // You should return both 4’s</li>

</ul>
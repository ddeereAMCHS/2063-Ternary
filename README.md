# Bitwise Methods

## Due: Mon 2/6 at 11:59 PM

- Create a program called `BitwiseMethods.java`
- Write a method that takes an int as a parameter and returns the number of ones in the binary representation of that number
  - Calculate this using bitwise operators
- Write a method that takes an int which represents an RGBA value (red, green, blue, alpha) and return an array that contains the individual RGBA values
  - The leftmost byte represents red, the next represents green, the next represents blue, and the rightmost byte represents alpha
- Write a method that takes an int and returns whether that int is odd or even
  - Calculate this using bitwise operators
- Write a method that takes two ints and returns the sum of those two numbers
  - Calculate this using bitwise operators (no + operator allowed)
- In your main method:
  - Prompt the user for an int
    - This will be the number for which you must calculate the number of ones in its binary representation
  - Prompt the user for another int
    - This will be the number for which you must calculate the individual RGBA values
  - Prompt the user for another int
    - This will be the number for which you must determine whether it is odd or even
  - Prompt the user for two ints
    - These will be the numbers for which you must calculate the sum
  - Call each method you wrote with the corresponding parameter(s)
  - Print everything you calculated following the format in the example output 

***Example Input:***\
11123\
305419896\
1234567\
316\
828\
***Example Output:***\
The number 11123 has 9 ones in its binary representation\
The number 305419896 comprises the RGBA values of 18, 52, 86, and 120 respectively\
The number 1234567 is odd\
The sum of the numbers 316 and 828 is 1144

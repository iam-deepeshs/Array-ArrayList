# ArrayFunctions Project

## Project Overview
This project contains a Java program that performs two key operations on an array:
1. Separates even and odd numbers from the given array.
2. Finds the index of the first number in a pair with the smallest absolute difference between consecutive elements.

## Files in the Project
- **ArrayFunctions.java**: Contains the functions for array operations.
- **Main.java**: The driver class where user input is taken and appropriate functions are called.

## How to Run the Program
1. Compile both Java files:
   ```sh
   javac ArrayFunctions.java Main.java
   ```
2. Run the Main class:
   ```sh
   java Main
   ```
3. Follow the prompts:
   - Enter the size of the array.
   - Input the array elements.
   - Choose an option to either separate even/odd numbers or find the smallest distance pair.

## Functionalities
### 1. Separate Even and Odd Numbers
- This function segregates even and odd numbers into two separate arrays and prints them.

### 2. Find the Smallest Distance Pair
- Finds the two neighboring numbers in the array with the smallest absolute difference and returns the index of the first number in that pair.

## Example Input/Output
```
Enter the size of the array:
5
Enter the numbers:
4 7 2 9 3

Choose a functionality:
1. Separate even and odd numbers
2. Find the two neighboring numbers with the smallest distance

Enter choice: 1
Even Numbers: 4 2
Odd Numbers: 7 9 3
```
```
Enter choice: 2
The index of the first number with the smallest distance is: 3
```

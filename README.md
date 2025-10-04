# Program 1

1. Input Phase:

    input('Enter a number: ') - Prompts user to enter a number

    int() - Converts the user's input from string to integer

    Num - Stores the converted integer value

2. Even/Odd Check:

    Num % 2 == 0 - Uses modulo operator to check divisibility by 2

    Modulo operation: Returns remainder when Num is divided by 2

    If remainder = 0 → Number is even

    If remainder = 1 → Number is odd

3. Decision Making:

    if condition: Num % 2 == 0 evaluates to True for even numbers
    
    else condition: Executes when the if condition is False (odd numbers)

4. Output Phase:

    Prints appropriate message: "X is even number" or "X is odd number"
    
    Uses comma separation to automatically handle string concatenation


# Program 2

1. Initialized a counter variable sum = 0 to store the cumulative total

2. Iterated 50 times using a for loop with range(1, 51) to generate numbers 1 through 50

3. Accumulated the sum by adding each number sequentially:

{ Start: 0

After 1st iteration: 0 + 1 = 1

After 2nd iteration: 1 + 2 = 3

After 3rd iteration: 3 + 3 = 6

...

Final result: 1275 } 

4. Displayed the output: "The sum of numbers from 1 to 50 is: 1275"

# Pattern

## Aim:
To write a C# program to draw a pattern.

## Equipment Required:
Step 1: Create a class and declare a variable with string datatype

Step 2: Use for loop to check whether the input is a palindrome or not.

Step 3: Use if condition to check whether input is equal to the calculated number.

Step 4: Display the results of the condition of the input using Console.WriteLine().


## Algorithm:


## Program:
```
Developed by :DHARSHAN V
Register No: 212222230031
```
```
using System;
class HelloWorld
{
    static void Main()
    {
        int c = 0, rows = 6;
        for (int i = 0; i < rows; i++)
        {
            for (int s = 0; s < rows - i; s++)
            {
                Console.Write("  ");
            }
            for (int j = 0; j <= i; j++)
            {
                if (i == 0 || j == 0)
                {
                    c = 1;
                }
                else
                {
                    c = c * (i - j + 1) / j;
                }

                Console.Write("   " + c);

            }
            Console.WriteLine();

        }
    }
}
```

## Output:
![Screenshot 2023-10-16 211613](https://github.com/Dharshan011/C-Pattern/assets/113497491/88fc1479-5828-41a9-817f-07aff5b449f4)



## Result:
A C# program for a pascal's triangle is executed successfully.

```markdown
# Table of a Given Number

This program prints the multiplication table of a given number.

## C# Code

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter a number: ");
        int number = int.Parse(Console.ReadLine());

        Console.WriteLine($"Multiplication table for {number}:");
        for (int i = 1; i <= 10; i++)
        {
            Console.WriteLine($"{number} x {i} = {number * i}");
        }
    }
}
```

## How to Run

1. Copy the code into a file named `Program.cs`.
2. Open a terminal and navigate to the directory containing `Program.cs`.
3. Run the following commands:
    ```sh
    csc Program.cs
    ./Program.exe
    ```
4. Enter a number when prompted to see its multiplication table.
```
# C-Sharp_Guide
1.) Create Csharp new project
```Csharp
dotnet new console -n ProjectName
```
2.) Change directory to run project
```Csharp
cd ProjectName
```
3.) Run Project
```Csharp
dotnet run
```
# Introduction to C#
```Csharp
using System;
class Program {
    static void Main() {
        Console.WriteLine("Hello, C#");
    }
}
```
## Variables & Data Types
```Csharp
int age = 25;
float price = 10.5f;
bool isAlive = true;
char grade = 'A';
string name = "Rahul";
```
## Operators in C#
- Arithmetic Operators: +, -, *, /, %
- Comparison Operators: ==, !=, >, <, >=, <=
- Logical Operators: &&, ||, !
- Assignment Operators: =, +=, -=, *=, /=
```Csharp
int a = 10, b = 5;
Console.WriteLine(a + b); // Output: 15
```
## Conditional Statements
- if, else if, else
- switch-case
```Csharp
int number = 10;
if (number > 0) {
    Console.WriteLine("Positive Number");
} else {
    Console.WriteLine("Negative Number");
}
```
```Csharp
int day = 3;
switch (day) {
    case 1:
        Console.WriteLine("Monday");
        break;
    case 2:
        Console.WriteLine("Tuesday");
        break;
    default:
        Console.WriteLine("Other Day");
        break;
}
```
##  Loops in C#
- for loop
- while loop
- do-while loop
- foreach loop (specially for arrays and collections)
```Csharp
for (int i = 1; i <= 5; i++) {
    Console.WriteLine(i);
}
```
```Csharp
int i = 1;
while (i <= 5) {
    Console.WriteLine(i);
    i++;
}
```
```Csharp
int[] numbers = {1, 2, 3, 4, 5};
foreach (int num in numbers) {
    Console.WriteLine(num);
}
```



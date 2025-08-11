# 🌟 C# Beginner Guide - Easy & Clear

This guide helps beginners learn the basics of C# in simple English with useful examples.

---

## ✅ Variables and If Statements

```csharp
int age = 20;

if (age >= 18)
{
    Console.WriteLine("You are an adult.");
}
else
{
    Console.WriteLine("You are a minor.");
}
````

* `if`: checks a condition.
* `else`: runs if the condition is false.

---

## 🔗 Logical Operators

| Operator | Meaning          | Example                     |                   |                |   |             |
| -------- | ---------------- | --------------------------- | ----------------- | -------------- | - | ----------- |
| `&&`     | AND (both true)  | `if (age > 18 && age < 60)` |                   |                |   |             |
| \`       |                  | \`                          | OR (any one true) | \`if (age < 18 |   | age > 60)\` |
| `!`      | NOT (reverse it) | `if (!(age > 18))`          |                   |                |   |             |

---

## ❓ Ternary Operator

Shortcut for `if-else`.

```csharp
int score = 75;
string result = score >= 60 ? "Pass" : "Fail";
Console.WriteLine(result); // Pass
```

---

## 🔄 Switch Statement

### Old Way

```csharp
string light = "Green";

switch (light)
{
    case "Green":
        Console.WriteLine("Go");
        break;
    case "Red":
        Console.WriteLine("Stop");
        break;
    default:
        Console.WriteLine("Invalid signal");
        break;
}
```

### New Way (Switch Expression)

```csharp
string light = "Red";

string action = light switch
{
    "Green" => "Go",
    "Red" => "Stop",
    _ => "Unknown"
};

Console.WriteLine(action);
```

---

## 🕳️ Nullable Types

```csharp
// int a = null; ❌ Error
int? a = null; // ✅ OK
Nullable<int> b = null; // ✅ OK
```

Use `?` to allow a variable to be null.

---

## 🤔 Null-Coalescing Operator `??`

Gives a default value if null.

```csharp
string? name = null;
string finalName = name ?? "No Name";
Console.WriteLine(finalName); // No Name
```

---

## 🔡 User Input (Safe Way)

```csharp
Console.Write("Enter number: ");
bool isValid = int.TryParse(Console.ReadLine(), out int number);

if (!isValid)
{
    Console.WriteLine("Invalid number.");
}
else
{
    Console.WriteLine("You entered: " + number);
}
```

---

## 🔐 Constants

```csharp
const double Pi = 3.14;
// Pi = 4.0; ❌ Error: Cannot change a constant
```

---

## ✂️ String Functions

```csharp
string movie = "  Lord of the Rings  ";

Console.WriteLine(movie.Trim());         // Remove spaces
Console.WriteLine(movie.ToUpper());      // UPPER CASE
Console.WriteLine(movie.ToLower());      // lower case
Console.WriteLine(movie.Length);         // Count letters
Console.WriteLine(movie.Replace("o", "0"));
Console.WriteLine(movie.IndexOf("Ring"));  
Console.WriteLine(movie.Substring(5));   // Part of string
Console.WriteLine(movie.Insert(0, "The ")); 
Console.WriteLine(movie.Contains("Lord")); 
```

---

## ✨ Escape Sequences

```csharp
Console.WriteLine("Hello \"World\""); // Hello "World"
Console.WriteLine("Line1\nLine2");   // New line
Console.WriteLine("Tab\tSpace");     // Tab
```

### Verbatim String

```csharp
Console.WriteLine(@"C:\Users\Me\Documents");
```

---

## 🔁 Loops

### For Loop

```csharp
for (int i = 1; i <= 3; i++)
{
    Console.WriteLine("Count: " + i);
}
```

### While Loop

```csharp
int i = 1;
while (i <= 3)
{
    Console.WriteLine("While: " + i);
    i++;
}
```

### Do While Loop

```csharp
int j = 1;
do
{
    Console.WriteLine("DoWhile: " + j);
    j++;
}
while (j <= 3);
```

---

## 🧮 Math Functions

```csharp
Console.WriteLine(Math.Ceiling(4.3));    // 5
Console.WriteLine(Math.Floor(4.9));      // 4
Console.WriteLine(Math.Round(4.5));      // 5
Console.WriteLine(Math.Abs(-10));        // 10
Console.WriteLine(Math.Pow(2, 3));       // 8
Console.WriteLine(Math.Sqrt(16));        // 4
Console.WriteLine(Math.Max(5, 9));       // 9
Console.WriteLine(Math.Min(5, 9));       // 5
```

---

## 📦 Arrays

### Declare Arrays

```csharp
int[] numbers = { 1, 2, 3, 4 };
string[] cities = { "Cairo", "Paris", "London" };
```

### Access + Update

```csharp
Console.WriteLine(cities[0]); // Cairo
cities[1] = "Tokyo";
```

### Loop through Array

```csharp
foreach (string city in cities)
{
    Console.WriteLine(city);
}
```

---

## 🔢 Count Male and Female

```csharp
char[] genders = { 'm', 'f', 'f', 'm', 'm' };

int male = 0, female = 0;

foreach (char g in genders)
{
    if (g == 'm') male++;
    else if (g == 'f') female++;
}

Console.WriteLine($"Males: {male}, Females: {female}");
```

---

## 🔼 Find Maximum in Array

### Manual Way

```csharp
int[] nums = { 3, 9, 2, 5 };
int max = nums[0];

for (int i = 1; i < nums.Length; i++)
{
    if (nums[i] > max)
        max = nums[i];
}

Console.WriteLine("Max = " + max);
```

### Easy Way

```csharp
Console.WriteLine(nums.Max());
Console.WriteLine(nums.Min());
```

---

## 🔁 Bubble Sort (Manual Sort)

```csharp
int[] numbers = { 5, 2, 9, 1 };
int temp;

for (int i = 0; i < numbers.Length - 1; i++)
{
    for (int j = 0; j < numbers.Length - 1 - i; j++)
    {
        if (numbers[j] > numbers[j + 1])
        {
            temp = numbers[j];
            numbers[j] = numbers[j + 1];
            numbers[j + 1] = temp;
        }
    }
}
```

---

## 🧼 Built-in Sort

```csharp
Array.Sort(numbers);   // Sort ascending
Array.Reverse(numbers); // Descending
```

---

## 🧊 2D Arrays

```csharp
int[,] matrix = {
    {1, 2, 3},
    {4, 5, 6}
};

Console.WriteLine(matrix[1, 1]); // 5

for (int i = 0; i < matrix.GetLength(0); i++)
{
    for (int j = 0; j < matrix.GetLength(1); j++)
    {
        Console.Write(matrix[i, j] + " ");
    }
    Console.WriteLine();
}
```

---

## 🪄 Ranges and Indices

```csharp
string[] letters = { "a", "b", "c", "d", "e" };

Console.WriteLine(letters[^1]); // Last element ("e")

string[] firstThree = letters[0..3]; // a, b, c

foreach (var letter in firstThree)
{
    Console.WriteLine(letter);
}
```

---

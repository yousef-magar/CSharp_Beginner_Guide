## ✅ C# Beginner Guide – MCQ Study Sheet (English + Arabic)

> Multiple Choice Questions with ✅ answers and **simple Arabic explanations** to help beginners study C# easily.

---

### 📘 **Contents**

1. [Variables](#1-variables)
2. [Declaring & Using Variables](#2-declaring--using-variables)
3. [Writing Output](#3-writing-output)
4. [Math Operations](#4-math-operations)
5. [Prefix vs Postfix Increment](#5-prefix-vs-postfix-increment)
6. [Type Conversion](#6-type-conversion)
7. [Strings & Numbers](#7-converting-strings-and-numbers)
8. [`var` Keyword](#8-var-keyword)
9. [String Formatting](#9-string-formatting)
10. [StringBuilder](#10-stringbuilder)
11. [Formatting Numbers](#11-formatting-numbers)
12. [Date & Time](#12-dates-and-time)
13. [User Input](#13-getting-user-input)
14. [Mini Challenges](#14-mini-challenges)
15. [Control Flow & Logic](#15-control-flow--logic)
16. [Arrays & Loops](#16-arrays--loops)
17. [2D Arrays & Indexing](#17-2d-arrays--indexing)

---

## 1. Variables

**Q1.** What is the correct data type to store a whole number in C#?

* A) string
* B) int ✅
* C) float
* D) char
  **📘 الشرح:** `int` يُستخدم لتخزين الأرقام الصحيحة مثل 25.

---

**Q2.** Which data type is best for storing money values?

* A) float
* B) string
* C) decimal ✅
* D) int
  **📘 الشرح:** `decimal` أدق من `float` ويفضل استخدامه مع القيم المالية.

---

**Q3.** What data type would you use for true/false values?

* A) int
* B) bool ✅
* C) char
* D) double
  **📘 الشرح:** `bool` يخزن إما `true` أو `false`.

---

## 2. Declaring & Using Variables

**Q4.** Correct way to declare a string variable in C#:

* A) string name = Ali;
* B) string name = "Ali"; ✅
* C) name = string "Ali";
* D) string = "Ali";
  **📘 الشرح:** القيم النصية يجب أن توضع بين علامات تنصيص `" "`.

---

## 3. Writing Output

**Q5.** What does `Console.WriteLine()` do?

* A) Reads input
* B) Writes on same line
* C) Writes and moves to next line ✅
* D) Closes the program
  **📘 الشرح:** تقوم بطباعة النص ثم تنقلك لسطر جديد.

---

## 4. Math Operations

**Q6.** What is the result of `10 + 3` in C#?

* A) 13 ✅
* B) 7
* C) 30
* D) 3.33
  **📘 الشرح:** 10 + 3 = 13. عملية جمع بسيطة.

---

**Q7.** How to get decimal result from dividing int values?

* A) Use `int`
* B) Use `bool`
* C) Convert one to `double` ✅
* D) Multiply first
  **📘 الشرح:** تحويل أحد الأعداد إلى `double` يعطيك نتيجة عشرية.

---

## 5. Prefix vs Postfix Increment

**Q8.** What does `i++` do?

* A) Increases before using
* B) Decreases the value
* C) Increases after using ✅
* D) Keeps it the same
  **📘 الشرح:** `i++` تعني "استخدم القيمة ثم زدها بعد ذلك".

---

## 6. Type Conversion

**Q9.** What is implicit conversion in C#?

* A) Manually casting big to small
* B) Automatic conversion from small to big ✅
* C) Not allowed
* D) Used in loops
  **📘 الشرح:** يتم التحويل تلقائيًا من نوع صغير إلى نوع أكبر دون فقدان البيانات.

---

**Q10.** What happens when converting `12.9` (double) to `int`?

* A) Converts without loss
* B) Keeps decimals
* C) Rounds the number
* D) Loses the decimal ✅
  **📘 الشرح:** `(int)12.9` يعطيك 12 فقط، ويتم تجاهل الفاصل العشري.

---

## 7. Converting Strings and Numbers

**Q11.** What method converts `"30"` (string) to integer?

* A) ToString()
* B) ParseInt()
* C) int.Parse("30") ✅
* D) .Length
  **📘 الشرح:** `int.Parse()` يحول نص إلى عدد صحيح.

---

## 8. `var` Keyword

**Q12.** What is the type of `var number = 100;`?

* A) string
* B) bool
* C) int ✅
* D) float
  **📘 الشرح:** `var` يحدد النوع تلقائيًا من القيمة، وهنا 100 = int.

---

## 9. String Formatting

**Q13.** Best way to combine variables in strings?

* A) `+`
* B) string.Format
* C) string interpolation ✅
* D) ToString
  **📘 الشرح:** باستخدام `$"{name}"` تكون أكثر وضوحًا وأسهل.

---

## 10. StringBuilder

**Q14.** Why use `StringBuilder` instead of `+` in loops?

* A) Slower
* B) Harder
* C) Faster for many changes ✅
* D) It doesn’t work
  **📘 الشرح:** `StringBuilder` أكثر كفاءة عند تعديل النصوص بشكل متكرر.

---

## 11. Formatting Numbers

**Q15.** What does `{0:C}` format do?

* A) Shows percent
* B) Adds currency symbol ✅
* C) Rounds to nearest
* D) Adds zeros
  **📘 الشرح:** تعرض الرقم مع رمز العملة مثل `$` أو `ريال`.

---

## 12. Dates and Time

**Q16.** How to get current time in C#?

* A) Time.Now
* B) DateTime.Now ✅
* C) Date.Only
* D) TimeSpan
  **📘 الشرح:** `DateTime.Now` يعطيك الوقت والتاريخ الحالي.

---

## 13. Getting User Input

**Q17.** What method is used to read user input?

* A) Console.ReadKey()
* B) Console.Write()
* C) Console.ReadLine() ✅
* D) Console.Print()
  **📘 الشرح:** `ReadLine()` تقرأ النص الذي يُدخله المستخدم كسطر.

---

## 14. Mini Challenges

**Q18.** What does `birthday.DayOfWeek` return?

* A) Number of days
* B) Day name like Monday ✅
* C) Full date
* D) Month only
  **📘 الشرح:** تُعيد اسم اليوم حسب التاريخ، مثل "Saturday" أو "Friday".

---

## 15. Control Flow & Logic

---

### 🔹 **1. If Statements**

**Q1.** What will this code print if `age = 20`?

```csharp
if (age >= 18)
    Console.WriteLine("You are an adult.");
else
    Console.WriteLine("You are a minor.");
```

* A) You are a minor.
* B) You are an adult. ✅
* C) Error
* D) Nothing
  **📘 الشرح:** الشرط `age >= 18` صحيح، لذا سيتم طباعة "You are an adult."

---

### 🔹 **2. Logical Operators**

**Q2.** What does `&&` mean in a condition?

* A) OR
* B) NOT
* C) AND ✅
* D) EQUAL
  **📘 الشرح:** `&&` تعني "و"، أي يجب تحقق الشرطين معًا.

---

**Q3.** What will `!(age > 18)` return if `age = 20`?

* A) true
* B) false ✅
* C) 20
* D) Error
  **📘 الشرح:** `age > 18` = true → `!true` = false.

---

### 🔹 **3. Ternary Operator**

**Q4.** What is the output of:

```csharp
int score = 75;
string result = score >= 60 ? "Pass" : "Fail";
```

* A) Error
* B) Pass ✅
* C) Fail
* D) 60
  **📘 الشرح:** الشرط صحيح، لذا القيمة ستكون "Pass".

---

### 🔹 **4. Switch Statements**

**Q5.** What is printed when `light = "Red"`?

```csharp
switch (light)
{
    case "Green":
        Console.WriteLine("Go");
        break;
    case "Red":
        Console.WriteLine("Stop");
        break;
}
```

* A) Stop ✅
* B) Go
* C) Unknown
* D) Nothing
  **📘 الشرح:** "Red" تطابق الحالة، لذا يتم تنفيذ `Console.WriteLine("Stop");`.

---

### 🔹 **5. Nullable Types**

**Q6.** Which declaration is correct for a nullable integer?

* A) int? a = null; ✅
* B) int a = null;
* C) int a? = null;
* D) null int a;
  **📘 الشرح:** `int?` يسمح بتخزين `null` في المتغير.

---

### 🔹 **6. Null-Coalescing Operator**

**Q7.** What is the output of:

```csharp
string? name = null;
string finalName = name ?? "No Name";
```

* A) null
* B) No Name ✅
* C) Error
* D) name
  **📘 الشرح:** لأن `name` تساوي null، فسيتم استخدام `"No Name"`.

---

### 🔹 **7. Safe User Input**

**Q8.** What does `int.TryParse()` return?

* A) The number
* B) A string
* C) true/false ✅
* D) Error
  **📘 الشرح:** تستخدم `TryParse` للتحقق من صحة التحويل، وتعيد true أو false.

---

### 🔹 **8. Constants**

**Q9.** What happens if you try to change a `const` variable?

* A) It changes
* B) Gives warning
* C) Compile-time error ✅
* D) Runtime error
  **📘 الشرح:** `const` تعني أن القيمة ثابتة ولا يمكن تغييرها.

---

### 🔹 **9. String Functions**

**Q10.** What does `movie.Trim()` do?

* A) Cuts part of string
* B) Changes letters
* C) Removes spaces from start/end ✅
* D) Adds symbols
  **📘 الشرح:** `Trim()` تحذف الفراغات من بداية ونهاية النص فقط.

---

### 🔹 **10. Escape Sequences**

**Q11.** What is the output of:

```csharp
Console.WriteLine("Line1\nLine2");
```

* A) Line1 Line2
* B) Line1\nLine2
* C) Line1
  Line2 ✅
* D) Error
  **📘 الشرح:** `\n` تعني الانتقال لسطر جديد.

---

## 16. Arrays & Loops

---

### 🔹 **1. Loops**

**Q12.** How many times will this loop run?

```csharp
for (int i = 1; i <= 3; i++)
```

* A) 2
* B) 3 ✅
* C) 4
* D) Infinite
  **📘 الشرح:** `i` = 1, 2, 3 → أي 3 مرات.

---

**Q13.** Which loop runs at least once even if the condition is false?

* A) for
* B) while
* C) do-while ✅
* D) foreach
  **📘 الشرح:** `do-while` ينفذ مرة واحدة على الأقل قبل فحص الشرط.

---

### 🔹 **2. Math Functions**

**Q14.** What is the result of `Math.Sqrt(16)`?

* A) 8
* B) 4 ✅
* C) 2
* D) Error
  **📘 الشرح:** الجذر التربيعي لـ 16 هو 4.

---

### 🔹 **3. Arrays**

**Q15.** What is the output of:

```csharp
string[] cities = { "Cairo", "Paris", "London" };
Console.WriteLine(cities[0]);
```

* A) Paris
* B) Cairo ✅
* C) London
* D) Error
  **📘 الشرح:** العنصر الأول دائمًا يبدأ بالفهرس 0.

---

**Q16.** Which loop is best to go through all items in an array?

* A) for
* B) while
* C) foreach ✅
* D) do-while
  **📘 الشرح:** `foreach` تسهّل المرور على كل العناصر بدون كتابة فهارس.

---

### 🔹 **4. Array Logic**

**Q17.** What will this code count?

```csharp
if (g == 'm') male++;
```

* A) Female
* B) Male ✅
* C) Errors
* D) All characters
  **📘 الشرح:** يتم عد الذكور فقط إذا كانت القيمة `m`.

---

### 🔹 **5. Sorting**

**Q18.** What does `Array.Sort()` do?

* A) Filters array
* B) Sorts ascending ✅
* C) Sorts descending
* D) Duplicates items
  **📘 الشرح:** `Sort()` يرتب العناصر تصاعديًا (من الأصغر إلى الأكبر).

---

**Q19.** What does `Array.Reverse()` do?

* A) Duplicates
* B) Removes items
* C) Reverses order ✅
* D) Sorts ascending
  **📘 الشرح:** `Reverse()` يعكس ترتيب العناصر في المصفوفة.

---

## 17. 2D Arrays & Indexing

---

### 🔹 **1. 2D Arrays**

**Q20.** What is the value of `matrix[1,1]` in:

```csharp
int[,] matrix = {
  {1, 2, 3},
  {4, 5, 6}
};
```

* A) 2
* B) 4
* C) 5 ✅
* D) 6
  **📘 الشرح:** العنصر في الصف الثاني والعمود الثاني هو `5`.

---

### 🔹 **2. Index from End**

**Q21.** What does `letters[^1]` return?

* A) First letter
* B) Middle letter
* C) Last letter ✅
* D) Error
  **📘 الشرح:** الرمز `^1` يعني "آخر عنصر" في المصفوفة.

---




## 🧠 Mastering C# – Full Expert Roadmap (With Simple Explanation)

---

### 🟢 1. **Basics (Start Strong)**

* **Variables**
  Think of variables as boxes that store data (numbers, text, etc.).
  Example: `int age = 25;`

* **Data Types**
  Learn the differences between:

  * `int`, `float`, `double`, `decimal` (numbers)
  * `string`, `char` (text)
  * `bool` (true/false)

* **Type Conversion**
  Understand how to convert data safely.
  Example: `int.Parse("50")`, `(int)12.5`

* **Input & Output**
  Input: `Console.ReadLine()`
  Output: `Console.WriteLine()`

> ✅ This is where you build confidence with writing code.

---

### 🔵 2. **Conditions & Logic**

* **If / Else**
  Make decisions based on conditions.
  Example: `if (age >= 18) { }`

* **Comparison Operators**
  `==`, `!=`, `>`, `<`, `>=`, `<=`

* **Logical Operators**
  `&&` (AND), `||` (OR), `!` (NOT)

* **Ternary Operator**
  Short `if-else`: `var result = score >= 60 ? "Pass" : "Fail";`

* **Switch Statement & Expressions**
  Choose between many options efficiently.

> 🧠 This section trains your logic. Focus here.

---

### 🟣 3. **Loops (Repetition)**

* **for loop**
  Run a block multiple times.
  Example: `for (int i = 0; i < 5; i++)`

* **while / do-while**
  Run until a condition is false.
  Example: `while (x < 10)`

* **foreach**
  Loop through collections easily.

> 🔄 Loops help automate repetitive tasks. Practice them a lot.

---

### 🔶 4. **Strings & Text Handling**

* **String Functions**
  `.Trim()`, `.ToUpper()`, `.ToLower()`, `.Replace()`, `.Substring()`

* **String Interpolation**
  `Console.WriteLine($"Hello {name}")`

* **StringBuilder**
  For efficient string editing (especially in loops).

> 💬 Handling text cleanly is a real-world skill.

---

### 🟡 5. **Arrays & Collections**

* **Arrays**
  Fixed-size lists: `int[] nums = {1, 2, 3};`

* **Loops with arrays**
  Loop and access items with `[]`.

* **Multidimensional Arrays (2D)**
  Like a grid: `int[,] matrix = new int[2,3];`

* **List<T> (Dynamic Arrays)**
  `List<string> names = new List<string>();`

* **Dictionaries**
  Key-Value pairs: `Dictionary<string, int> scores`

> 📦 Collections are everywhere. Master how to store and access data.

---

### 🔴 6. **Methods (Functions)**

* **Why?**
  Reuse code, organize your program.

* **Syntax**

  ```csharp
  void SayHi(string name) {
      Console.WriteLine("Hi " + name);
  }
  ```

* **Return Values**
  `int Add(int a, int b) => a + b;`

* **Parameters (with default, optional)**
  `void Greet(string name = "Guest")`

> 🧩 Functions are building blocks of every program.

---

### 🟢 7. **Object-Oriented Programming (OOP)**

The real **power of C#** lies in OOP.

* **Class**
  A blueprint for creating objects.

  ```csharp
  class Car {
      public string Model;
      public void Drive() { ... }
  }
  ```

* **Object**
  An instance of a class: `Car myCar = new Car();`

* **Encapsulation**
  Hide data using `private`, and control access using `get` / `set`.

* **Inheritance**
  A class can extend another: `class Dog : Animal`

* **Polymorphism**
  Same method behaves differently across classes (`virtual`, `override`)

* **Abstraction**
  Focus on what an object does, not how.

> 🧠 OOP = Think like an architect. Design clean, reusable code.

---

### 🔵 8. **Exception Handling (Try / Catch)**

* **Why?**
  Handle errors without crashing the program.

* **Syntax**

  ```csharp
  try {
      int x = int.Parse("abc");
  } catch (Exception ex) {
      Console.WriteLine("Error: " + ex.Message);
  }
  ```

> 🛡️ A pro always handles the unexpected.

---

### 🟣 9. **Files & Data**

* **Read/Write Text Files**
  `File.ReadAllText()`, `File.WriteAllText()`

* **Working with JSON**
  Use `Newtonsoft.Json` or `System.Text.Json`

* **Databases**
  Use `ADO.NET` or `Entity Framework`

> 💾 Knowing how to work with data makes you industry-ready.

---

### 🟠 10. **LINQ (Language Integrated Query)**

Query collections like SQL:

```csharp
var evenNumbers = numbers.Where(n => n % 2 == 0).ToList();
```

* Filter, sort, group, select
* Works with arrays, lists, and databases

> 🔍 LINQ is powerful. Learn it early.

---

### 🔵 11. **Advanced Topics**

* **Async / Await**
  For non-blocking code (used in I/O, web apps)

* **Events and Delegates**
  Custom behavior for actions, e.g. button clicks

* **Generics**
  Reusable code across types: `List<T>`, `Func<T>`

* **Interfaces**
  Contract-like structures: `interface IDriveable { void Drive(); }`

* **Dependency Injection**
  Loose coupling of components, used in ASP.NET Core

* **Reflection**
  Look into types and properties at runtime

* **Design Patterns**
  Singleton, Factory, Observer, etc.

> 🧠 These are expert-level tools. Learn one at a time, slowly.

---

### 🧑‍💻 12. **Project Building (Very Important)**

Don’t just study. **Build**. Ideas:

* A calculator app
* To-do list
* Note-taking app with file save/load
* Budget tracker
* API client (get data from websites)
* Web app with ASP.NET Core
* Game using Unity (C# is used!)

> 🛠️ Real coding builds real experience.

---

### 📚 Extra Tips to Master C\#

1. **Practice daily** – 20 minutes is better than 0.
2. **Use Visual Studio or VS Code** – Learn the tools.
3. **Read code from others** – GitHub is gold.
4. **Debug like a pro** – Step through code.
5. **Teach someone else** – Explaining means you’ve learned.

---

### ✅ Summary Map to Become Expert

| Level           | Topics                                                   |
| --------------- | -------------------------------------------------------- |
| 🟢 Beginner     | Variables, Data Types, Loops, If/Else, Input/Output      |
| 🔵 Intermediate | Arrays, Methods, OOP, String Manipulation                |
| 🟣 Advanced     | LINQ, Exceptions, Files, Interfaces, Generics            |
| 🔴 Expert       | Async, Reflection, Dependency Injection, Design Patterns |

---

## 🧠 C# Expert MCQs – With Arabic Explanation

---

### 🔹 **1. What is the default data type for decimal numbers in C#?**

A) `float`
B) `decimal`
C) `double` ✅
D) `int`

**✅ الإجابة: C) double**
**الشرح:**
النوع الافتراضي للأرقام العشرية في C# هو `double`، إلا إذا قمت بإضافة `M` أو `F` لاستخدام `decimal` أو `float`.

---

### 🔹 **2. What does `Console.ReadLine()` return?**

A) int
B) string ✅
C) bool
D) void

**✅ الإجابة: B) string**
**الشرح:**
دالة `ReadLine()` دائمًا تعيد قيمة من نوع `string` حتى لو أدخل المستخدم رقمًا، لذا تحتاج لتحويلها إذا كنت تريد رقم.

---

### 🔹 **3. Which loop guarantees at least one execution even if the condition is false?**

A) `for`
B) `while`
C) `do-while` ✅
D) `foreach`

**✅ الإجابة: C) do-while**
**الشرح:**
في `do-while` يتم تنفيذ الكود أولًا ثم يتم التحقق من الشرط، لذا سيعمل مرة واحدة على الأقل.

---

### 🔹 **4. What is the purpose of `string interpolation` in C#?**

A) To split strings
B) To convert numbers to strings
C) To insert variables into strings ✅
D) To loop through strings

**✅ الإجابة: C) To insert variables into strings**
**الشرح:**
`$"Hello {name}"` تسمى String Interpolation وهي أسهل طريقة لإدخال قيم المتغيرات داخل النصوص.

---

### 🔹 **5. What does the `List<T>` class offer over arrays?**

A) It's fixed in size
B) It's slower than arrays
C) It's dynamic and resizable ✅
D) It only stores strings

**✅ الإجابة: C) It's dynamic and resizable**
**الشرح:**
`List<T>` يمكن تغيير حجمها أثناء التشغيل على عكس المصفوفات التي يجب أن تعرف حجمها مسبقًا.

---

### 🔹 **6. What does `int.TryParse("abc", out int x)` return?**

A) true
B) false ✅
C) 0
D) Error

**✅ الإجابة: B) false**
**الشرح:**
`abc` لا يمكن تحويلها إلى رقم، لذا `TryParse` تُرجع `false` وتمنع حدوث استثناء (Exception).

---

### 🔹 **7. What is a benefit of using `StringBuilder`?**

A) It makes strings shorter
B) It can format numbers
C) It is faster for repeated string changes ✅
D) It replaces variables

**✅ الإجابة: C) It is faster for repeated string changes**
**الشرح:**
`StringBuilder` مصمم لتعديل النصوص داخل الحلقات بدون استهلاك ذاكرة زائدة كما يفعل `string`.

---

### 🔹 **8. What is the role of an `interface` in C#?**

A) Store values
B) Implement UI
C) Define contracts for classes ✅
D) Save files

**✅ الإجابة: C) Define contracts for classes**
**الشرح:**
`interface` تحدد مجموعة من الدوال التي يجب أن تنفذها الكلاسات، بدون تنفيذ حقيقي داخلها.

---

### 🔹 **9. What is the use of `async` and `await`?**

A) Sorting arrays
B) File writing
C) Non-blocking code execution ✅
D) Drawing UI

**✅ الإجابة: C) Non-blocking code execution**
**الشرح:**
`async` و `await` يسمحان بتنفيذ العمليات الثقيلة (مثل القراءة من الإنترنت) بدون تجميد البرنامج.

---

### 🔹 **10. What will this LINQ query return?**

```csharp
var result = numbers.Where(n => n > 5);
```

A) All numbers
B) Numbers less than 5
C) Numbers greater than 5 ✅
D) Even numbers

**✅ الإجابة: C) Numbers greater than 5**
**الشرح:**
`Where(n => n > 5)` تعني اختيار الأرقام التي أكبر من 5 فقط.

---

### 🔹 **11. What does `Dependency Injection` help with?**

A) Making databases
B) Avoiding object creation
C) Reducing dependency between classes ✅
D) Injecting viruses 😅

**✅ الإجابة: C) Reducing dependency between classes**
**الشرح:**
Dependency Injection يساعد في جعل الكلاسات مستقلة عن بعضها، وهذا يسهل اختبار وصيانة الكود.

---

### 🔹 **12. Which design pattern ensures only one instance of a class?**

A) Factory
B) Singleton ✅
C) Observer
D) Strategy

**✅ الإجابة: B) Singleton**
**الشرح:**
نمط Singleton يضمن وجود نسخة واحدة فقط من الكلاس طوال فترة عمل البرنامج.

---

### 🔹 **13. What does `File.ReadAllText("file.txt")` do?**

A) Writes to the file
B) Deletes the file
C) Reads all text from the file ✅
D) Creates the file

**✅ الإجابة: C) Reads all text from the file**
**الشرح:**
تقوم هذه الدالة بقراءة محتوى الملف النصي بالكامل وتعيده كنص.

---

### 🔹 **14. What does `Math.Pow(2, 3)` return?**

A) 6
B) 9
C) 8 ✅
D) 5

**✅ الإجابة: C) 8**
**الشرح:**
`2` أس `3` = `2 * 2 * 2 = 8`

---

### 🔹 **15. Why do we use `virtual` and `override` keywords?**

A) For sorting
B) For math functions
C) For customizing inherited methods ✅
D) For creating loops

**✅ الإجابة: C) For customizing inherited methods**
**الشرح:**
`virtual` تسمح بإعادة تعريف الدالة في الكلاس الأب، و`override` تُستخدم في الكلاس الابن لتطبيق سلوك جديد.

---

أكيد! إليك المزيد من أسئلة الاختيار من متعدد (MCQs) مع شرح باللغة العربية:

---

### 🔹 **16. What happens when you use `int i = (int)3.9;` ?**

A) `i` becomes 4
B) `i` becomes 3 ✅
C) Error occurs
D) `i` becomes 0

**✅ الإجابة: B) i becomes 3**
**الشرح:**
عند تحويل `double` إلى `int` باستخدام التحويل الصريح (casting)، يتم حذف الجزء العشري بدون تقريب.

---

### 🔹 **17. Which of these is the correct way to declare a nullable integer?**

A) `int a = null;`
B) `int? a = null;` ✅
C) `Nullable a = 0;`
D) `int a;`

**✅ الإجابة: B) int? a = null;**
**الشرح:**
العلامة `?` تسمح للمتغيرات بأن تأخذ قيمة `null`، وهي طريقة مختصرة لتعريف `Nullable<T>`.

---

### 🔹 **18. What does `??` operator do?**

A) Checks equality
B) Assigns default if null ✅
C) Logical AND
D) Converts types

**✅ الإجابة: B) Assigns default if null**
**الشرح:**
`a ?? b` تعني "إذا كانت a ليست null استخدمها، وإلا استخدم b".

---

### 🔹 **19. How to declare a constant in C#?**

A) `var Pi = 3.14;`
B) `const double Pi = 3.14;` ✅
C) `double Pi = 3.14;`
D) `readonly Pi = 3.14;`

**✅ الإجابة: B) const double Pi = 3.14;**
**الشرح:**
`const` تعني أن القيمة ثابتة ولا يمكن تغييرها أثناء تشغيل البرنامج.

---

### 🔹 **20. Which method removes all leading and trailing spaces from a string?**

A) `Trim()` ✅
B) `Replace()`
C) `ToUpper()`
D) `Substring()`

\*\*✅ الإجابة: A) Trim()`**   **الشرح:**  
`Trim()\` تزيل المسافات الفارغة من بداية ونهاية النص.

---

### 🔹 **21. What does `foreach` loop do?**

A) Loop based on a condition
B) Loop through each item in a collection ✅
C) Loop fixed number of times
D) Loop backwards

**✅ الإجابة: B) Loop through each item in a collection**
**الشرح:**
`foreach` تسهل المرور على جميع العناصر في مجموعة أو مصفوفة.

---

### 🔹 **22. Which operator is used for logical AND in C#?**

A) `||`
B) `&&` ✅
C) `!`
D) `==`

**✅ الإجابة: B) &&**
**الشرح:**
`&&` يعني “و” منطقي، كلا الشرطين يجب أن يكونا صحيحين.

---

### 🔹 **23. How to safely convert a string to int without crashing if invalid?**

A) `int.Parse()`
B) `Convert.ToInt32()`
C) `int.TryParse()` ✅
D) `ToString()`

\*\*✅ الإجابة: C) int.TryParse()`**   **الشرح:**  
`TryParse`تعيد`false\` بدلاً من حدوث خطأ إذا لم يكن النص رقمًا صحيحًا.

---

### 🔹 **24. What does this code print?**

```csharp
int i = 5;
Console.WriteLine(i++);
```

A) 6
B) 5 ✅
C) 0
D) Error

**✅ الإجابة: B) 5**
**الشرح:**
`i++` هو postfix increment، يطبع القيمة أولًا ثم يزيدها.

---

### 🔹 **25. How to declare a variable with automatic type detection?**

A) `var number = 10;` ✅
B) `int number = "10";`
C) `auto number = 10;`
D) `string number = 10;`

**✅ الإجابة: A) var number = 10;**
**الشرح:**
`var` يخبر المترجم بتحديد نوع المتغير تلقائيًا بناءً على القيمة.

---

### 🔹 **26. What does `switch` statement do?**

A) Loops through numbers
B) Selects code to run based on a value ✅
C) Reads user input
D) Converts data types

**✅ الإجابة: B) Selects code to run based on a value**
**الشرح:**
`switch` يسمح بتنفيذ أكواد مختلفة حسب قيمة متغير معين.

---

### 🔹 **27. What is the correct syntax for a `for` loop?**

A) `for (int i = 0; i < 5; i++) { ... }` ✅
B) `for i = 0 to 5 { ... }`
C) `loop for (int i; i < 5;) { ... }`
D) `foreach (int i = 0; i < 5; i++) { ... }`

**✅ الإجابة: A) for (int i = 0; i < 5; i++) { ... }**
**الشرح:**
`for` loop تحتوي على 3 أجزاء: البداية، الشرط، والتحديث.

---

### 🔹 **28. How do you declare a two-dimensional array?**

A) `int[] arr = new int[2,3];` ✅
B) `int[,] arr = new int[2,3];`
C) `int[][] arr = new int[2][3];`
D) `int arr[2,3];`

**✅ الإجابة: B) int\[,] arr = new int\[2,3];**
**الشرح:**
`[,]` يرمز لمصفوفة ثنائية الأبعاد في C#.

---

### 🔹 **29. What is the output of this code?**

```csharp
string name = "Ali";
Console.WriteLine($"{name} scored {90} points");
```

A) Ali scored 90 points ✅
B) {name} scored {90} points
C) Name scored 90 points
D) Error

**✅ الإجابة: A) Ali scored 90 points**
**الشرح:**
هذا مثال على String Interpolation حيث يتم إدخال قيم المتغيرات داخل النص.

---

### 🔹 **30. Which of the following correctly converts a string `"100"` to an integer?**

A) `int.Parse("100")` ✅
B) `"100".ToInt()`
C) `Convert.ToString(100)`
D) `int.ToString("100")`

**✅ الإجابة: A) int.Parse("100")**
**الشرح:**
`int.Parse` يحول النص إلى عدد صحيح.

---

### 🔹 **31. What is the result of this expression?**

```csharp
bool result = !(true && false);
```

A) true ✅
B) false
C) null
D) error

**✅ الإجابة: A) true**
**الشرح:**
`true && false` يساوي false، وعند نفيه `!false` يصبح true.

---

### 🔹 **32. How do you create a new instance of a class called `Person`?**

A) `Person p = new Person();` ✅
B) `new Person p();`
C) `Person p();`
D) `Person = new p();`

\*\*✅ الإجابة: A) Person p = new Person();`**   **الشرح:**  
هذا هو الشكل الصحيح لإنشاء كائن جديد من نوع `Person\`.

---

### 🔹 **33. What keyword is used to inherit a class?**

A) `implements`
B) `inherits`
C) `extends`
D) `:` ✅

**✅ الإجابة: D) :**
**الشرح:**
في C# نستخدم النقطتين `:` لوراثة كلاس.

---

### 🔹 **34. What does `override` keyword do?**

A) Creates a new method
B) Hides a method
C) Changes the behavior of an inherited method ✅
D) Deletes a method

**✅ الإجابة: C) Changes the behavior of an inherited method**
**الشرح:**
`override` يسمح بإعادة تعريف طريقة موجودة في الكلاس الأب.

---

### 🔹 **35. Which keyword is used to declare a method that can be overridden?**

A) `virtual` ✅
B) `abstract`
C) `override`
D) `static`

**✅ الإجابة: A) virtual**
**الشرح:**
`virtual` تعني أن هذه الدالة يمكن للكلاسات الابنة أن تغيرها.

---

### 🔹 **36. What does `abstract` mean in a class?**

A) The class cannot be instantiated ✅
B) The class has no methods
C) The class is static
D) The class is a struct

**✅ الإجابة: A) The class cannot be instantiated**
**الشرح:**
`abstract` تعني أن هذه الكلاس مجردة ولا يمكن إنشاء كائن مباشر منها.

---

### 🔹 **37. What is `LINQ` used for?**

A) File input/output
B) Query data collections easily ✅
C) Math calculations
D) Graphic design

**✅ الإجابة: B) Query data collections easily**
**الشرح:**
LINQ هو لغة مدمجة للبحث والتعامل مع البيانات في المجموعات.

---

### 🔹 **38. What is the purpose of `using` statement?**

A) Define namespaces
B) Automatically dispose resources ✅
C) Loop through arrays
D) Declare variables

**✅ الإجابة: B) Automatically dispose resources**
**الشرح:**
`using` يضمن تحرير الموارد (مثل الملفات) بشكل آمن بعد استخدامها.

---

### 🔹 **39. Which type is best for storing money?**

A) `float`
B) `double`
C) `decimal` ✅
D) `int`

**✅ الإجابة: C) decimal**
**الشرح:**
`decimal` مصمم للتعامل مع القيم المالية بدقة عالية.

---

### 🔹 **40. What does `async` method return?**

A) void
B) Task or Task<T> ✅
C) int
D) string

**✅ الإجابة: B) Task or Task<T>**
**الشرح:**
الأساليب غير المتزامنة (async) عادة تعيد `Task` أو `Task<T>` لتدعم التشغيل الغير متزامن.

---

### 🔹 **41. What is the difference between `Console.Write()` and `Console.WriteLine()`?**

A) Both print and move to next line
B) `Write()` prints and stays on the same line; `WriteLine()` moves to next line ✅
C) `WriteLine()` does not print anything
D) No difference

**✅ الإجابة: B)**
**الشرح:**
`Console.Write()` يطبع النص ويبقى في نفس السطر، بينما `Console.WriteLine()` يطبع وينتقل للسطر التالي.

---

### 🔹 **42. What does `StringBuilder` help with?**

A) Creating immutable strings
B) Efficiently modifying strings without creating new ones ✅
C) Converting numbers to strings
D) Parsing strings

**✅ الإجابة: B)**
**الشرح:**
`StringBuilder` يُستخدم لتحسين الأداء عند تعديل النصوص بشكل متكرر لأنه لا ينشئ نسخة جديدة لكل تعديل.

---

### 🔹 **43. Which data type should you use for a character?**

A) `string`
B) `char` ✅
C) `int`
D) `bool`

**✅ الإجابة: B)**
**الشرح:**
`char` يُستخدم لتخزين حرف واحد فقط.

---

### 🔹 **44. What will `Console.WriteLine(90.ToString("C"));` print?**

A) 90.00
B) \$90.00 (or local currency format) ✅
C) 90C
D) Error

**✅ الإجابة: B)**
**الشرح:**
`"C"` هو تنسيق العملة الذي يعرض الرقم بصيغة العملة المحلية.

---

### 🔹 **45. How do you add 5 years to a DateTime object `birthday`?**

A) `birthday + 5`
B) `birthday.AddYears(5)` ✅
C) `birthday.AddDays(5)`
D) `birthday.Add(5)`

**✅ الإجابة: B)**
**الشرح:**
`AddYears` تضيف عدد السنوات المطلوب إلى التاريخ.

---

### 🔹 **46. How to safely read an integer from user input?**

A) `int.Parse(Console.ReadLine())`
B) `Convert.ToInt32(Console.ReadLine())`
C) `int.TryParse(Console.ReadLine(), out int num)` ✅
D) `Console.ReadLine()`

**✅ الإجابة: C)**
**الشرح:**
`TryParse` تتحقق إذا كان الإدخال صالحًا كرقم قبل التحويل.

---

### 🔹 **47. What is `var` keyword used for?**

A) Declaring constants
B) Declaring variables with automatic type detection ✅
C) Declaring arrays
D) Declaring nullable types

**✅ الإجابة: B)**
**الشرح:**
`var` يخلي المترجم يحدد نوع المتغير حسب القيمة المخصصة له.

---

### 🔹 **48. What does the postfix increment operator `i++` do?**

A) Increments `i` then returns value
B) Returns value then increments `i` ✅
C) Decrements `i`
D) Does nothing

**✅ الإجابة: B)**
**الشرح:**
`i++` يعيد القيمة أولاً، ثم يزيدها.

---

### 🔹 **49. Which keyword allows a variable to hold a null value?**

A) `nullable`
B) `?` after type name ✅
C) `null`
D) `void`

**✅ الإجابة: B)**
**الشرح:**
إضافة `?` بعد نوع البيانات تجعل المتغير يقبل القيمة null.

---

### 🔹 **50. How do you write a comment in C#?**

A) `<!-- Comment -->`
B) `// Comment` ✅
C) `/* Comment */`
D) Both B and C ✅

**✅ الإجابة: D)**
**الشرح:**
`//` للتعليقات السطرية، و`/* ... */` للتعليقات متعددة الأسطر.

---

### 🔹 **51. What will this code print?**

```csharp
int a = 10;
double b = a;
Console.WriteLine(b);
```

A) 10
B) 10.0 ✅
C) Error
D) Null

**✅ الإجابة: B) 10.0**
**الشرح:**
هذا مثال على التحويل الضمني (implicit conversion) من `int` إلى `double` حيث يتم تحويل العدد الصحيح إلى عدد عشري بدون فقدان البيانات.

---

### 🔹 **52. What happens when you cast a double to int like this?**

```csharp
double d = 12.9;
int i = (int)d;
Console.WriteLine(i);
```

A) 12 ✅
B) 13
C) 12.9
D) Error

**✅ الإجابة: A) 12**
**الشرح:**
التحويل الصريح (explicit cast) من `double` إلى `int` يزيل الجزء العشري ويأخذ الجزء الصحيح فقط.

---

### 🔹 **53. What is the output of:**

```csharp
int[] numbers = {1, 2, 3};
Console.WriteLine(numbers.Length);
```

A) 2
B) 3 ✅
C) 1
D) Error

**✅ الإجابة: B) 3**
**الشرح:**
`Length` تعطي عدد عناصر المصفوفة.

---

### 🔹 **54. How do you loop through an array using `foreach`?**

A) `for each (int n in numbers) { ... }`
B) `foreach (int n in numbers) { ... }` ✅
C) `loop (int n in numbers) { ... }`
D) `foreach int n; numbers { ... }`

**✅ الإجابة: B)**
**الشرح:**
الصيغة الصحيحة هي `foreach (type var in collection) { ... }`.

---

### 🔹 **55. What is the difference between `int` and `int?`?**

A) `int?` can be null, `int` cannot ✅
B) `int` can be null, `int?` cannot
C) No difference
D) `int` is a class, `int?` is a struct

**✅ الإجابة: A)**
**الشرح:**
`int?` نوع Nullable يسمح له باحتواء قيمة `null`، بينما `int` لا يقبل `null`.

---

### 🔹 **56. What is the output of this code?**

```csharp
int x = 5;
Console.WriteLine(++x);
```

A) 5
B) 6 ✅
C) Error
D) Null

**✅ الإجابة: B) 6**
**الشرح:**
`++x` هو الـ prefix increment، يزيد القيمة قبل الطباعة.

---

### 🔹 **57. Which of these is the correct way to declare a constant?**

A) `const int days = 7;` ✅
B) `int const days = 7;`
C) `constant int days = 7;`
D) `static const int days = 7;`

**✅ الإجابة: A)**
**الشرح:**
`const` تسبق نوع المتغير وتجعله ثابتاً لا يمكن تغييره.

---

### 🔹 **58. What is the purpose of the null-coalescing operator `??`?**

A) Throws exception if null
B) Returns left value if not null, otherwise right value ✅
C) Checks if value is null
D) Converts null to empty string

**✅ الإجابة: B)**
**الشرح:**
`??` تعطي القيمة الموجودة على اليسار إذا كانت غير null، أو القيمة على اليمين إذا كانت null.

---

### 🔹 **59. How do you declare a method that returns nothing?**

A) `void MethodName() { ... }` ✅
B) `int MethodName() { ... }`
C) `null MethodName() { ... }`
D) `void() MethodName { ... }`

**✅ الإجابة: A)**
**الشرح:**
`void` يعني أن الدالة لا تعيد أي قيمة.

---

### 🔹 **60. Which of these is a correct way to concatenate strings?**

A) `"Hello" + " World"` ✅
B) `"Hello".Add(" World")`
C) `"Hello".Append(" World")`
D) `"Hello".Concat(" World")`

**✅ الإجابة: A)**
**الشرح:**
استخدام `+` هو الطريقة البسيطة لدمج النصوص في C#.

---



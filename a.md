
## ✅ C# Beginner Guide – Multiple Choice Questions (Simple English + Arabic)

```md
# 🎓 C# Beginner Guide – MCQ Questions with Answers & Arabic Explanation

---

```md
### 1. What Are Variables?

**Q1.** What is the correct data type to store a whole number in C#?
- A) string  
- B) int  
- C) float  
- D) char  
**Answer:** B) int  
**شرح:**  
النوع `int` يستخدم لتخزين الأرقام الصحيحة مثل 25، بدون فواصل عشرية.

...

### 1. What Are Variables?

**Q1.** What is the correct data type to store a whole number in C#?  
- A) string  
- B) int  
- C) float  
- D) char  
**Answer:** B) int  
**شرح:**  
النوع `int` يُستخدم لتخزين الأرقام الكاملة بدون فواصل عشرية.

**Q2.** Which data type is best for money values?  
- A) float  
- B) string  
- C) decimal  
- D) int  
**Answer:** C) decimal  
**شرح:**  
`decimal` دقيق جداً ومناسب للتعامل مع القيم المالية.

**Q3.** What data type would you use for yes/no answers?  
- A) int  
- B) bool  
- C) char  
- D) double  
**Answer:** B) bool  
**شرح:**  
النوع `bool` يُخزن القيمتين فقط: true أو false، وهو ممتاز للقرارات.

---

### 2. Declaring and Using Variables

**Q4.** What is the correct way to declare a string variable in C#?  
- A) string name = Ali;  
- B) string name = "Ali";  
- C) name = string "Ali";  
- D) string = "Ali";  
**Answer:** B) string name = "Ali";  
**شرح:**  
يجب وضع النص داخل علامات تنصيص `" "` عند تخزينه في متغير من نوع `string`.

---

### 3. Writing Output

**Q5.** What does `Console.WriteLine()` do?  
- A) It reads input  
- B) It writes and stays on the same line  
- C) It writes and moves to the next line  
- D) It closes the program  
**Answer:** C) It writes and moves to the next line  
**شرح:**  
`Console.WriteLine()` تُستخدم لطباعة النص ثم النزول لسطر جديد.

---

### 4. Math Operations

**Q6.** What is the result of `10 + 3` in C#?  
- A) 13  
- B) 7  
- C) 30  
- D) 3.33  
**Answer:** A) 13  
**شرح:**  
العملية `+` تقوم بجمع الرقمين.

**Q7.** How can we get decimal result from dividing int values in C#?  
- A) Use `int`  
- B) Use `bool`  
- C) Convert one to `double`  
- D) Multiply first  
**Answer:** C) Convert one to `double`  
**شرح:**  
يجب تحويل أحد الأرقام إلى `double` للحصول على ناتج عشري.

---

### 5. Prefix vs Postfix Increment

**Q8.** What does `i++` do in C#?  
- A) Increases before using  
- B) Decreases the value  
- C) Increases after using  
- D) Keeps it the same  
**Answer:** C) Increases after using  
**شرح:**  
`i++` تطبع أولاً ثم تزيد القيمة بعد الطباعة.

---

### 6. Type Conversion

**Q9.** What is implicit conversion in C#?  
- A) Manually casting big to small  
- B) Automatic conversion from small to big  
- C) Not allowed in C#  
- D) Used only in loops  
**Answer:** B) Automatic conversion from small to big  
**شرح:**  
التحويل الضمني يتم تلقائياً من نوع صغير إلى نوع أكبر دون فقد البيانات.

---

### 7. Converting Strings and Numbers

**Q10.** What method converts string "30" to integer?  
- A) ToString()  
- B) int.Parse()  
- C) Convert.ToChar()  
- D) GetType()  
**Answer:** B) int.Parse()  
**شرح:**  
`int.Parse()` تحول النص إلى عدد صحيح.

---

### 8. var Keyword

**Q11.** What is the type of `var number = 100;`?  
- A) string  
- B) bool  
- C) int  
- D) float  
**Answer:** C) int  
**شرح:**  
`var` يحدد النوع تلقائياً بناءً على القيمة، وهنا 100 هي `int`.

---

### 9. String Formatting

**Q12.** Which is better for combining variables in strings?  
- A) `+`  
- B) string.Format  
- C) string interpolation  
- D) ToString  
**Answer:** C) string interpolation  
**شرح:**  
الطريقة `${}` أكثر سهولة ووضوحاً في التعامل مع المتغيرات داخل النصوص.

---

### 10. StringBuilder

**Q13.** Why use `StringBuilder` instead of `+`?  
- A) Slower  
- B) Harder  
- C) Faster for many changes  
- D) It doesn’t work  
**Answer:** C) Faster for many changes  
**شرح:**  
`StringBuilder` سريع جداً عند تعديل النصوص عدة مرات.

---

### 11. Formatting Numbers

**Q14.** What does `{0:C}` format do?  
- A) Shows percent  
- B) Adds currency symbol  
- C) Rounds to nearest  
- D) Adds zeros  
**Answer:** B) Adds currency symbol  
**شرح:**  
`C` تستخدم لعرض الرقم مع رمز العملة المحلية مثل `$`.

---

### 12. Dates and Time

**Q15.** How to get current time in C#?  
- A) Time.Now  
- B) DateTime.Now  
- C) Date.Only  
- D) TimeSpan  
**Answer:** B) DateTime.Now  
**شرح:**  
`DateTime.Now` يُستخدم للحصول على الوقت والتاريخ الحالي.

---

### 13. Getting User Input

**Q16.** What method is used to read user input?  
- A) Console.ReadKey()  
- B) Console.Write()  
- C) Console.ReadLine()  
- D) Console.Print()  
**Answer:** C) Console.ReadLine()  
**شرح:**  
`ReadLine()` تُستخدم لقراءة السطر المدخل من المستخدم كـ `string`.

---

### 14. Mini Challenges

**Q17.** What does `birthday.DayOfWeek` return?  
- A) Number of days  
- B) Day name like Monday  
- C) Full date  
- D) Month only  
**Answer:** B) Day name like Monday  
**شرح:**  
`DayOfWeek` يُرجع اسم اليوم مثل "Saturday" أو "Monday".

---
```

---

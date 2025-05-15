# 📘 Day 2: JavaScript Coding Assignments – Variables, Data Types & Type Coercion

Welcome to **Day 2** of your MERN Stack Journey!  
Today is all about deep hands-on coding practice based on what you learned in **Day 1** — Variables, Data Types, Type Conversion, Template Literals, and more.

---

## 🟢 Easy (Foundations) — 25 Questions

1. **Create a string variable called `username`.**  
   Assign your name as a string. Print the value and use `typeof` to check its data type.

2. **Create a number variable called `age`.**  
   Assign your current age to it. Use `typeof` to confirm it's a number.

3. **Use `const` to declare your `birthYear`.**  
   Then, try changing its value. What error do you get? Why is it not allowed?

4. **Declare one variable using each: `var`, `let`, and `const`.**  
   Modify their values if possible. Which ones let you reassign values?

5. **Create a string called `country` and use `typeof` on it.**  
   Confirm the type and explain what `typeof` is doing.

6. **Create a number variable for your `favoriteNumber`.**  
   Use `typeof` to check the type and describe why it shows “number”.

7. **Create a boolean variable `isStudent` and assign `true` or `false`.**  
   Check its type using `typeof`.

8. **Declare a variable `middleName` but don’t assign any value.**  
   Log the value and type. Why does JavaScript say it's `undefined`?

9. **Assign `null` to a variable called `result`.**  
   What type does `typeof` show? Why is it `"object"`?

10. **Create `firstName` and `lastName` variables and combine them.**  
    Use the `+` operator to build `fullName`.

11. **Use a template literal to create a sentence:**  
    For example: `My name is [your name] and I am [your age] years old.`

12. **Create a variable `heightInMeters` and assign a decimal value like `1.75`.**  
    What type does `typeof` show?

13. **Assign your favorite emoji to a variable `emoji`.**  
    What does `typeof` return?

14. **Evaluate this expression:**  
    ```js
    let x = "10" + 5;
    ```  
    What is the value of `x`? Why does it result in a string?

15. **Evaluate this expression:**  
    ```js
    let y = 5 + "10";
    ```  
    What’s the output and why? Explain left-to-right coercion.

16. **Convert the string `"123"` into a number.**  
    Use `Number("123")`. What is the result and type?

17. **Convert the number `456` into a string.**  
    Use `String(456)`. What does `typeof` return?

18. **Evaluate Boolean values:**  
    Try `Boolean(0)`, `Boolean(1)`, and `Boolean("")`. What do each return and why?

19. **Check the type of `Infinity` and `NaN`.**  
    Are they both numbers? Why?

20. **Create a large integer using the BigInt notation:**  
    ```js
    let big = 1234567890123456789012345678901234567890n;
    ```  
    What data type is this?

21. **Create a unique value using Symbol:**  
    ```js
    let id = Symbol("id");
    ```  
    What type is this and what’s special about it?

22. **Declare a `price` variable with a decimal like `9.99`.**  
    What data type is it?

23. **Try using different naming styles:**  
    Create variables with `camelCase`, `snake_case`, and `kebab-case`. Which ones work?

24. **Evaluate this expression:**  
    ```js
    let result = "3" * 2;
    ```  
    What is the output and why does this result in a number?

25. **Compare using `==`:**  
    ```js
    let a = "5";
    let b = 5;
    console.log(a == b);
    ```  
    Why is the output `true` even though one is a string?

---

## 🟡 Medium (Exploration) — 20 Questions

26. **Try reassigning a `const` variable.**  
    What happens? What is the exact error message and why does it occur?

27. **Extract a number from a string using `parseInt()`:**  
    ```js
    let value = "42px";
    let number = parseInt(value);
    ```  
    What does `number` contain?

28. **Compare `undefined` and `null`:**  
    ```js
    let x = undefined;
    let y = null;
    ```  
    What’s the result of `x == y` and `x === y`?

29. **Check types of `null` and `{}`:**  
    ```js
    console.log(typeof null === typeof {});
    ```  
    What is the output? Why might this be surprising?

30. **Declare the same `let` variable twice in one block.**  
    What error appears?

31. **Test variable scope:**  
    Use `var` and `let` inside a `{}` block. Can you access them outside?

32. **Evaluate this nested `typeof`:**  
    ```js
    typeof typeof 1;
    ```  
    What is the result and why?

33. **Try this expression:**  
    ```js
    let z = 1 + "2" + 3;
    ```  
    What is `z` and why? Explain step-by-step how JavaScript evaluates it.

34. **Multiply a string by a number:**  
    ```js
    let a = "10";
    let b = 2;
    let c = a * b;
    ```  
    What is `c` and why is it not NaN?

35. **Add a boolean to a number:**  
    ```js
    let result = true + 1;
    ```  
    What is the result? How is `true` coerced?

36. **Create a dynamic sentence with variables:**  
    Use template literals to write a sentence using `name` and `age`.

37. **Add a BigInt to a number:**  
    ```js
    let big = 100n;
    let normal = 10;
    big + normal; // What happens?
    ```  
    What error occurs and how can you fix it?

38. **Assign `NaN` and use it in math:**  
    ```js
    let notANumber = NaN;
    console.log(notANumber + 5);
    ```  
    What is the result?

39. **Use `isNaN()` on different strings:**  
    ```js
    isNaN("hello");
    isNaN("123");
    ```  
    Why do they return different results?

40. **Create different variables and log their types:**  
    One string, one number, one boolean — confirm their types with `typeof`.

41. **Try to swap two constants:**  
    Why does it fail? What’s the rule about `const`?

42. **Check `var` scope in a block:**  
    Declare `var x = 5` inside `{}`. Can you access it outside?

43. **Compare results of `+` and `-` with a string:**  
    Why does `"5" - 2` result in a number while `"5" + 2` gives a string?

44. **Declare a variable but don’t assign it:**  
    What is its value and type when you log it?

45. **Compare `Boolean("false")` vs `Boolean(false)`:**  
    Why do they give different results? What is truthy and falsy?

---

## 🔴 Hard (Deeper Understanding) — 10 Questions

46. **What’s the difference between `undefined` and not defined?**  
    Try logging a variable that was never declared vs one that is declared but uninitialized.

47. **String + Number addition:**  
    ```js
    let name = "John";
    let age = 25;
    let intro = name + age;
    ```  
    What does `intro` contain and why?

48. **Multiplying two string numbers:**  
    ```js
    let a = "2";
    let b = "3";
    let result = a * b;
    ```  
    Why does it return 6?

49. **Coercion with different types:**  
    ```js
    "10" - true;
    "10" - null;
    "10" - undefined;
    ```  
    What are the results? Why do some give `NaN`?

50. **Compare `null == undefined` vs `null === undefined`:**  
    What’s the difference and what does each return?

51. **Evaluate types of various values:**  
    ```js
    typeof null;
    typeof [];
    typeof {};
    ```  
    Why do they all return `"object"`?

52. **Check floating point math:**  
    ```js
    let a = 0.1 + 0.2;
    ```  
    Is the result exactly `0.3`? Why not?

53. **Use `typeof` before a variable is declared:**  
    What happens with `var`, `let`, and `const`?

54. **Try using a reserved word as a variable:**  
    ```js
    let let = "hello";
    ```  
    What kind of error appears?

55. **Evaluate string division:**  
    ```js
    let x = "10" / 2;
    let y = "ten" / 2;
    ```  
    Why does one give a number and the other `NaN`?

---



Happy Coding 🚀

# ☂️ Java Exception Handling - Interview Questions

---

## 🔹 Basic Concepts

1. **What is an exception in Java?**
2. **What is the difference between an error and an exception?**
3. **What is the hierarchy of exception classes in Java?**
4. **What is the difference between checked and unchecked exceptions?**
5. **Can you create your own custom exception in Java? How?**

---

## 🔹 Try-Catch-Finally

6. **What is the purpose of the `finally` block?**
7. **Can a `finally` block be executed even if the try block has a return statement?**
8. **What happens if an exception is thrown inside a `finally` block?**
9. **Is it possible to have multiple catch blocks for a try block?**
10. **What is multi-catch in Java 7 and later?**

---

## 🔹 Throw vs Throws

11. **What is the difference between `throw` and `throws`?**
12. **Can you throw multiple exceptions from a method?**
13. **Why must checked exceptions be declared or handled in Java?**
14. **Can constructors throw exceptions?**
15. **Can static blocks throw exceptions?**

---

## 🔹 Custom Exceptions

16. **How do you create a custom checked exception?**
17. **How do you create a custom unchecked exception?**
18. **Why and when should you use custom exceptions?**
19. **Should custom exceptions extend `Exception` or `RuntimeException`?**

---

## 🔹 Exception Propagation

20. **What is exception propagation?**
21. **How are exceptions propagated in Java?**
22. **What happens if no catch block is found for an exception?**
23. **Can an exception be caught at multiple levels in the call stack?**

---

## 🔹 Best Practices

24. **Should you catch `Throwable` or `Exception`? Why not `Error`?**
25. **Why is it a bad practice to catch generic exceptions like `Exception` or `Throwable`?**
26. **What are the drawbacks of using empty catch blocks?**
27. **How should you log exceptions in production-grade code?**
28. **How do you handle exceptions in lambda expressions and streams?**

---

## 🔹 Real-World Scenarios

29. **How would you design exception handling for a layered architecture (Controller → Service → DAO)?**
30. **How can you wrap checked exceptions into unchecked ones and why?**
31. **What is the difference between re-throwing an exception and wrapping it?**
32. **How do frameworks like Spring handle exceptions globally?**

---

## 🔹 Advanced

33. **What is the `Suppressed Exception` in try-with-resources?**
34. **What are suppressed exceptions and how are they handled in try-with-resources?**
35. **What happens if both the try and finally blocks throw exceptions?**
36. **What is the use of `getCause()` and `initCause()` methods in `Throwable`?**
37. **Can exceptions be chained? How?**
38. **What is exception translation?**
39. **How do you test exception scenarios using JUnit and Mockito?**

---

## 🧠 Bonus

40. **What are the pitfalls of overusing exceptions for control flow?**
41. **What is defensive programming and how does it relate to exception handling?**

---

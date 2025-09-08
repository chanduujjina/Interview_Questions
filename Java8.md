
# 📘 Java 8 Interview Questions

---

## 🔹 Lambda Expressions

1. What is a lambda expression in Java 8?  
2. How does a lambda expression differ from an anonymous inner class?  
3. Can lambda expressions access variables from the enclosing scope?  
4. What are the restrictions on using variables inside a lambda?  
5. Can lambdas be serialized?

---

## 🔹 Functional Interfaces

6. What is a functional interface?  
7. What is the purpose of the `@FunctionalInterface` annotation?  
8. Can a functional interface have default or static methods?  
9. Give examples of built-in functional interfaces in `java.util.function`.

---

## 🔹 Method and Constructor References

10. What is a method reference in Java 8?  
11. What are the types of method references?  
    - Static method reference: `ClassName::staticMethod`  
    - Instance method reference: `object::instanceMethod`  
    - Constructor reference: `ClassName::new`  
12. How do method references relate to functional interfaces?

---

## 🔹 Streams API

13. What is the Java 8 Stream API?  
14. What is the difference between `Collection` and `Stream`?  
15. Explain intermediate vs terminal operations in Stream.  
16. What are some commonly used intermediate operations?  
17. What are some terminal operations?  
18. Difference between `map()` and `flatMap()`?  
19. What is `collect()` in streams? How is it used?  
20. How does `filter()` work in streams?  
21. How do you sort elements in a stream?  
22. What is the use of `Optional` with Streams?

---

## 🔹 Optional

23. What is `Optional` in Java 8?  
24. Why should we use `Optional` instead of null?  
25. What is the difference between `Optional.of()`, `Optional.ofNullable()`, and `Optional.empty()`?  
26. How do you use `ifPresent()`, `orElse()`, and `orElseGet()`?  
27. Can `Optional` be used as a method parameter or return type?

---

## 🔹 Default and Static Methods in Interfaces

28. What are default methods in interfaces?  
29. Why were default methods introduced in Java 8?  
30. What happens if two interfaces have the same default method?  
31. Can an interface have a static method? How is it used?

---

## 🔹 Date and Time API (java.time)

32. What are the main classes in the new Date and Time API?  
33. Difference between `LocalDate`, `LocalTime`, and `LocalDateTime`?  
34. How do you format and parse dates in Java 8?  
35. How is `ZonedDateTime` different from `LocalDateTime`?  
36. What is `Duration` and `Period`?

---

## 🔹 Collectors and Grouping

37. How does `Collectors.toList()` work?  
38. What is `Collectors.groupingBy()` and `partitioningBy()`?  
39. What is the difference between `reduce()` and `collect()`?  
40. How can you perform aggregation functions like sum, avg, count using streams?

---

## 🔹 Parallel Streams

41. What are parallel streams?  
42. How do you convert a stream to a parallel stream?  
43. What are the benefits and risks of using parallel streams?  
44. When should you avoid using parallel streams?

---

## 🔹 Miscellaneous

45. What is the difference between `Iterator` and `Spliterator`?  
46. What is the purpose of `Predicate`, `Function`, `Supplier`, `Consumer`?  
47. Can lambda expressions throw checked exceptions?  
48. What is effectively final variable?  
49. How do you handle exceptions in lambda expressions?  
50. How is method overloading affected by lambda expressions?
---


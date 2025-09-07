md_content = """
# 📘 Tricky Core Java Interview Questions (8+ Years Experience)

---

## 1. What’s the difference between `==` and `.equals()` in Java?
- **Follow-up:** How does it behave with `String`, `Integer`, and custom objects?

---

## 2. How does Java handle memory management?
- **Follow-up:** Explain PermGen vs Metaspace (Java 8 onwards), and reference types (strong, soft, weak, phantom).

---

## 3. What are the problems with using `Thread.stop()` and `Thread.suspend()`?
- **Follow-up:** How do you safely stop a thread in production-grade applications?

---

## 4. What is the difference between `synchronized`, `Lock`, and `ReentrantLock`?
- **Follow-up:** When would you prefer `ReentrantLock` over `synchronized`? What is a fair lock?

---

## 5. How does the `volatile` keyword work in Java?
- **Follow-up:** Can it replace synchronization? How does it relate to the Java Memory Model?

---

## 6. What happens when an object becomes eligible for garbage collection?
- **Follow-up:** Is `finalize()` guaranteed to be called? What are the risks?

---

## 7. Can you override a static method?
- **Follow-up:** What about method hiding? How is method resolution done?

---

## 8. What’s the difference between `Exception`, `RuntimeException`, and `Error`?
- **Follow-up:** Should we catch `Error`? Why or why not?

---

## 9. Explain the difference between fail-fast and fail-safe iterators.
- **Follow-up:** Which collections provide which type? What are the risks in concurrent modification?

---

## 10. What is the contract between `hashCode()` and `equals()`?
- **Follow-up:** What happens if you violate the contract in a `HashMap` or `HashSet`?

---

## 11. How does Java's `HashMap` work internally?
- **Follow-up:** What changed in Java 8 with treeification? How are collisions handled?

---

## 12. How is `String` immutable? Can you prove it?
- **Follow-up:** What are the advantages of immutability? What would happen if `String` was mutable?

---

## 13. What is the difference between `Comparator` and `Comparable`?
- **Follow-up:** Can you use both together? How do `TreeSet` and `TreeMap` behave?

---

## 14. How do `wait()`, `notify()`, and `notifyAll()` work?
- **Follow-up:** What’s the risk of using `notify()` over `notifyAll()`? What if `notify()` is called before `wait()`?

---

## 15. Can an abstract class have a constructor? Why?
- **Follow-up:** What’s the use of a constructor in abstract classes?

---

## 16. What's the difference between `ExecutorService` and `ForkJoinPool`?
- **Follow-up:** When would you choose one over the other?

---

## 17. What happens when you call `System.exit(0)`?
- **Follow-up:** Will `finally` blocks execute? What if you're inside a try-catch-finally?

---

## 18. What are memory leaks in Java? How do they occur even with GC?
- **Follow-up:** How would you identify them? What tools can help?

---

## 19. Can you explain the Double-Checked Locking pattern and its issues?
- **Follow-up:** Why was it broken before Java 5? How does `volatile` help?

---

## 20. What's the difference between `ThreadLocal` and a normal variable?
- **Follow-up:** How is it used in multi-threaded environments? Common pitfalls?

---

## 🧠 Bonus: Behavioral & Design

- How would you refactor a legacy Java application to improve performance and readability?
- How do you handle concurrency in high-load applications?
- Have you faced any issues with memory or thread leakage in Java apps?
"""



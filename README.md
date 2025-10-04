# Effective-Modern-CPlusPlus
This column draws on insights and best practices presented in Effective Modern C++.

# My First Example

This is a simple **bold** and *italic* text example.

## Here’s a List
- Item 1
- Item 2
  - Sub-item
- Item 3

## Add a Link
You can check my project [here](https://github.com/yourname/yourrepo).

## Code Example

```cpp
#include <iostream>
int main() {
    std::cout << "Hello, world!" << std::endl;
}
```

# Introduction — Exploring *Effective Modern C++*

Before **C++14**, there were four official versions of the language: **C++98**, **C++03**, **C++11**, and **C++14**.  
Among them, **C++11** marked a turning point in **modern** C++ development. It introduced several transformative features:

---

## Key Modern Features in C++11

C++11 introduced not only new syntax and functionality but also new ways of thinking about code design.

### Language Features
- `auto` declarations for automatic type inference  
- Range-based `for` loops for cleaner iteration  
- Lambda expressions for inline, anonymous functions  
- Rvalue references enabling **move semantics**

### Concurrency Support
C++11 brought standard threading and atomic operations, making **concurrent programming** portable and safer.

### Idiomatic Shifts

C++11 also changed what is considered "good style" in modern C++:

- `0` → **`nullptr`**  
- `typedef` → **`using` alias declarations**  
- Unscoped enums → **`enum class`**  
- Raw pointers → **Smart pointers (`std::unique_ptr`, `std::shared_ptr`)**  
- Copying objects → **Moving objects** (where possible)

---

## About *Effective Modern C++*

To continue writing efficient and reliable code in this evolving ecosystem, Scott Meyers’s *Effective Modern C++* provides a wealth of practical insights and best practices.  

In this column, I plan to:
- Summarize and discuss the suggestions from *Effective Modern C++*  
- Present code examples illustrating these ideas  
- Add my own understanding and reflections along the way  

The goal is both for my **future review** and for the **benefit of readers** who wish to deepen their understanding of modern C++.

---

*Written by fumeshroom*  
*Date: 2025-10-04*  


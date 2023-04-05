---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Welcome to Kotlin

Fundamentals of Kotlin

---
transition: slide-right
---

# What is Kotlin?

Kotlin is a statically typed, multi-paradigm programming language developed by JetBrains.

- It is interoperable with JVM and Java Class Libraries.

- Officially supported by Google as the preferred language for Android app development.


<!--
 Since the release of Android Studio 3.0 in October 2017, Kotlin has been included as an alternative to the standard Java compiler. 
 
 The Android Kotlin compiler produces Java 8 bytecode by default (which runs in any later JVM), but lets the programmer choose to target Java 9 up to 19, for optimization
-->

---
transition: slide-left
---

# Why use Kotlin?

- Readability
<!-- Readability is a primary goal in the design of the language. Designed to be very concise -->
- Tooling
<!-- Kotlin comes from JetBrains, a company that specializes in developer tooling. It has first-class tooling support, and many language features were designed with tooling in mind. -->
- Multi-Paradigm
<!-- Supports Imperative Programming, Functional Programming, and Object-Oriented Programming paradigms -->

---
transition: slide-left
---

# What is Kotlin used for

- **Android Development** - Kotlin is officially supported by Google as the preferred language for Android app developers.
<!--
 Since the release of Android Studio 3.0 in October 2017, Kotlin has been included as an alternative to the standard Java compiler. 
 
 The Android Kotlin compiler produces Java 8 bytecode by default (which runs in any later JVM), but lets the programmer choose to target Java 9 up to 19, for optimization
-->
- **Back-end web development** - Back-end web app development traditionally uses Java. Kotlin is interoperable with Java and supports Java Class Libraries.
- **Full-stack web development** - Developers use Kotlin for JavaScript to translate Kotlin lines of code into JavaScript for front-end web development. Kotlin can also be used for Front-end development using the Kotlin/JS compiler
- **Data science** - Data Scientists have always used Java to calculate numbers, detect trends, and make predictions. Tools used by data scientists such as Jupyter and Zeppelin also support Kotlin
---
transition: slide-left
---

# Basic Syntax

---
transition: slide-left
---

# Hello World

```ts{}
fun main() {
  println("Hello World!")
}
```
<br></br>

- `fun`: keyword to declare a function
- `main`: the function that is called when executing the program.
- `print`: function that displays the inputted parameter when called.

<!-- Unlike some langages, you do not need to use a semicolon (;) at the end of an expression in Kotlin. -->

---
transition: slide-left
---

# Data Types
<br></br>

## Integer Types

 |     |     |
 | --- | --- |
 | **Type** | **Range** |
 | `byte` | -128 to 127 |
 | `short` | -32,768 to 32,767 |
 | `int` | -2,147,483,648 to 2,147,483,647 |
 | `long` | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |

<!-- int: Negative 2 billion, 147 million, 483 thousand, 647 -->

<!-- long: 9 Quintillion, 223 Quadrillion, 372 Trillion, 36 Billion, 854 Million, 775 Thousand, 807 

Optionally, the value can be ended with “L” to denote Long data type.-->

---
transition: slide-left
---


# Data Types
<br></br>

## Floating Point Types

 |     |     |
 | --- | --- |
 | `float` | The `Float` data type holds up to six or seven demial points |
 | `double` | The Double data type supports up to fifteen decimal points. |

Both Float and Double data types support representing a scientific number with an ‘e’ or ‘E’ to indicate the power of 10.


---
transition: slide-left
---


# Data Types
<br></br>

## Booleans

The Boolean data type can only take the values true or false.
<br></br>

## Boolean Operators
<!-- In order of precedence -->
 |     |     |     |
 | --- | --- | --- |
 | **NOT** | An unary operator that reverses the Boolean value. | Denoted with `!` |
 | **XOR** | A binary operator that returns true if the operands have different values. Otherwise it returns false. | Pronounced "**Exclusive OR** |
 | **AND** | A binary operator that returns true if both operands are true. Otherwise it returns false. | Denoted with `&&` |
 | **OR** | A binary operator that returns true if at least one operand is true. Otherwise it returns false. | Denoted with `||` |

---
transition: slide-left
---

# Characters

- The Char data type is used to store a single character.

- A Char value must be surrounded by single quotation marks (’).

- Unlike Java, you **cannot** use ASCII values to display certain characters.

```ts

```

<!-- The value 66 would output a “B” in Java, but will generate an error in Kotlin. -->

---
transition: slide-left
---

# String

- The `String` data type is used to store a sequence of characters.

- `String` values must be surrounded by **double** quotation marks (”).

---
transition: slide-left
---


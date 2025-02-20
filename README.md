# JanabScript README

JanabScript is a simple, expressive scripting language designed to introduce basic programming constructs. Its syntax is intuitive and focuses on readability, making it ideal for beginners and anyone interested in learning programming fundamentals.

## Table of Contents

- [Datatypes](#datatypes)
- [Input/Output](#inputoutput)
- [Control Flow](#control-flow)
- [Strings](#strings)
- [Comments](#comments)
- [Arithmetic Operations](#arithmetic-operations)
- [Identifiers](#identifiers)
- [Examples](#examples)
- [Conclusion](#conclusion)

## Datatypes

JanabScript supports several core datatypes:

- **Integer (**\`\`**)**\
  Used for whole numbers.\
  *Example:*

  ```janabscript
  adad a = 21;
  ```

- **Decimal (**\`\`**)**\
  Represents numbers with fractional parts. JanabScript allows decimals with precision up to five digits after the decimal point.\
  *Example:*

  ```janabscript
  nukta pi = 3.14159;
  ```

- **Boolean**\
  Used for true/false values. The language uses specific keywords for boolean values: `sahi` for true and `galat` for false.\
  *Example:*

  ```janabscript
  sach flag = sahi;
  ```

- **Character (**\`\`**)**\
  Holds a single lowercase alphabet character.\
  *Example:*

  ```janabscript
  harf ch = 'a';
  ```

## Input/Output

JanabScript provides simple keywords for interacting with the user:

- **Print Output (**\`\`**)**\
  Outputs text or variable values to the user.\
  *Example:*

  ```janabscript
  farmai "Hello Janab";
  ```

- **Input (**\`\`**)**\
  Captures input from the user and assigns it to a variable.\
  *Example:*

  ```janabscript
  sun name;
  ```

## Control Flow

To direct program execution, JanabScript offers control flow statements:

- **If Statement (**\`\`**)**\
  Begins with `agar` followed by a condition in parentheses.\
  *Example:*

  ```janabscript
  agar (x > 0) {
      // statements to execute if the condition is true
  }
  ```

- **Else Statement (**\`\`**)**\
  Provides an alternate block of code if the if condition fails.\
  *Example:*

  ```janabscript
  warna {
      // statements to execute if the condition is false
  }
  ```

## Strings

String literals in JanabScript are enclosed in double quotes. They are used to represent text in the code.\
*Example:*

```janabscript
"Janabscript zindabad!";
```

## Comments

Comments allow you to add explanations or disable code without affecting execution:

- **Single Line Comments**\
  Begin with `//` and continue to the end of the line.\
  *Example:*

  ```janabscript
  // This is a single-line comment.
  ```

- **Multiline Comments**\
  Enclosed between `/*` and `*/`, spanning multiple lines if needed.\
  *Example:*

  ```janabscript
  /*
     This is a multiline comment.
     It can span multiple lines.
  */
  ```

## Arithmetic Operations

JanabScript includes the following arithmetic operators for mathematical expressions:

- **Addition:** `+`
- **Subtraction:** `-`
- **Multiplication:** `*`
- **Division:** `/`
- **Modulus:** `%`
- **Exponentiation:** `^`

These operators can be used to build and evaluate expressions as part of your programs.

## Identifiers

Identifiers are names given to variables. In JanabScript, they must begin with a lowercase letter and may contain lowercase letters, digits, and underscores.\
*Example:*

```janabscript
score_1 = 100;
```

## Examples

### Basic Variable Declaration

```janabscript
adad count = 10;
nukta fraction = 0.12345;
sach isActive = sahi;
harf letter = 'a';
```

### Input and Output

```janabscript
farmai "Enter your name:";
sun userName;
farmai "Welcome, " + userName;
```

### Conditional Statements

```janabscript
adad number = 5;
agar (number > 0) {
    farmai "Positive number";
} warna {
    farmai "Non-positive number";
}
```

## Conclusion

JanabScript offers an easy-to-read syntax that covers essential programming features including datatype declarations, input/output operations, control flow, arithmetic expressions, and commenting. This simplicity makes it a great starting point for learning the basics of programming.

Happy coding with JanabScript!


JanabScript Syntax
==================

Keywords:
---------
1. janab banao  
   Usage: Declare a variable (similar to "let").  
   Example:  
       janab banao adad a = 5;

2. agar  
   Usage: Start an if-condition block ("if").  
   Example:  
       agar (a > 0) { ... }

3. warna  
   Usage: Else part of the condition ("else").  
   Example:  
       warna { ... }

4. janab bolo  
   Usage: Print output to the screen ("print").  
   Example:  
       janab bolo a;

Data Types:
-----------
1. adad  
   Meaning: Integer (whole number).  
   Example:  
       janab banao adad a = 5;

2. nukta  
   Meaning: Decimal (real number).  
   Example:  
       janab banao nukta pi = 3.14159;

3. sach  
   Meaning: Boolean type.  
   Literals:  
       sahi   -> true  
       galat  -> false  
   Example:  
       janab banao sach flag = sahi;

4. harf  
   Meaning: Character (single letter).  
   Example:  
       janab banao harf abjad = 'x';

Operators & Syntax:
---------------------
- Assignment:  
  Use "=" to assign values.  
  Example:  
      janab banao adad a = 10;

- Arithmetic Operators:  
  +  -> Addition  
  -  -> Subtraction  
  *  -> Multiplication  
  /  -> Division  
  %  -> Modulus  
  ^  -> Exponent  
  Example:  
      janab banao adad natija = a + b * 2;

- Statement Termination:  
  End each statement with a semicolon (;).

- Grouping:  
  Use parentheses () for conditions and expressions.  
  Use curly braces {} to group blocks of code.

Comments:
---------
- Single-line Comment:  
  Start with "//"  
  Example:  
      // Yeh ek comment hai, janab.

- Multi-line Comment:  
  Enclose in /* ... */  
  Example:  
      /* Janab, yeh multi-line
         comment hai */

Example Program in JanabScript:
--------------------------------
janab banao adad a = 5;
janab banao adad b = 3;
janab banao adad natija = a + b * 2;

agar (natija > 10) {
    janab bolo natija;
} warna {
    janab bolo a;
}

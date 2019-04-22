# Basic Syntax
In order to understand the basic syntax of languages, let’s check these

**Comments**

Comments are a way to improve the readability of a program. Comments can be used to include additional information and its are ignored by the compiler.

types of comments of the languages


item| Python | Groovy | TypeScript
---------|----------|---------|---------
 Single-line comments |#  | // | //
 Multi-line comments | '''|/* */ | /* */
Case sensitive ? | yes| yes| yes

**Identifiers**

Identifiers are used to define variables, functions or other user defined variables

**_Python Identifiers_**

A Python identifier is a name used to identify a variable, function, class, module or other object. An identifier starts with a letter A to Z or a to z or an underscore (_) followed by zero or more letters, underscores and digits (0 to 9).

Python does not allow punctuation characters such as @, $, and % within identifiers
Here are naming conventions for Python identifiers −

* Class names start with an uppercase letter. All other identifiers start with a lowercase letter.

* Starting an identifier with a single leading underscore indicates that the identifier is private.

* Starting an identifier with two leading underscores indicates a strong private identifier.

* If the identifier also ends with two trailing underscores, the identifier is a language-defined special name.

**_Groovy Identifiers_**

Identifiers are used to define variables, functions or other user defined variables. Identifiers start with a letter, a dollar or an underscore. They cannot start with a number. 

Here are some examples of valid identifiers −

    def employeename 

    def student1 

    def student_name

where def is a keyword used in Groovy to define an identifier.

**_Identifiers in TypeScript_**

Identifiers are names given to elements in a program like variables, functions etc. The rules for identifiers are −

* Identifiers can include both, characters and digits. However, the identifier cannot begin with a digit.

* Identifiers cannot include special symbols except for underscore (_) or a dollar sign ($).

* Identifiers cannot be keywords.

* They must be unique.

* Identifiers are case-sensitive.

* Identifiers cannot contain spaces.

**Data types**

In any programming language, you need to use various variables to store various types of information. Variables are nothing but reserved memory locations to store values. This means that when you create a variable you reserve some space in memory to store the value associated with the variable.

You may like to store information of various data types like string, character, wide character, integer, floating point, Boolean, etc. Based on the data type of a variable, the operating system allocates memory and decides what can be stored in the reserved memory.

_Python data types_

    Numbers: int, float, complex
    String
    List
    Tuple
    Dictionary

_TypeScript data types_

    Number
    String
    Boolean
    Void
    Null
    Undefined

_Groovy data types_

    byte  
    short  
    int  
    long   
    float  
    double  
    char  
    Boolean  
    String  

**Operators**
The major operators can be classified as 

* Arithmetic operators
* Logical operators
* Relational operators
* Bitwise operators
* Assignment operators
* Ternary/conditional operator
* String operator
* Type Operator

**Types of Operator**

Language supports the following types of operators

- Arithmetic Operators
- Comparison (Relational) Operators
- Assignment Operators
- Logical Operators
- Bitwise Operators
- Membership Operators
- Identity Operators

(P)ython | (G)roovy | (T)ypescript

**Arithmetic Operators**

| Item | Operator | Apply | Not Apply |
| --- | --- | --- | --- |
| Addition | + | PGT |   |
| Subtraction | - | PGT |   |
| Multiplication | \* | PGT |   |
| Division | / | PGT |   |
| Modulus | % | PGT |   |
| Exponent | \*\* | PGT |   |
| Floor Division | // | PT | Groovydef x = 26def y = 10 def resultIntDiv = x.intdiv(y) |

**Unary Operators**
In terms of unary arithmetics operators, the ++ (increment) and -- (decrement) operators are available, both in prefix and postfix notation:

| Item | Operator | Apply | Not Apply |
| --- | --- | --- | --- |
| Increment | ++ | GT |  P | 
| Decrement | -- | GT |  P | 

**Comparison Operators**

These operators compare the values on either side of them and decide the relation among them. They are also called Relational operators.



| **Operator** | **Description** | **Apply** | **Not Apply** |
| --- | --- | --- | --- |
| == | equal | PGT |   |
| != | not equal, | PGT |   |
| >| greater than | PGT |   |
| >| less than | PGT |   |
| >= | greater than or equal to | PGT |   |
| <= |  less than or equal   | PGT |   |

**Assignment Operators**

| **Operator** | **Description** | **Apply** | **Not Apply** |
| --- | --- | --- | --- |
| = | Assigment | PGT |   |
| += | Add AND | PGT |   |
| -= | Subtract AND | PGT |   |
| \*= | Multiply AND | PGT |   |
| /= | Divide AND | PGT |   |
| %= | Modulus AND | PGT |   |
| \*\*= | Exponent AND | PGT |   |
| //= | Floor Division | PGT |   |

**Bitwise Operators**

Bitwise operator works on bits and performs bit-by-bit operation. Assume if a = 60; and b = 13; Now in binary format they will be as follows −

a = 0011 1100

b = 0000 1101

-----------------

a&amp;b = 0000 1100

a|b = 0011 1101

a^b = 0011 0001

~a = 1100 0011





| **Operator** | **Description** | **Apply** | **Example** |
| --- | --- | --- | --- |
| &amp; | Binary AND | PGT | (a &amp; b) (means 0000 1100) |
| | | Binary OR | PGT | (a | b) = 61 (means 0011 1101) |
| ^ | Binary XOR | PGT | (a ^ b) = 49 (means 0011 0001) |
| ~ | Binary Ones Complement | PGT | (~a ) = -61 (means 1100 0011 in 2&#39;s complement form due to a signed binary number. |
| \&lt;\&lt; | Binary Left Shift | PGT | a \&lt;\&lt; 2 = 240 (means 1111 0000) |
| \&gt;\&gt; | Binary Right Shift | PGT | a \&gt;\&gt; 2 = 15 (means 0000 1111) |

**Logical Operators**

| **Operator** | **Python** | **Groovy** | **TypeScript** |
| --- | --- | --- | --- |
| Logical AND | AND | &amp;&amp; | &amp;&amp; |
| Logical OR | OR | || | || |
| Logical NOT | NOT | ! | ! |

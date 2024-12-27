# JavaScript
#### Basics 
• What is JavaScript?
• Key Concepts
• Components
• Web browsers
• Create alert pop-up
• Basic arithmetic

#### Numbers and Math
The order of operations in JavaScript follows the acronym **PEMDAS** (or **BODMAS** in some regions):
|   Operation                           |   Description                                                             |
|:---                                   |:---                                                                       |
| **P**arenthesis/**B**rackets          | Operations within parentheses are always evaluated first.                 |
| **E**xponents/**O**rders              | Exponents (like `2^3`) are evaluated next.                                |
| **M**ultipication and **D**ivision    | These have equal precedence and are evaluated from left to right.         |
| **A**ddition and **S**ubstraction     | These also have equal precedence and are evaluated from left to right.    |

In this case:
1. **Multiplication** `3 * 4 = 12`
2. **Addition** `2 + 12 = 14` 
``` JavaScript
let result = 2 + 3 * 4;
```
**Using Parenthesis:**
You can use parenthesis to change the order of operation:
In this case:
1. **Parenthesis** `2 + 3 = 5 `
2. **Multiplication** `5 * 4 = 20`
``` JavaScript
let result = (2 + 3) * 4;
```
***Key Points:***

**Left-to-right**, if the multiple operators have the same precedence (like multiplication and division), they are evaluated from left to right.
**Clarity**, using parenthesis can make your code more readable and prevent unexpected results
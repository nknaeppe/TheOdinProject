1. Name the three ways to declare a variable?
 - let, var ,const
2. Which of the three variable declarations should you avoid and why?
- var, because it misses a scoping mechanism. Let and const just work in their defined block
3. What rules should you follow when naming variables?
- The variable should use a descriptive Name, so the code is easily understandable. 
- do not use names that are already taken ( return, let, etc..)
- do not start with capitalized letters
- use camelcase
4. What should you look out for when using the + operator with numbers and strings?
- the code is interpreted from left to the right. If the operation starts with a string, the following is also interpreted as a string.
5. How does the % operator work?
- the operator returns the remainder of the divison. 7 % 5 is 2, because 5 can be divided by 5 and leaves 
6. Explain the difference between == and ===.
- the == operator only compares the value of the variable, the strict === operator compares the value and the type of the variable.
7. When would you receive a NaN result?
- when you doing an arithmetic operation with a non non-numeric variable. Like dividing a number by a string like "apple"
8. How do you increment and decrement a number?
- by adding ++ in front or behind a variable, like ++counter. To decrement: --counter, counter--.
9. Explain the difference between prefixing and post-fixing increment/decrement operators.
- The difference between prefixing or post-fixing is, that is either returns the old or the ne value. A prefix increments or decrements the variable and return the new one. The post-fix increments or decrements the value and returns the old value.
10. What is operator precedence and how is it handled in JS?
- The operator precedence sets the priority of the operation. A high priority will executed before a lower priority. A multiplikation will be calculated before a substraction. Parantheses are used for overwrtiting lower priotrity operations, because they have a higher precedence. This way a substraciton can be made before a multiplication
11. How do you access developer tools and the console?
- by right clicking in the browser and selecting inspect
12. How do you log information to the console?
- consologe.log("Information")
13 What does unary plus operator do to string representations of integers?
- it converts the string to number. 

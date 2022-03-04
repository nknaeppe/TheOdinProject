1. What are the eight data types in JavaScript?
- primitive: string, number, bigint, boolean, null, undefined
- complex: object, symbol
2. Which data type is NOT primitive?
- object
3. What is the relationship between null and undefined?
- null is datatype which only has the value null, it can be referred to a variable as an empty value.
- undefined is assigned to a variable after it is initalized. It only has the value undefined.
4. What is the difference between single, double, and backtick quotes for strings?
- single -> general string
- double -> general string
- backticks --> String with extra functionality, allows to embed variables and expression with ${}
5. What is the term for embedding variables/expressions in a string?
- Template literals
6. Which type of quote lets you embed variables/expressions in a string?
- the backtick quotes
7. How do you embed variables/expressions in a string?
- by using ${} inside the backtick quuote
8. How do you escape characters in a string?
- by adding a backslash to letter which needs to be escaped
9. What is the difference between the slice/substring/substr string methods?
- slice : extracts a part of a string and returns a new string
- substring: extracts a number of characters from a string between two specified indices
- substr: extracts a number of characters from a string, from a start index
10. What are the three logical operators and what do they stand for?
- AND &&, if one of the value is false , the output is false. If all are true , the output is true
- OR || if one of the value is true, the output is true. If all are false the output is false;
-  NOT ! It inverse the value of the input. A true statement with a not operator outputs false
11. What are the comparison operators?
- "<"
- ">"
- "=="
- "!="
- "==="
- "!=="
- "=<"
- "=>"
12. What are truthy and falsy values?
- a falsy value is "", null, undefined. NaN
- all other values are truthy
13. What are the falsy values in JavaScript?
- "", null, undefined.
14. What are conditionals?
- conditionals are used to make decisions by code. An input is used to make decision and give an output, which can change by the input
15. What is the syntax for an if/else conditional?
´´´
if (condition) {
//do something
}
else{
//do this if condition is not true
}
´´´
16. What is the syntax for a switch statement?
´´´
switch(condition){
case condition1:
  //do something
  break;
case conditon2:
  //do something else
  break;
default: {
  //runs if none cases matches;
}
}
´´´
17. What is the syntax for a ternary operator?
´´´
let result = (condition) ? value1 : value2;
´´´
18. What is nesting?
- Putting if else statements inside another one 

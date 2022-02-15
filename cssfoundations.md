1. What are the main differences between external, internal, and inline CSS?
- external: The CSS used in HTML file is stored in an external file. With the link tag, the html file can locate the css stylesheet. 
- internal: The CSS is stored in the head element of the html file. The CSS code is stored between the style tag.
- inline: The inline css is placed in the html tag. The style tag inside the html tag and written inline and seperated by a ;.
2. What is the syntax for class and ID selectors?
- class: #
- id: .
3. How would you apply a single rule to two different selectors?
- To chain two different css selectors a , is used. The two selectors are written before the curly braces and seperated by a comma.
- ``` selector1, selector2 { ... } ```
4. Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?
- ´´´#title, .primary {... }´´´
5. What does the descendant combinator do?
- A descendant combinator is used to style html elements, which are nested. It only styles specfic elements, which are nested inside another element.
6. Between a rule that uses one class selector and a rule that uses three type selectors, which rule has the higher specificity?
- The class selector has higher specifcity.

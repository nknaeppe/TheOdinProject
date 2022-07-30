1. What is the difference between the child combinator and the descendant combinator?
- Descendant combinator: combines two elements, if the first element has an ancestor with the second element, it gets selected 
- Child combinator: Only selects the direct children
2.How does the syntax of pseudo-classes and pseudo-elements differ?
- """:pseudo-class"""
- """::pseudo-elements"""
3.Do pseudo-classes exist somewhere in HTML? Do pseudo-elements?
-  Pseudo-class selectors are prefixed with a single colon and are a different way to target elements that already exist in HTML.
-  Pseudo-elements are prefixed with two colons and are used to target elements that don’t normally exist in the markup.
4. Name two ways you could select every second child of an element, starting with the first.
- :nth-child(2n)
- :nth-child(2n - 2)
5. What is the difference between div:first-child and div:last-child? What will each select?
- div:first-child --> First element of its siblings
- div:last-child --> Last element of its siblings
6. What selector would you use to style a button a user is currently hovering over? How about one that is currently being clicked on?
- :hover
7. How could you select all input elements with a type of text?
- inpute[type="text]
8. How could you select all classes that begin with thunder?
- [class^="thunder"]

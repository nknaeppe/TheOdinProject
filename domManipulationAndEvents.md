1. What is the DOM?
- Document Object Model
- it's an programming interface for other language to manipulate the html of a website
- it views the html a tree of nodes
2. How do you target the nodes you want to work with?
- with a query selector, like querySelector(<node>). The node will be copied into a variable and can be manipulated. It uses the CSS Selector
3. How do you create an element in the DOM?
- with document.createElement(<element>)
- the element is only created in memory, so it still needs to be added
4. How do you add an element to the DOM?
- by appending it to node with appendChild(<elemen>)
5. How do you remove an element from the DOM?
- <parentNode>.removeChild(element)
6. How can you alter an element in the DOM?
- By selecting it first and then edit the properties
- <element>.style.color ="bule";
7. When adding text to a DOM element, should you use textContent or innerHTML? Why?
- textContent should be used, because innerHTML can also interpret HTML tags and even javascript, which can lead to cross site scripting
- it is more safe to use textContent, because it only interprets everything as text
8. Where should you include your JavaScript tag in your HTML file when working with DOM nodes?
- it should be placed after the body element,so the DOM will be rendered before the javascript
9. How do “events” and “listeners” work?
- events are actions that occure on a website, they are triggered by interactions like a click or by pressing a key.
- an event can be added direct into the html or to the DOM in the javascript.
- the an event listener is added to the node inside the Javascript
10. What are three ways to use events in your code?
- Method1: attach it to the HTML elements
  ```
  <button onclick="alert('Hello World')">Click</button>
  ```
- Method2: Adding it to the Javascript
  ```
  HTML > <button id="btn">Click Me</button>
  JS:
  const btn = document.querySelector('#btn')
  btn.onclick = () => alert("Hello World");
  ```
- Method3:
  ```
  //same as  Method2 but different function
  btn.addEventListener('click', () => {
   alert("Hello World");
  }
  ```  
11. Why are event listeners the preferred way to handle events?
- because with a DOM element can only have 1 "onclick" property
- an event listener is more flexible and powerful
12. What are the benefits of using named functions in your listeners?
- named function are more clean and the function can be used again.
13. How do you attach listeners to groups of nodes?
- By getting a nodelist ( querySelectorAll(<element>)) and iterate through the list --> ```nodelist.forEach(node) => { //node.doSomething }```
14. What is the difference between the return values of querySelector and querySelectorAll?
- The querySelector returns the first node of the dom with the matching query. The querySelectorAll creates a nodelist with all nodes  matching the query.
15. What does a “nodelist” contain?
- a collection of document nodes
16. Explain the difference between “capture” and “bubbling”.
  example structure:
  body
    div-1
      div-2
        div-3
- when an event happens, the browser finds it, by following the html structure. It goes all the way down to find it. After it has found the element with the listener, it goes back to the body element, bubbling up.
- Bubbling: Will run the structure down from body to div-3
- Capture: An option, which can be added to the event listener. It changes the direction, so it runs the strcture up from div-3 to body
- Can be stopped triggering events on the parent nodes by adding stopPropagation() to the element of the funciton. Stop bubbling
 
  

  

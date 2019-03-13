

# A Front-end handbook

This handbook is a list of keywords that you can use to search for specific tutorials, videos, documents or references. These keywords are chosen base on our experience accumulated through many projects, so it may not be completed but can be improved over time. The reason we only list the keywords is that you can freely choose a source (i.e. documents, websites, videos, tutorials, books) of your favourite to learn. If you can’t find any source that you like, we have a list of recommended sources, including our previous and current sources.
The content of this handbook will cover all the major languages and technologies that run the entire front-end world, from the simplest language HTML to the complex Javascript. In every section, there are quizzes and exercises for you to do. Quizzes are a list of small questions, it may test how well have you learnt throughout the section, but it may also test your searching, reading and thinking skills by asking about historical knowledge, use cases or the purpose of a particular concept. Exercises, on the other hand, are lists of exercises that require you to practice just like a real project, helps you understand what you have learnt and keeps the lessons in your mind for a long time.

[[toc]]

## 1. HTML
### 1.1. Basics
- What is HTML?
- HTML syntax.
- HTML tags: html, head, body, div, p, a, img, iframe, section, article, header, footer, link, script, style, input, form, button, textarea, source, video, table, ul, ol, li, etc.
- HTML attributes: src, alt, style, class, id, title, value, placeholder, name, href, target, etc.
- SVG, Canvas.
- Embedded iframe.
- HTML Meta tags.
- Relative path, absolute path.
### 1.2. Advances
- HTML Entities.
- HTML Charset.
- URL, URI. URN.
- XHTML, XML.
- HTML picture tag.
- Search Engine Optimization.
### 1.3. Quizzes
- What is the similarities and differences between HTML, Markdown and Latex?
- What is the “Hypertext” in HTML means?
- What is the similarities and differences between HTML and XML?
- What are the advantages and disadvantages of SVG over PNG and JPEG?
### 1.4. Exercises
Try to explore the HTML structure of popular websites such as:
https://www.amazon.com/
https://vnexpress.net/
or any website of your interest.
Figure out the purpose of each tag, which case to use, which case not.

## 2. CSS
### 2.1. Basics
- What is CSS?
- CSS syntax.
- Insert CSS.
- CSS tags, classes, ids.
- CSS basic properties: position, top, right, bottom, left, padding, margin, width, height, color, text-align, border, font, background, display, overflow, float, etc.
- CSS combinators.
- CSS pseudo-elements, pseudo-classes.
- RGB(A) color, Hex color.
- CSS transform, filter.
- CSS transition, animation.
- CSS units.
- CSS specificity.
### 2.2. Advances
- CSS naming convention.
- CSS variables.
- CSS aspect ratio.
- CSS flexbox.
- CSS grids.
- CSS media queries.
- Responsive design.
- CSS vendor prefixes.
- CSS preprocessor: Sass, Less.
- CSS frameworks: Bootstrap.
- CSS minifier.
### 2.3. Quizzes
- In which case should we use external CSS, internal CSS or inline style?
- Why do we need vendor prefixes?
- Why do we need Sass or Less? Why not just writing plain CSS?
- Why do we need to minimize CSS file?
- What happens if we use long but easy to understand class or id? And if we use meaningless but short class or id?
### 2.4. Exercises
- Complete all exercises at https://www.w3schools.com/css/css_exercises.asp, or at a site that provides CSS exercises from basic to advanced.
- Remake the top navigation bar of https://www.amazon.com/ as similar as possible.

## 3. JAVASCRIPT
Because JavaScript is so huge that it can’t be learnt at once, we put exercises at multiple breakpoints from Basics to Advances instead of placing them at the end of this section. Each breakpoint marks a milestone on the journey of learning the hard JavaScript. The keywords between 2 breakpoints focus on a particular knowledge to achieve a specific goal.
### 3.1. Basics
#### 3.1.1. Introduction
- Script tag, external JS.
- JS output: console.log(), alert(), document.write(), innerHTML.
- JS syntax.
- JS statements (if, else, switch, for, while).
- JS variables.
- JS comments.
- JS operators.
- Exercises:
- Calculate: a = 10!
- Calculate the sum from 1 to 1000.
- Convert from 37 Celcius degree to Fahrenheit.
#### 3.1.2. Data types & methods
- JS data types:
- String.
- Array.
- Object.
- Dates.
- Math.
- JS type conversion.
- JS bitwise.

##### Exercises:
- Concatenate 2 string “Hello” and “World”, separated by white space.
Calculate the sum of this array: <br>`[4, 9, 13, 4, -5, 24, 19, 66, 9]`

- Declare an object with 2 properties:`name: <your_name>`,`birthday: <your_birthday>`.After that, create a new property `“email”` with the value of your email in this object.
- Convert this string `“01-01-2019”` to `Date` object.
- Create an array of 100 elements from `Math.random()`
- Calculate: `sin(x) + cos(x) * exp(x) ^ 2, with x = 3pi/4.`
- `parseInt()` may be used later.
#### 3.1.3. Function
- JS function:
  - Declare function.
  - Function parameter.
  - Function call, Function apply.
- The `this` keyword.
- JS scope.
##### Exercises:
- Write a function to calculate Fibonacci sequence.

  Function prototype:`function fibonacci(n) { /* Your code here */ }`

  Example: `fibonacci(10) = 55`
	
- Write a function that finds a number in an array and returns its index in the array, if not found return -1.
  Function prototype:`function findIndex(n, array) { /* Your code here */ }`
  
  Example:
	</br>`findIndex(10, [4, 10, 3]) = 1`
	</br>`findIndex(9, [4, 10, 3]) = -1`

#### 3.1.4. DOM & BOM
- DOM and the “document” object.
- Event listeners.
- Browser Object Model: 
  - window
  - screen 
  - location 
  - history
  - timing events, etc.
##### Exercises:
- Create a button that changes a paragraph’s color property when clicked.
- Display the value of the current width of the window, this value will be updated if the window is resized.
- When you press down the left mouse button, moving it around and release it. Compute the distance in ‘px’ between the position where the left mouse button is pressed and the position where it is released.
- Create a slide show effect that is similar to https://www.hpacademy.vn/.
- Use `getBoundingClientRect` and `getSelection` to display a `div` when we select a text using the mouse. This `div` contains the length of the selected text and is placed right above the select text. The image below will show, replace the icons with the length of the selected text (which is 12 in this image).

#### 3.1.5. Regular Expression
- Regular Expression.
##### Exercises:
- Write a function to find “123” in a string, it should return the index of the first encounter in the string.
  
  Function prototype: `function find123(str) { /* Your code here */ }`
  
  Example: `find123(“abc123”) = 3`

- Given an email, write a function to return the domain name of that email.
  
  Function prototype: `function findDomainName(email) { /* Your code here */ }`
  
  Example: `findDomainName(“example@abc.com”) = “abc”`

- Write a function to count the number of words in a string. A word is valid if it only contains characters from a-z and A-Z, no digits or any other characters are allowed.
  
  Function prototype: `function countWords(str) { /* Your code here */ }`
  
  Example: `countWords(“This is the 1st sentence. This is not the 123rd sentence.”) = 9`
#### 3.1.6. JSON
- JSON, JSON parse, JSON stringify.
##### Exercises:
- JSON stringify and parse will be used in the AJAX section.
#### 3.1.7. Others
- Hoisting.
- Strict mode.
### 3.2. Advances
#### 3.2.1. Storages
- Cookies
- Local storage.
#### 3.2.2. ECMAScript
- ECMAScript.
- ES5, ES6.
- Block scoping: let, const.
- New Array methods: map, filter, forEach, etc.
- New Object methods: assign, etc.
- Arrow function.
- Destructuring assignment.
- Object destructuring.
- Spread.
- Modules: import, export.
- Promise.
- Async, await.
- Template Literals.
- Generators.
- JS Transpiler: Babel.
#### 3.2.3. OOP
- JS Prototypes.
- JS Classes (ES6).
#### 3.2.4. AJAX
- Asynchronous JS.
- AJAX, XMLHttpRequest, fetch API.
#### 3.2.5. JavaScript frameworks
JS frameworks: Jquery, React.js, Angular.js, Vue.js, Jquery, etc.
Node.js.
Web bundlers: Browserify, Webpack, Parcel.
#### 3.2.6. Advanced concepts
- JS Closure.
- JS Garbage collection.
- JS Web Worker.
- JS Event loop.
### 3.3. Quizzes
- What is JavaScript? Why do we need JavaScript?
- What is an interpreted language?
- Does JavaScript have any relationship with Java?
- What is the original name of JavaScript?
- Why does JavaScript have the asynchronous mechanism? What happens if we use asynchronous language?

## 4. OTHER IMPORTANT KNOWLEDGE
- OOP
- Functional programming.
- Testing: unit test, integration test.
- DNS.
- Internet protocol: HTTP, HTTPS, Web socket, FTP, SSH, MQTT, etc.
- Security:
- Cross-Origin Resource Sharing
- Content Security Policy
- XSS attack, DDOS attack, SQL injection, Session hijacking, etc.
- Cryptography: symmetric encryption, asymmetric encryption, SSL, hashing, SHA, HMAC, JWT,etc.
- Optimization techniques: lazy loading, async loading, prefetch, cache, compression, minification, CDN, etc.

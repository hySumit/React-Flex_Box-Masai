
## REACT DOCUMENTATION

#### It is a brief description of what React is.




### 1. What is React?

Answer- React is a JavaScript library for building user interfaces, the React framework uses Webpack to automatically compile React, JSX, and ES6 code while handling CSS file prefixes. it is a library rather than a language, the library first appeared in May 2013 and is now one of the most commonly used frontend libraries for web development.

### 2. Who made React?

Answer - React was created by Jordan Walke, a software engineer at Meta, who released an early prototype of React called "FaxJS".


### 3. What is Babel?

Answer - Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.
Here is the Example .

![babel](https://github.com/hySumit/React-Flex_Box-Masai/assets/112721086/bcc38d82-2b2e-4a53-a3dd-b2668ca9f611)


### 4. How does Babel convert html code in React into valid code?
Answer - Babel is a key tool that can translate JSX syntax, which is used to create HTML-like code in React components, into valid JavaScript code that can be executed in preferred browsers. By converting the JSX code into JavaScript functions that return the same HTML-like structures.

![transformation](https://github.com/hySumit/React-Flex_Box-Masai/assets/112721086/673f7d65-b91f-408e-875f-85974df308de)

### 5. What is ReactDOM used for? Write an example?

Answer - 
ReactDOM is a package in the React library that provides DOM-specific methods for rendering React components. It acts as a bridge between React's virtual DOM and the actual DOM in a web page.

![example](https://github.com/hySumit/React-Flex_Box-Masai/assets/112721086/2b41da8b-19db-47f9-ba17-1b51f8eefaad)

### 6. What are the packages that you need to import for react to work with?

Answer - To work with react we need 2 packages to import or link its CDN to our Documentation.

1. React: This is the core library for building user interfaces in React.
2. ReactDOM: This package provides methods for interacting with the DOM in React, like rendering components.

### 7. How do you add react to a web application?
Answer - For adding react in our web application we must need node and npm in our system. 
And we need to follow these steps :-
1. Set Up Your Development Environment.
2. Create a New React Application:
The easiest way to start a new React project is by using create-react-app, a tool that sets up a new React project with a sensible default configuration.
Open your terminal and run the following command:

``` 
npx create-react-app my-react-app
```
3. Navigate to the Project Directory

```
cd my-react-app
```
4. Run the Development Server

```
npm start
```

### 8. What is React.createElement?

Answer - ```ReactDOM.createRoot()``` creates a root node where your React elements will live.
it is a important function in React that is used when we compile jsx code into javacsript by using babel.


### 9. What are the three properties that createElement accept?

Answer - There are 3 main properties that createElement accepts : 
1. Type or Element - it can be a string representing an HTML tag name example-, 'div', 'span' etc.
2. Props or Properties - An object containing the properties or attributes of the React element. These properties include things like className, style, and any other custom properties that you want to pass to the component
3. The child elements or content that will be nested within the created element. Children can be strings, other React elements, or arrays of React elements

### 10. What is the meaning of render and root?

Answer - React "render" and React "root" refer to key concepts related to displaying and updating the user interface.

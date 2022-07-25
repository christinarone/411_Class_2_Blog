# 411_Class_2_Blog
Discuss in words something you learned in class today or this week.
  I learned about classes and functions with React.
  
Why/when would you use a class-based component vs a functional component? What are the differences? What new alternatives are there?
  A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX).	A class component requires you to extend from React. Component and create a render function which returns a React element.

What is create-react-app? Dig into this.
  Create React App is a comfortable environment for learning React, and is the best way to start building a new single-page application in React. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production.

What is JSX?
  JSX is a React extension to the JavaScript language syntax which provides a way to structure component rendering using syntax familiar to many developers. It is similar in appearance to HTML. 

How does React work? From entry point to last child component? How?
  React uses a declarative paradigm that makes it easier to reason about your application and aims to be both efficient and flexible. It designs simple views for each state in your application, and React will efficiently update and render just the right component when your data changes. React does batch updates.

How does the virtual DOM work in React? Explain in detail.
  In summary, Virtual DOM in React solves the issue with updating unnecessary objects. When you try to update the DOM in react, the virtual DOM gets compared to what it looked like before you updated it, and React figures out which objects have changed. Then the changed objects get updated on real DOM.

Which (if there is) node library method could you use to solve the algorithm problem you solved last night in your pre-homework?
  I think the best library to use for this is Puppeteer.

What’s the difference between a React Element and a React Component?
  A React Element is what gets returned from components. It's an object that virtually describes the DOM nodes that a component represents. With a function component, this element is the object that the function returns. With a class component, the element is the object that the component's render function returns.

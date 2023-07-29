### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
It's a library, and because of components you can reuse certain codes over and over again without having to repeatedly hardcode it. 

- What is Babel?

Babel is a JavaScript compiler that converts modern JavaScript code into a version compatible with all browsers.

- What is JSX?

It's a syntax extension to JavaScript.

- How is a Component created in React?

By creating a separate js file, where you write a function that accepts a prop and export it. Then you import in the main App file, and add the name of the component in a div with the < /> tags around it. 

- What are some difference between state and props?

Props are used to pass data from a parent component to a child component, while state is used to manage data within a component.

- What does "downward data flow" refer to in React?

It  refers to the passing of data and/or functions via props from parent to child components.

- What is a controlled component?

it's form data thata is controlled by the component's state

- What is an uncontrolled component?

it's form data thata is controlled by the component's state

- What is the purpose of the `key` prop when rendering a list of components?

To give an id to the data (to avoid an error on the console)

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

Because it relies on the array, which although it's unique, it can change, and is therefore unstable. 

- Describe useEffect.  What use cases is it used for in React components?

it's a hook that allows you to perform side effects to your component

- What does useRef do?  Does a change to a ref value cause a rerender of a component?

a hook that accepts one value and returns an object that has a special property current. And no.

- When would you use a ref? When wouldn't you use one?

When you want to change the value of a child component without using props. Don't use if you can use useState instead. 

- What is a custom hook in React? When would you want to write one?

A reusable function you design yourself. 

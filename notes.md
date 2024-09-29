## Important questions and their answers

1. Which file does the module bundler webpack expect to be its entry point ?
   - index.js
2. What does <React.StrictMode>...</React.StrictMode> do ?
   - During development it render the components twice in order to find certain bugs.
3. When problem or bug arises what solution developer use to find them ?
   - first of all make sure application is runnning.
   - Always work with [ESLint](https://eslint.org/) extension to help identify and fix issues in javascript code.
4. What are components in react ?
   - Components are the building block of use interface in react, it is piece of react that has it own data, logic and appearance.
5. What are the rules that we must remember when we use components as function ?
   - first one it must start with uppercase letter
   - it must return some markup in form of JSX or null.
   - always declare components on top level, never nest them.
6. What is JSX ?
   - JSX is declarative syntax to describe what components look like and how they work, also they are extension of JS that allows to embed JS, CSS and react componenets into HTML
7. Which tool is used to convert JSX back to HTML ?
   - Babel
8. Why react is declarative in nature ?
   - React is declarative in nature because we use JSX to tell react what we want to see on the screen but not how to achieve it step by step (then that will be imperative)
9. Why HTML and JS are colocated in components in react ?
   - HTML and JS are colocated because things that change together should be located as close as possible together i.e components formation.
10. What is separation of concern in react ?
    - Separation of concern is transformation of one technology per file to one components per file.
11. Which tool in create-react-app responsible for injecting css in application when imported ?
    - Webpack
12. What are props in react ?
    - Props is how we pass data between components mainly from parent component to child components i.e one way data flow.
    - With props, parent components control how child components look and work.
    - Anthing can be passed as props, single values, arrays, objects, function, other components.
    - Props are immutable, they are read only.
13. How state is different from props ?
    - Props are data coming from outside, and can be only updated by the parent element while states are internal data that can be updated by the componenets logic.
14. Name framework which has two way data flow ?
    - Angular, from parent to child components and vice-versa.
15. Why one-way data flow is important ?
    - make applications more predictable and easier to understand.
    - makes application easy to debug.
16. What is mean by rendering a list ?
    - Rendering a list means when we have an array and we want to create one component for each element of the array.
17. What is key is react ?
    -key is basically a prop that is internal to react which is needed for some performance optimization.
18. What must me keep in mind while doing conditional rendering with &&?
    - React not render truthy or falsy values, it only render 0.
19. What is react fragments ?
    - React fragments allow to group some elements without leaving any trace in the HTML tree so in the DOM.


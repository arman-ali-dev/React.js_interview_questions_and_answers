# 54 ReactJS Interview Questions and Answers

**1. What is React?**
React is a JavaScript library for building user interfaces. It allows you to create reusable components that manage their own state and efficiently update the UI.

**2. What are Components in React?**
Components are the building blocks of React applications. They are reusable pieces of code that encapsulate functionality and UI.

**3. Explain JSX in React.**
JSX (JavaScript XML) is a syntax extension that lets you write HTML-like structures within your JavaScript code.

**4. Explain the concept of the Virtual DOM.**
The Virtual DOM is a concept implemented in React that provides a programming API like a lightweight copy of the actual DOM.

**5. Distinguish between a Class component and a Functional component.**
Class components extend from `React.Component` and can manage state and lifecycle methods. Functional components are simpler and use hooks like `useState` for state.

**6. How do you create a React component?**
You can create components using either class-based syntax or functional syntax. Functional components use functions and JSX, while class-based use ES6 classes.

**7. What are Props in React?**
Props are read-only data passed from parent to child components to customize and render dynamic content.

**8. What's the difference between Props and State in React?**
Props are read-only and passed from parent to child. State is managed within the component and can change over time.

**9. What does the render() method do in React components?**
The render() method in class components returns the UI output for that component based on props and state.

**10. What are keys in React and why are they important?**
Keys are unique identifiers used in lists to help React track which items have changed, improving performance.

**11. What is an event in React?**
Events in React are wrapped in the SyntheticEvent system to provide cross-browser consistency for user interactions.

**12. How do you handle events in React?**
Use event handlers like `onClick` with function references to respond to user interactions.

**13. What is a stateful component?**
A stateful component manages and stores state internally using `this.state` in classes or `useState` in functions.

**14. What is a stateless component?**
A stateless component does not manage internal state; it renders UI based on props alone.

**15. How do you pass data between components in React?**
Data is passed from parent to child components using props.

**16. What are controlled components?**
Controlled components are form inputs whose value is controlled by React state.

**17. How do you update the state of a component?**
Use `setState` in class components or the updater function from `useState` in functional components.

**18. What is the significance of the componentDidMount lifecycle method?**
It's called after the component is mounted and is ideal for API calls and DOM interactions.

**19. Explain the purpose of the useState hook.**
`useState` allows functional components to manage local state.

**20. What is the useEffect hook and how is it used?**
`useEffect` handles side effects in functional components like fetching data or updating the DOM.

**21. What are higher-order components?**
Higher-order components are functions that take a component and return a new component with added functionality.

**22. Explain the lifecycle of a React component.**
It has three phases: mounting, updating, and unmounting. Lifecycle methods help perform actions during these phases.

**23. How can you handle forms in React?**
Use controlled components by managing form values with component state.

**24. What is lifting state up in React?**
Lifting state up means moving state to a common ancestor so it can be shared among child components.

**25. How does React implement the re-rendering of components?**
React compares the virtual DOM before and after updates, and applies minimal changes to the real DOM.

**26. What are controlled components?**
Components whose input values are controlled by React state.

**27. What are uncontrolled components?**
Components that store their own state internally and use refs to access DOM values.

**28. Explain the concept of virtual DOM and how it differs from real DOM.**
The virtual DOM is a lightweight copy of the real DOM used to optimize UI updates.

**29. How do you optimize performance in a React application?**
Use `React.memo`, code-splitting, lazy loading, and avoid unnecessary re-renders.

**30. What is the context API?**
Context API allows sharing global data like theme, user info, without prop drilling.

**31. How do you use refs in React?**
Refs are created using `React.createRef()` and can access DOM nodes directly.

**32. Explain forward refs in React.**
Forward refs allow a parent to pass a ref to a child component.

**33. What are synthetic events in React?**
Synthetic events are cross-browser wrappers around native events.

**34. How do you implement error handling in React components?**
Use error boundaries to catch and handle JavaScript errors in the UI.

**35. What are portals in React?**
Portals render children into a DOM node outside of the parent component hierarchy.

**36. How does React Router work?**
React Router handles routing in single-page apps by changing the component based on the URL.

**37. What is the difference between React Router and traditional routing?**
React Router uses client-side routing, while traditional routing involves full page reloads.

**38. How do you implement code-splitting in React?**
Use `React.lazy()` and `Suspense` to load components on demand.

**39. What are the different ways to manage State in a React application?**
Use local state (`useState`), global state (Redux/Context), server state (React Query), and URL state (React Router).

**40. How do you handle side effects in React components?**
Use the `useEffect` hook for operations like API calls or subscriptions.

**41. Explain the concept of hooks in React. What problems do they solve?**
Hooks allow using state and lifecycle in functional components, improving code reusability and readability.

**42. How would you implement global state management in React without using external libraries?**
Use Context API to share global state across components.

**43. What is React Fiber?**
React Fiber is the new reconciliation engine in React that enables incremental rendering.

**44. How do you handle server-side rendering with React?**
Use frameworks like Next.js for rendering React components on the server.

**45. What are the common performance issues in React applications? How do you troubleshoot them?**
Issues include unnecessary re-renders and large virtual DOM diffs. Use `React.memo`, split components, and analyze with DevTools.

**46. How do you secure a React application?**
Sanitize input, use HTTPS, and implement proper authentication and authorization.

**47. What are the pros and cons of using Redux?**
Pros: centralized state, predictability. Cons: complex setup and boilerplate.

**48. How do you integrate TypeScript with React?**
Use TypeScript by creating `.tsx` files and defining prop and state types.

**49. Explain the main principles of Redux.**
Single source of truth, state is read-only, changes via pure functions.

**50. How do you handle asynchronous actions in Redux?**
Use middleware like Redux Thunk or Redux Saga.

**51. What is React Suspense and how do you use it?**
React Suspense allows lazy loading with a fallback UI for components that are not ready.

**52. How do you test React components?**
Use Jest and React Testing Library to write unit and integration tests.

**53. What is the use of static type checking in React?**
Static typing with TypeScript catches errors early and improves maintainability.

**54. Explain the role of immutability in React.**
Immutability helps with predictable state updates and optimization in React.


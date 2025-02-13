# Unnecessary useEffect re-renders in React component
This repository demonstrates a common React performance issue caused by using the `useEffect` hook without proper dependency management.
The `useEffect` hook in the `MyComponent` component runs after every render, leading to performance degradation and excessive console logging.
The solution shows how to properly use the `useEffect` hook with a dependency array to control when the effect runs.
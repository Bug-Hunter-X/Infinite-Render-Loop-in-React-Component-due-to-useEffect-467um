# Infinite Render Loop in React Component

This repository demonstrates a common React bug: an infinite render loop caused by an incorrectly placed `useEffect` hook. The `useEffect` hook in the original `MyComponent` runs after every render, causing the component to re-render infinitely.  The solution demonstrates how to fix this by adding a dependency array to `useEffect`.
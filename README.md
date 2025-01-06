# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook and its dependency array.  The code in `bug.js` shows an example of an infinite loop caused by incorrectly managing the interval within `useEffect`.

The solution provided in `bugSolution.js` corrects the issue by including the count state in the dependency array to ensure the cleanup function is called appropriately.
# React 19 useState Hook Issue

This repository demonstrates a bug encountered with the `useState` hook in React 19 where the state update doesn't seem to reflect immediately in the component's rendering, and the console log shows the previous state value.  The issue is resolved by using a functional update within the `setCount` function.
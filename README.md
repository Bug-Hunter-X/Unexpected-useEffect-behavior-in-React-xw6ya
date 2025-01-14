# React useEffect Bug

This repository demonstrates a common error when using the `useEffect` hook in React. The bug stems from a misunderstanding of how the dependency array works, leading to unexpected behavior.

## Bug Description
The `useEffect` hook is intended to perform side effects after a render. However, if the dependency array is incorrect, side effects can occur at unexpected times and lead to performance issues.  This specific example shows an `useEffect` that always runs, even though it's intended to only run once.
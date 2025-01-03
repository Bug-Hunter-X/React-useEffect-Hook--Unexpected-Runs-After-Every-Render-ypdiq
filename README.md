# React useEffect Hook: Unexpected Runs After Every Render

This repository demonstrates a common issue with React's `useEffect` hook where it runs after every render, even the initial one. This might lead to unnecessary re-renders or unwanted side effects.

## Problem

The `useEffect` hook, when not carefully managed, can run more often than intended, leading to performance problems and unexpected behavior.  The provided example illustrates this.

## Solution

The solution involves using the optional dependency array in `useEffect` to control when the effect runs. By specifying dependencies, the effect is only executed when those dependencies change.

## How to run

1. Clone this repository: `git clone https://github.com/<your_username>/react-useEffect-problem.git`
2. Navigate to the repository's directory: `cd react-useEffect-problem`
3. Install dependencies: `npm install`
4. Run the app: `npm start`
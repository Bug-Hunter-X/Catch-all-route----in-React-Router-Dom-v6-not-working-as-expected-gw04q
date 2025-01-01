# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes, but it's not behaving as expected in this specific example.  The solution provided addresses this issue.

## Problem

The `App.js` file contains a standard React Router setup. However, the catch-all route (`/*`) doesn't correctly catch unmatched routes.  This results in unexpected behavior when navigating to non-existent routes. 

## Solution

The `AppSolution.js` file shows a corrected implementation that fixes the problem.  The key is ensuring that the catch all route is at the end.
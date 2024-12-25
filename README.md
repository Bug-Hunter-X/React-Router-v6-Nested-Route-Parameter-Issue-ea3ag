# React Router v6 Nested Route Parameter Issue

This repository demonstrates a common issue encountered when using nested routes and parameters in React Router v6. The problem arises when trying to access a nested route parameter within a parent route that also has a path defined.  The solution shows how to resolve this issue using a more specific path for the nested route.

## Problem

The provided example shows a simple application with three routes: Home, About, and Contact. The Contact route has a nested route for detailed information.  However, the nested route parameter ':id' does not work correctly causing the ContactDetail component to never render.

## Solution

The solution refactors the nested route to use a more specific path, avoiding the conflict with the parent route. This ensures that the parameter is correctly matched and the nested component is rendered.
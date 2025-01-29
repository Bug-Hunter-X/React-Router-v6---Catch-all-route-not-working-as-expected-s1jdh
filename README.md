# React Router v6 Catch-all Route Issue

This repository demonstrates a problem with the catch-all route (`<Route path="*" ... />`) in React Router v6.  The catch-all route is intended to handle any URL that doesn't match other defined routes, but in this instance, it's not working correctly.

## Problem

When navigating to a non-existent route, the `NotFound` component, designed to handle such cases, is not rendered. This leads to unexpected behavior, leaving the user with a blank screen or a default React Router error message.

## Solution

The solution involves ensuring the catch-all route is correctly placed within the routes structure, as well as a possible double-check of the path being used for navigation.
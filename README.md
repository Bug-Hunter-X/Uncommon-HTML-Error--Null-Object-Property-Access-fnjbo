# Uncommon HTML Bug: Null Object Property Access

This repository demonstrates an uncommon bug in HTML that can occur when accessing properties of objects that might be null. This often occurs when using JavaScript within HTML to manipulate the DOM.

## Bug Description
The bug arises from attempting to access a property of an object before verifying that the object itself is not null. This usually results in a `TypeError` in JavaScript.

## Solution
The solution involves adding a null check before accessing properties to handle the case where the object might be null.  Always check for null or undefined values before accessing their properties to prevent such errors.
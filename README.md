# Uncommon HTML Bug: Incorrect Element Selection
This repository demonstrates a subtle bug related to HTML element selection and modification using JavaScript.
The bug arises from the incorrect usage of `document.getElementByTagName()`.  This method returns a NodeList (similar to an array), not a single element, which can lead to unexpected behavior when attempting operations like modifying `innerText`.
The solution highlights the correct way to select and manipulate elements based on different criteria to achieve the intended behavior.

## Bug
The `bug.html` file contains the erroneous code that fails to change the innerText because of wrong element selection. 

## Solution
The `bugSolution.html` shows the corrected code, demonstrating how to properly select elements and modify their `innerText` using the appropriate DOM manipulation techniques.
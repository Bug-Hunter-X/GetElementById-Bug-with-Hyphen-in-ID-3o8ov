# getElementById Bug with Hyphen in ID

This repository demonstrates a common, yet easily missed, error when using `document.getElementById()` in JavaScript to select HTML elements.

The bug occurs when an element's ID contains a hyphen (-) and the JavaScript code does not accurately match the ID.

## Bug
The `bug.html` file contains an HTML div with the ID `myDiv`. The JavaScript code attempts to select the element using `document.getElementById('my-div')`. This is incorrect because the ID in the HTML and the ID in JavaScript do not match.

## Solution
The `bugSolution.html` file provides the corrected code, ensuring the IDs match correctly.
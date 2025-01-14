# Uncommon HTML Bug: getElementById Typo

This repository demonstrates a subtle bug that can occur in HTML/JavaScript code. The bug involves a simple typo in the `getElementById` method, leading to a silent failure without any error messages.

## The Bug

The `bug.html` file contains a typo in the JavaScript code. Instead of using `document.getElementById`, it uses `document.getElementByIdx`, which is incorrect. This results in the script not finding the element, and therefore not hiding the div.  This is a silent error; no error messages are thrown.

## The Solution

The `bugSolution.html` file corrects the typo. By using the correct `document.getElementById` method, the script now correctly hides the div element.

## How to reproduce:
1. Open the `bug.html` file in your browser.
2. Notice that the text within the div is still visible, even though the script is attempting to hide it.
3. Open the `bugSolution.html` file. The text should be hidden, demonstrating the corrected code.

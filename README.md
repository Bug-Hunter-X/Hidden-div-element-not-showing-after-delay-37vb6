# Hidden Div Element Not Showing After Delay

This repository demonstrates an uncommon bug related to showing a hidden div element in HTML after a delay. The issue arises from an incorrect or incomplete use of the `display` property for styling.

The `bug.html` file shows the problem.  The `bugSolution.html` file provides a corrected version.

## Bug Description
The primary issue involves using the `style.display = "hidden"` to initially hide the div and then using `style.display = "block"` to show the div after a 3-second delay. In some cases, particularly with complex layouts or transitions, the element might not reappear.

## Solution
The solution avoids potential issues by using a class to manage visibility. Using a class provides better compatibility and separation of concerns.
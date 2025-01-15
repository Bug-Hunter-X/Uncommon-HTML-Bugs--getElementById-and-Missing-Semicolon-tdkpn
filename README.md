# Uncommon HTML Bugs

This repository demonstrates two subtle but important HTML bugs:

1. **Incorrect getElementById usage:**  The code attempts to use getElementById with a variable but wrongly assumes it is directly accessing the HTML element when used with the variable elementId.
2. **Missing Semicolon:** The console.log statement lacks a terminating semicolon. While often tolerated by browsers, it is considered best practice to include semicolons.

The `bug.html` file contains the buggy code. The `bugSolution.html` file provides the corrected version.  This example highlights the importance of careful variable handling and consistent coding styles in HTML, even in seemingly simple contexts.
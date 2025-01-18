# CSS Specificity Gotcha: Unexpected Inheritance Behavior

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected inheritance behavior.  The problem arises when a more specific selector overrides a seemingly inherited style.  The `bug.css` file contains the problematic code, while `bugSolution.css` shows a solution to resolve the unexpected behavior.

## Problem Description

The issue lies in understanding how CSS specificity works in relation to inheritance. A child element normally inherits styles from its parent. However, when a more specific selector targets the child element directly, it overrides the inherited styles, even if the inherited styles seem logically more appropriate.

## Solution

The solution focuses on adjusting the CSS selector or style order to achieve the desired inheritance and color outcome.  The solution clarifies the selectors' specificity to resolve the inheritance issue.
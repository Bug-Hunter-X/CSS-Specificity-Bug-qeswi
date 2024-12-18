# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  The bug arises from conflicting style rules where the order and specificity of selectors lead to unexpected rendering.

The `bug.css` file shows the problematic code. The `solution.css` file provides a fix.

## Problem

The intended style is not applied due to the specificity of the selectors.  Understanding how CSS specificity works is crucial for debugging such issues.

## Solution

The solution uses more specific selectors or the `!important` flag (use cautiously) to override the conflicting style and ensure the intended styling is applied.
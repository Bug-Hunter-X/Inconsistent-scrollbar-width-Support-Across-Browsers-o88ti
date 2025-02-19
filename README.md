# Inconsistent scrollbar-width Support Across Browsers

This repository demonstrates an uncommon issue related to the `scrollbar-width` property in CSS. While many modern browsers support it, its lack of formal standardization leads to inconsistencies.

The `bug.css` file showcases the problematic code, while `bugSolution.css` provides a cross-browser compatible alternative.

## Problem

The `scrollbar-width` property, although widely adopted, isn't part of any official CSS specification.  This means that its behavior may differ significantly across browsers, potentially causing unexpected display issues.

## Solution

The solution involves using a combination of techniques to customize scrollbars in a more consistent manner, ensuring that they appear as intended across different browser environments.
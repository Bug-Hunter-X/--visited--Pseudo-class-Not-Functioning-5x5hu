# :visited Pseudo-class Issue in CSS

This repository demonstrates a problem with the CSS `:visited` pseudo-class not correctly styling visited links.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides a corrected version.  This might be due to issues with specificity, incorrect selector usage, or browser-specific behaviors related to the `:visited` selector.

## Problem

The `:visited` selector should style links that have already been visited by the user. However, in the original CSS, this styling does not occur.  This could be caused by incorrect implementation. 

## Solution

The solution demonstrates a way to correctly use the `:visited` pseudo-class to target visited links and apply the desired style.  Specifically, the solution likely involves ensuring that the `:visited` pseudo-class has appropriate specificity and is applied to the correct elements. 
# CSS Specificity Bug
This repository demonstrates a common CSS issue related to specificity.  A more specific selector is unexpectedly overridden by a less specific selector, resulting in unintended styling. The `bug.css` file contains the problematic code, and `bugSolution.css` provides a corrected version.

## Problem
The original CSS (`bug.css`) demonstrates the issue where a specific selector (.container p) is overridden by a less specific selector (p). This causes unexpected styling of the paragraph elements within the container.

## Solution
The solution (`bugSolution.css`) addresses the issue by adjusting the specificity of the selectors or using the !important flag (as a last resort), ensuring that the intended styles are applied correctly.  In general, it's best to avoid relying on !important, but it can be helpful in rare and complex situations.
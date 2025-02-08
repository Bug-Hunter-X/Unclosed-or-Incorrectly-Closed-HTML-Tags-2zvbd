# Unclosed or Incorrectly Closed HTML Tags

This repository demonstrates a common HTML error: improper use of closing tags.  Specifically, it highlights the issues that can arise from incorrectly closing self-closing tags (like `<br>`) or failing to close block-level elements (`<div>`, `<p>`).  The `bug.html` file showcases the erroneous code, while `bugSolution.html` provides the corrected version.

**Problem:**

Unclosed or incorrectly closed tags can lead to unexpected layout and rendering inconsistencies across different browsers.  HTML validators will also flag these errors.

**Solution:**

Ensure all block-level elements are properly closed with their corresponding closing tags.  Avoid closing self-closing tags.  Use a HTML validator to identify such errors. 
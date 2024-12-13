# Uncommon HTML Bug: Non-Standard Attribute Usage

This repository demonstrates a potential issue arising from the use of non-standard attributes in HTML elements.  While seemingly functional, these attributes may cause inconsistencies in how different browsers and rendering engines interpret and render your HTML, potentially leading to unexpected behavior or failures.

The `bug.html` file showcases the problematic HTML, using a non-standard attribute `data-test`. The solution, presented in `bugSolution.html`, illustrates a better practice.  This practice uses standard attributes where possible, improving cross-browser compatibility and maintainability.  Standard attributes provide more consistent behavior across rendering engines.
# 584-HTML-intro
# HTML Elements Implementation

## Overview

This project demonstrates the implementation of various HTML elements including headers and ordered lists with specific attributes.

## Elements Added

### Header Elements

I added the following header elements to create a hierarchical structure:

- **`<h2>`** - Contains the text "this is a test for header 2"
- **`<h3>`** - Contains the text "also header 3 for fun"

### Text Hierarchy

The header elements follow this size hierarchy:
- `<h2>` text is smaller than `<h1>`
- `<h3>` text is smaller than `<h2>`

This creates a proper visual hierarchy where each subsequent header level is progressively smaller in size.

### Ordered List with Reversed Attribute

I implemented an ordered list (`<ol>`) with the `reversed` attribute, which counts down instead of up:

```html
<ol reversed>
  <li>counting down</li>
  <li>using the reversed attribute</li>  
  <li>with the ordered list element</li>
</ol>
```

Using the `reversed` attribute in the `<ol>` element, the list displays as:
1. **3.** counting down
2. **2.** using the reversed attribute  
3. **1.** with the ordered list element

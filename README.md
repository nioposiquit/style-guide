# Style Guide

### The most commonly used media queries

* min-width
* max-width
* min-height
* max-height
* orientation:portrait
* orientation:landscape

**Note:**
* min-width = browser window
* min-device-width = display screen for the device.

### Add max-width for larger devices

`.container {
   max-width: 62.5rem;
}`

**Note:**
Avoid using pixels to declare your breakpoints, since this creates a horizontal scrollbar when the user zooms in on your content. Instead of using pixels, use relative units, which allows browsers to adjust the design, based on the user’s zoom level.

### Breakpoint Guidelines

* Optimize the text for reading
* Use major device breakpoints, and address content with minor breakpoints
* Treat your website’s layout as an enhancement
* Use relative units like rem or em;

### Images

* Most images on the Web are 72 and 100 pixels per inch
* Add `width` and `height` attributes
* The attribute `alt` is important



## Source

[Advanced CSS Concepts](https://www.edx.org/course/advanced-css-concepts) a course on [edX](https://www.edx.org/) by [Microsoft](https://www.microsoft.com/)
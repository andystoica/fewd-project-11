# Performance_Optimization
Problem: Apply the skills learned for optimization of graphics, HTML, CSS, and JavaScript to take a poorly optimized site and reduce the total load size to under 1.3mb and total requests to less than 27. Students will need to analyze the assets they've been provided to see where optimizations can and need to be made, make those optimizations, and measure their success. Multiple analyzation, optimization, and measuring cycles may be required.

Solution:
* Converted all CSS files to Sass and compiled to a compressed single file
* Concatenated all JS files into a single minified file
* Replaced CSS fonts with Google fonts
* Replaced PNG Social Media Icons with embedded SVGs
* Rescaled logo to retina size
* Rescaled all images to a maximum width of 950px, except for the header images
* Reduced number of HTTP requests to 26
* Reduced data transfer to aprox. 1MB
* Automation performed in CodeKit

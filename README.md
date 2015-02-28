Website Performance Performance Optimization Portfolio Project

Steps to Improve Google PageSpeed Score
	- Inlined the necissary CSS into the HTML to prevent render blocking
	- Added media="print" to print.css tag
	- Loaded additional css with javascript
	- Added async attribute on JavaScript tags
	- Optimized images by resizing and compressing with http://jpeg-optimizer.com/
	- Also completed these steps to increase PageSpeed score on the additional pages
	- All pages score at least a 90 on PageSpeed

Steps taken to Improve FPS on pizza.html
	- Inlined css
	- Resized and compressed images 
	- Minified larger files such as js and css
	- Made some alterations to main.js
		- Moved sizeSwitcher() function outside of the function it was defined in
		- Placed the static values outside their "for" loops in changePizzaSizes() function, the "pizza append on page load" function, and updatePositions() function.

References
https://developers.google.com/
https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery#example
http://www.addthis.com/blog/2014/11/04/pagespeed-insights-removing-render-blocking-css/#.VPH2mbPF8pB
http://jpeg-optimizer.com/
https://htmlcompressor.com/compressor/
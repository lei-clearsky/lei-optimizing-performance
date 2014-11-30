<h1>Website Performance Optimization portfolio project</h1>

<p>Optimize the critical rendering path of an exisiting online portfolio for Pagespeed Insights score above 90 by applying the techniques in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).</p>


<h2>Following techniques are used to optimize the website:</h2>
<ul>
	<li>Images are compressed</li>
	<li>Add async tag to js source to avoid render blocking</li>
	<li>Use <a href ="https://github.com/typekit/webfontloader">Web Font Loader</a> to load fonts</li>
	<li>Inline CSS to <a href="https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery">optimize CSS delivery</a></li>
	<li>Two major issues are fixed in the views/js/main.js to achieve 60 frames per second</li>
	<li>CSS files are minified as no changes are made to the original files</li>
	<li>Note: for review purpose, js files are not minified</li>
</ul>

<h2>Test:</h2>
<p>Use <a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insights</a> to test following pages</p>
<ul>
	<li><a href="http://lei-clearsky.github.io/lei-optimizing-performance">index.html</a></li>
	<li><a href="http://lei-clearsky.github.io/lei-optimizing-performance/project-2048.html">project-2048.html</a></li>
	<li><a href="http://lei-clearsky.github.io/lei-optimizing-performance/project-webperf.html">project-webperf.html</a></li>
	<li><a href="http://lei-clearsky.github.io/lei-optimizing-performance/project-mobile.html">project-mobile.html</a></li>
	<li><a href="http://lei-clearsky.github.io/lei-optimizing-performance/views/pizza.html">pizza.html</a></li>
</ul>
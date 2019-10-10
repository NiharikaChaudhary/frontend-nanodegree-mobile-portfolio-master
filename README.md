## Website Performance Optimization portfolio project

View the Project in Working at: [Github repo hosted webpage] : nikkie95.github.io/

#### to open the project locally:
* click on the index.html file and open it using browser of your choice
* click on views the select pizza.html to view the page in browser choose to open with the choice of your own browser 

The Key Goal of this Project was to Optimize a Given Website As Much As Possible for Faster Rendering & to Achieve High PageSpeed Score.

#### PageSpeed Insights
* Desktop 94/100
* Mobile 93/100


#### in order to optimise tools used are:


* CSS Minifier
* JS Compress
* HTML Formatter
* Jpeg/Png compressor : tools for image-optimisations


#### to Optimize `index.html`

* used Optimized Images
* Minified JavaScript (async)
* Minified CSS
* Inline CSS styling
* Minified index.html
* used media="print" in <link href="css/print.css" rel="stylesheet" media="print">
 

#### to Optimize `pizza.html`

* Optimized Images
* Recorded timeline.
* Separated loops that caused Forced Synched Layout in Main.js
* Made changes in UpdatePosition() 
* replaced querySelector and querySelectorAll by getElementById/ClassName
* used var before loops
* calculated no. of pizzas to show according to screen size resoulution
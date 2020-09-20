# Read 12 

## Charts
1. What are the **Charts**?
 Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
 2. how to drow a line Chart: (1) create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

<canvas id="buyers" width="600" height="400"></canvas>. 
(2) write a script that will retrieve the context of the canvas.

3. other type of chrts: (1) Line chart. ![line chart](https://google.github.io/charts/flutter/example/line_charts/simple_full.png)
 (2) Pie chart ![pie](meta-chart.com/assets/images/pie/pie_percent.png)
  . (3) Bar Chart ![bar](https://themexpert.b-cdn.net/images/xdocs/quix/elements/bar-chart/barChart3.png)


### Installation
You can download the latest version of Chart.js from the GitHub releases or use a Chart.js CDN. Detailed installation instructions can be found on the installation page.




## Basic Usage of Canvas
some will think that the **canvas** tag is the same ad the img tag , but only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

## Applying styles and colors

* **Colors** : Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
* **Transparency:** In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
* **Line styles**:There are several properties which allow us to style lines. ( *like: Width, Cap, Join, Limit, Dash, DashOffset)
* **Gradients**: Just like any normal drawing program, we can fill and stroke shapes using linear and radial gradients. We create a CanvasGradient object by using one of the following methods. We can then assign this object to the fillStyle or strokeStyle properties.



  ## Drawing Text
  The canvas rendering context provides two methods to render text:
  * Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
  * 
 ### Styling text


* font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
* **textAlign = value**: 
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
* **textBaseline = value**:
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
* **direction = value**:
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.



[**Back**](https://naji-albatayneh.github.io/reading-notes)

# Canvas Element in HTML

- **In HTML5, we can use the element canvas to `draw charts` using the tag `<canvas>`.**

- **Canvas element can be styled just like any normal image element.**

- **Unlike the `<img>` element, the `<canvas>` element requires the closing tag `</canvas>`. If this tag is not present, the rest of the document would be considered the `fallback content` and wouldn't be displayed.**

- **Canvas `grid` is used to draw, where normally `1 unit` in the grid corresponds to `1 pixel` on the canvas. The `origin` of this grid is positioned in the `top left corner at coordinate (0,0)`. All elements are placed relative to this origin.**

- **We can draw `shapes` and `text` on canvas.**

- **`<canvas>` only supports two primitive shapes: `rectangles` and `paths` (lists of points connected by lines). All other shapes must be created by combining one or more paths.**

- **There are three functions that draw rectangles on the canvas:**
- `fillRect(x, y, width, height)` Draws a `filled rectangle`.
- `strokeRect(x, y, width, height)` Draws a `rectangular outline`.
- `clearRect(x, y, width, height)` Clears the specified rectangular area, making it `fully transparent`.

- **Each of these three functions takes the same parameters. `x and y specify the position` on the canvas (relative to the origin) of the top-left corner of the rectangle. `width and height provide the rectangle's size`.**

- **We can draw `different shapes by drawing paths`. The following are the functions used to perform these steps:**
- `beginPath()` Creates a `new path`. Once created, future drawing commands are directed into the path and used to build the path up.

- **Path methods are Methods to set different paths for objects.**
- `closePath()` Adds a straight line to the path, going to the start of the current sub-path.
- `stroke()` Draws the shape by stroking its outline.
- `fill()` Draws a solid shape by filling the path's content area. 

[Read More on Drawing Shapes in Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

________________________________________________________

# Chart.js API

- **`Chart.js` is a `JavaScript plugin` that uses HTML5 `canvas element` to draw a chart onto the page.**

- **In order to be able to use `Chart.js` we need to import the script using this `<script src="https://cdn.jsdelivr.net/npm/chart.js@2.8.0"></script>`, also we need to create a `canvas element` in our HTML document.**

- **We need to create our `data` to display it in a chart format. Data is an object that contains `labels` for the base of our chart and `datasets` to describe the values on the chart.**

- **`Chart.js` allow us to draw different types of charts such as, `Line`, `Bar`, `Pie`, `Radar`, etc. However, the data for each type might differ from another.**

- **We can `modify` several properties of the chart in `options:{...}`**

- **We can make `2d` or `3d` charts.**

[Read More on Chart.js](https://www.chartjs.org/)

________________________________________________________
##### Naji A. Albatayneh | Ph.D (IT) | Faculty of Computing and Informatics, Multimedia University, Cyberjaya, Selangor, Malaysia

###### Mobile: +60-143-473374 , +962-786-324328 | E-mail: naji.albatayneh@gmail.com

###### Let's Connect on [LinkedIn](https://www.linkedin.com/in/naji-a-albatayneh/) | [Github](https://github.com/naji-albatayneh) | [Facebook](https://web.facebook.com/naji.albatayneh/)

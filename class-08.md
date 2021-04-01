[**Back**](https://naji-albatayneh.github.io/reading-notes)

# Layout in CSS

- **start on a new line Examples include: `<h1>` `<p>` `<ul>` `<li>`.**

- **Inline elements flow in between surrounding text Examples include: `<img>` `<b>` `<i>`.**

- **Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element..**

- **CSS has the following positioning schemes that allow you to control the layout of a page: `normal flow`, `relative` positioning, and `absolute` positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the `float` property.**

- Normal flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
- Relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.
- Absolute Positioning: This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

- **To indicate where a box should be positioned, you may also need to use `box offset` properties to tell the browser how far from the `top or bottom and left or right` it should be placed. (You will meet these when we introduce the positioning schemes on the following pages).**

- **When you move any element from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.**


- **Normal flow: `position:static`.**

- **Relative flow: `position:relative`.**

- **Absolute flow: `position:absolute`.**

- **Fixed positioning: `position:fixed`.**

- **The `float property` allows you to take an element in `normal flow` and place it as far to the left or right of the containing element as possible.**

- **A lot of layouts place boxes next to each other. The `float property` is commonly used to achieve this.**

- **The clear property allows you to say that no element (within the same containing element) should touch the left or right and sides of a box. It can take the following values: `left`, `right`, `both`, or `none`.**

- **`Problem:` If a containing element only contains floated elements, some browsers will treat it as if it is zero pixels tall.**

- **Many web pages use `multiple columns` in their design. This is achieved by using a `<div>` element to represent each column. The following three CSS properties are used to position the columns next to each other:**
- `width`: This sets the width of the columns.
- `float`: This positions the columns next to each other.
- `margin`: This creates a gap between the columns.**

- **Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.**

- **Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.**

- **Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).**

- **Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.**

- **Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window.**

- **We can use Grid layout.**

- **We can use multiple stylesheets.**

________________________________________________________
##### Naji A. Albatayneh | Ph.D (IT) | Faculty of Computing and Informatics, Multimedia University, Cyberjaya, Selangor, Malaysia

###### Mobile: +60-143-473374 , +962-786-324328 | E-mail: naji.albatayneh@gmail.com

###### Let's Connect on [LinkedIn](https://www.linkedin.com/in/naji-a-albatayneh/) | [Github](https://github.com/naji-albatayneh) | [Facebook](https://web.facebook.com/naji.albatayneh/)

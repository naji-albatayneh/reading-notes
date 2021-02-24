[**Back**](https://naji-albatayneh.github.io/reading-notes)

# Transforms in CSS

- **`Transform property` introduce new techniques to `position`, `resize`, and `layout` elements.**

- **The transform property comes in two different settings, `two-dimensional` and `three-dimensional`. Each of these come with their own individual properties and values.**

- **The `syntax` of `transform` property is quite simple, including the transform `property` followed by the `value`. The value specifies the `transform type` followed by a `specific amount inside parentheses`.**

## 2D Transforms

- **2D Rotate**
- The rotate value provides the ability to rotate an element `from 0 to 360 degrees`. Using a `positive value will rotate an element clockwise`, and `using a negative value will rotate the element counterclockwise`. The `default point of rotation is the center of the element`, 50% 50%, both horizontally and vertically.
- Example: _`.box-1 {transform: rotate(20deg);}`_

- **2D Scale**
- Using the `scale value` within the transform property allows you to change the `appeared size` of an element. The `default scale value is 1`, therefore any value `between .99 and .01` makes an element appear `smaller` while any value `greater than or equal to 1.01` makes an element appear `larger`.**
- We can scale only the `height` or `width` of an element using the `scaleX` and `scaleY` values.
- Example1: _`.box-1 {transform: scale(.75);}`_
- Example2: _`.box-1 {transform: scaleY(1.15);}`_

- **2D Translate**
- The `translate value` works a bit like that of `relative positioning`, pushing and pulling an element in different directions `without interrupting the normal flow of the document`. Using the `translateX` value will change the position of an element on the `horizontal` axis while using the `translateY` value will change the position of an element on the `vertical` axis.
- Example: _`.box-1 {transform: translateX(-10px);}`_

- **2D Skew**
- `Skew` is used to `distort` elements on the horizontal axis, vertical axis, or both. Using the `skewX` value distorts an element on the `horizontal` axis while the `skewY` value distorts an element on the `vertical` axis. To distort an element on `both axes` the `skew` value is used, declaring the `x axis value first, followed by a comma, and then the y axis value`.
- Example: _`.box-1 {transform: skewX(5deg);}`_

- **We can combine multiple transforms.**
- Example: _`.box-1 {transform: skew(10deg, 20deg) translateX(20px);}`_

## 3D Transforms

- **Working with `3-dimensional` transforms are similar to 2-dimensional transforms but we use also the z axis, giving control of depth as well as length and width.**

[Read More on Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

________________________________________________________

# Transitions & Animations

- **`Transitions` allow us to `alter the appearance and behavior` of an element whenever a `state change occurs`, such as when it is `hovered over`, `focused on`, `active`, or `targeted`.**

- **`Animations` allow the `appearance and behavior` of an element to be `altered in multiple keyframes`. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.**

[Read More on Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

________________________________________________________
##### Naji A. Albatayneh | Ph.D (IT) | Faculty of Computing and Informatics, Multimedia University, Cyberjaya, Selangor, Malaysia

###### Mobile: +60-143-473374 , +962-786-324328 | E-mail: naji.albatayneh@gmail.com

###### Let's Connect on [LinkedIn](https://www.linkedin.com/in/naji-a-albatayneh/) | [Github](https://github.com/naji-albatayneh) | [Facebook](https://web.facebook.com/naji.albatayneh/)

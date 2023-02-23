# Class 14 Reading Notes

## [CSS Transforms](http://learn.shayhowe.com/advanced-html-css/css-transforms)

- The transform property comes in two different settings, two-dimensional and three-dimensional

- The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

- Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. 

- 2D Rotate: The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. 

- 2D Scale: Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

- It is possible to scale only the height or width of an element using the scaleX and scaleY values. The scaleX value will scale the width of an element while the scaleY value will scale the height of an element. To scale both the height and width of an element but at different sizes, the x and y axis values may be set simultaneously. To do so, use the scale transform declaring the x axis value first, followed by a comma, and then the y axis value.

- 2D Translate: The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

- 2D Skew: The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p

- Combining Transforms: It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time

## [CSS Transitions & Animations](http://learn.shayhowe.com/advanced-html-css/transitions-animations/)

- With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

- Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

- There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

- Transitional Property: The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

- Transitional Properties: It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. 

- Transition Duration: The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

## [8 simple CSS3 transitions that will wow your users](http://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

- Fade in: Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.Fade in effects are coded in two steps: first, you set the initial state; next, you set the change, for example on hover.

- Change color: Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. Now, we just set the div’s class to ​“color” and specify the color we want in our CSS

- Grow & Shrink: To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge. Set your div’s class to ​“grow” 

- Rotate elements: CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element. Give your div the class ​“rotate” 

- Square to circle: A really popular effect at the moment is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property. Give your div the class ​“circle” 

- 3D shadow: 3D shadows were frowned upon for a year or so, because they weren’t seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces. This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen. Give your div the class ​“threed” 

- Swing: Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration. In this case, we’ll first define a CSS animation in your styles. You’ll notice that due to implementation issues, we need to use @-webkit-keyframes as well as @keyframes

- Inset border: One of the hottest button styles right now is the ghost button; a button with no background and a heavy border. We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow. Give your div the class ​“border” 

### Things I want to know more about

- [Pure CSS Bounce Animation](http://codepen.io/dp_lewis/pen/gCfBv)

- [6 Buttons animated](http://codepen.io/dp_lewis/pen/gCfBv)

- [Pure CSS Bounce Animation](http://codepen.io/dp_lewis/pen/gCfBv)

- [CSS3 Animations: Keyframes](http://codepen.io/akshaychauhan/pen/oAfae)

- [404](http://codepen.io/kieranfivestars/pen/MYdQxX)

#### Link to my github portfolio [https://github.com/jenniferlidotson](https://github.com/jenniferlidotson)


# Transforms of css
The value specifies the transform type followed by a specific amount inside parentheses.
> -webkit-transform: scale(1.5);
 >    -moz-transform: scale(1.5);
  >     -o-transform: scale(1.5);
   >       transform: scale(1.5);
   transform property includes multiple vendor prefixes to gain the best support across all browsers. The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property

   ## 2d
   html
   ><fegure class="box-1">Box 1</fegure>
><fegure class="box-2">Box 2</fegure>

              
CSS
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
# scale
allows you to change the appeared size of an element. The default scale value is 1
>transform: scale(.75);
# translate
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
> transform: translateX(-10px);
# skew
is used to distort elements on the horizontal axis, vertical axis, or both.
> transform: skewX(5deg); 
# Combining Transforms
Using multiple transform declarations will not work, as each declaration will overwrite the one above it. The behavior in that case would be the same as if you were to set the height of an element numerous times.

## Transform Origin
it can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.
# Transitions & Animations
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes
The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes
 background: #2db34a;
    border-radius: 6px
    transition-property: background, border-radius;
    transition-duration: 1s;
    transition-timing-function: linear;
  }
  .box:hover {
    background: #ff7b29;
    border-radius: 50%;
  }

# duration
The duration in which a transition takes place is set using the transition-duration property
# timing
he transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration
# Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. As with all other transition properties, to delay numerous transitions, each delay can be declared as comma separated values.
# Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.On top of being able to set the number of times an animation repeats, you may also declare the direction an animation completes using the animation-direction property. Values for the animation-direction property include normal, reverse, alternate, and alternate-reverse.
# cool css style 
1. Fade in
Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.
2. Change color
Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. Now, we just set the div’s class to “color” and specify the color
3. Grow & Shrink
To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.
4. Rotate elements
CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element. Give your div the class “rotate”
[check this](https://codepen.io/retyui/pen/ByoaXV)
and this one so u understand keyframes
[css keyfram](https://codepen.io/akshaychauhan/pen/oAfae)
this to help u about the 404 [404](https://codepen.io/kieranfivestars/pen/MYdQxX)

this one for pure css [pure css](https://codepen.io/dp_lewis/pen/gCfBv)









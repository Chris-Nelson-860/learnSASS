# learnSASS
Small Project I am using to learn SASS

-SASS Allows you to create variables, which CSS allows but might not be supported in all browsers.  

-SASS Allows you to nest elements 

-SASS Allows you to write functions.

Tool that generates a css clip path bennettfeely.com:

The clip-path property allows you to make complex shapes in CSS by clipping an element to a basic shape (circle, ellipse, polygon, or inset), or to an SVG source.

CSS Animations and transitions are possible with two or more clip-path shapes with the same number of points.

Mixin's:  This is how you write media queryies with SASS.  
-First you set a variable with the breakpoint, in this cass the variable was named desktop and had a value of 840px.  
-Next, you write the  mixin which looks like a function.  Line 25 is where the mixin starts.  It includes the min-width property with the variable for the desktop breakpoint.
-Then just go to the area that you need to alter with the media query, use @include and the breakpoint name and then just put the stuff in.
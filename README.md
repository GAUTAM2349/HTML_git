# Real-estate-app
providing facility of seamless surfing for property search on internet.
Testing


_____________________________________

1> box-shadow : right bottom      /* -right = left ,  -bottom = up

* it's imp to give both right and bottom, if not needed then 0 but give

* although creating utility class is helping a lot to apply css in same page while creating component
  but, i couldn't create it for each div, because many div requires different css, maybe little different
   but different.
   
* also if i need to change sth in order of elements or content, i go their then come to css page...hectic 

* order of css for elements matter. Usually i create outer divs and then inner components.
  but inner components css i write after all main div, which create pbm. i need to go to very top to check main div 
   of a component.
   
* to give height in % parent container must have specific length.


*  The issue lies in how JavaScript code is being used inside JSX. JSX doesn't allow statements like for loops directly. Instead, you should use expressions, as JSX is designed to evaluate expressions (not statements). A for loop is a statement and can't be used directly in the {} braces.

To iterate in JSX, use array methods like .map() or precompute the required logic before returning JSX.


** see live preview during development so that u can encouter error point as soon as it occurs. Otherwise u will confuse where error is
   and in large projects it's nightmare.

* above normal and lower little border on element in a card div in a background color, imitates as if element is on top of it.

* pre-requisite :- divide you font- range,cards  into 4-5 class and never worry abt it's style

* text that are not so imp should disappear automaticall on smaller screen

* boxes creates pbm, classify them in 4-5 categories
* when screen become smaller their wrapping should be defined.

1> map fn
# Basic_jQuery_Practice
A Practice Repository for jQuery

(jQuery)[www.jquery.com]

add jquery through jsdelivr
```
<script
src = "https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.min.js"
></script>
```

you can also add jQuery locally by downloading the jQuery script and adding it to your project 

#### jQuery Syntax:
`$('selector).action()`


Code Examples:
- `$('p').click()` clicks on all p elements
- `$('#item1').click()` clicks on item1 id
- `$('.box').click()` clicks on all box class
- `$('p').click(function () {...})` runs the function when you click on any p element
- `$('p').click(function () {$('this').hide()})` hides the specific p element which has been clicked

three main types of selectors:
- element `$('p').click()`
- id `$('#second').click()`
- class `$('.odd').click()`

other selectors:
- `$('*').click()` clicks on all the elements
- `$('p.odd').click()` clicks on all the p elements with class odd
- `$('p:first').click()` clicks on the first p element

#### Events in jQuery

Mouse events
- click 
- dblclick 
- mouseenter 
- mouseleave

KeyboardEvent
- keypress 
- keydown 
- keyup

form events
- submit 
- change 
- focus 
- blur

document/window events
- load 
- resize 
- scroll 
- unload


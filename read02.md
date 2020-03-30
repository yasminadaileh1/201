# jQuery, Events, and The DOM

## jQuery 

it's a small, fast and rich javascript library and simpliz HTML and CSS animation. and it accessed by JavaScript .
example of the DOM in JavaScript and JQuery:
in javaScript --> var el = document.getElementById ('Id');
                  el.innerHTML = "Go";

but in JQuery --> $("#id").html("Go");

to start using jquery we need to add a script tag to the HTML file <script src= “https:code.jquery.com/jquery-3.1.1.js”></script>
Will we put the tag of script at the top of the page so it’s better to wait the HTML page to be loaded first so we need to put this in the top of jquery page:
$(document).ready(functiona(){
//here we write our code.
}
Or $(function){
here we write our code.
}); and this is a shortcut.

And this prevent any jquery code from running before The document is finished loading.

$("element").action()
$(".class").action()
$("#id").action()

.html : method Used to Change the HTML Contant of an element with the marKap.
 $("div .menu")  all dies with the menu Class 
 $(" P:first ")  the first P element
 $(" h1,P") all h1 element and all p element
 $("div P ") P elements that are descendlant of a div element
 $(" * ") all element of the DOM.
 $("h1:last ") 
 $("P:first-Child)~ all P tags that are the firat Childot thier parent.

 and there is so many selector based of the relation between the element.
 we have a lot of method we can use it with jquery like :

 * .attr() It’s method used to assigned attributes to HTML elements
 * .removeAttr() to remove attribute setting for an HTML elements
 * .text() get the content of the HTML element without the markup
 * .val() allows to get and set values of form fields
  
  
  Adding content without deleting the first content: 
 * .append() add to the end of the select element
 * .prepend() add to the beginning of the selected element
 * .after() interest content after the selected element
 * .before() interest content before the selected element

We can create a new element also:
$(“<p></p>”)
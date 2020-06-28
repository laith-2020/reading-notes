# welcome READ 02

# jQuery

## jQuery offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed. 


![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlIq9GgW5hGqiazsJBRA72lQCtJJv5Zmhu4CS_GdUWIs8fS3Zr&s)


``SELECT ELEMENTS PERFORM TASKS HANDLE EVENTS
It is simpler to access jQuery's methods let you jQuery includes methods
elements using jQuery's update the DOM tree, that allow you to attach
CSS-style selectors than it animate elements into event listeners to selected
is using DOM queries. The and out of view, and loop elements without having
selectors are also more through a set of elements, to write any tailback code
powerful and flexible. all in one line of code. to support older browsers.``


# A BASIC JQUERY EXAMPLE 




``The examples in this chapter revisit the list application used in
the previous two chapters, and they will use jQuery to update the content of the page``


``1. In order to use jQuery, the first
thing you need to do is include
the jQuery script in your page.
You can see that it is included
before the closing </body> tag``


``Once jQuery has been added
to the page, a second JavaScript
file is included that uses jQuery
selectors and methods to update
the content of the HTML page``

```<body>
<div i d="page">
<hl id=" header">List</hl>
<h2>Buy groceries</h2>
<ul>
<li id="one" class="hot"><em>fresh</em> figs</li>
<li id="two" class="hot">pine nuts</ li>
<li id="three" class="hot">honey</ li>
<l i id="four">balsamic vinegar</ li>
</ ul>
</div>
G) <script src="j s/ jquery-1 .11. 0 .js "></script>
@ <script src="js/basic-example.js"></scri pt>
</body>```


## GETTING ELEMENT
CONTENT 


### The • htm 1 () and • text () methods both retrieve and update the content
of elements. This page will focus on how to retrieve element content. To
learn how to update element content, see p316 

### . html()
When this method is used to retrieve information
from a jQuery selection, it retrieves only the HTML
inside the first element in the matched set, along
with any of its descendants. 

### . text()
When this method is used to retrieve the text from
a jQuery selection, it returns the content from every
element in the jQuery selection, along with the text
from any descendants. 

## GETTING AT CONTENT

### On this page you can see variations on how the . html() and . text()
methods are used on the same list (depending on whether <ul >or <l i >
elements are used in the selector). 
# read  03 

Javascript Templating Language and Engine— Mustache.js with Node and Express

![](https://miro.medium.com/max/1400/1*YpdR22sjaflf8VWppz-y3g.png)

## Javascript Templating

Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
The template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.


## Mustache

![](https://miro.medium.com/max/1400/1*P9q0tkeaRY2l1JOXaVKAig.png)

Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.
mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

## Mustache-Express

f you intend you use mustache with Node and Express, you can use mustache-express. Mustache Express lets you use Mustache and Express together easily.
To install:
With Yarn:


``Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn``

## In the above, we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Sherlynn”.


display
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

.container {
  display: flex; /* or inline-flex */
}
Note that CSS columns have no effect on a flex container.

flex-direction
the four possible values of flex-direction being shown: top to bottom, bottom to top, right to left, and left to right

This establishes the main-axis, thus defining the direction flex items are placed in the flex container. Flexbox is (aside from optional wrapping) a single-direction layout concept. Think of flex items as primarily laying out either in horizontal rows or vertical columns.

.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
row (default): left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top
flex-wrap
two rows of boxes, the first wrapping down onto the second
By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.

.container {
  flex-wrap: nowrap | wrap | wrap-reverse;
}
nowrap (default): all flex items will be on one line
wrap: flex items will wrap onto multiple lines, from top to bottom.
wrap-reverse: flex items will wrap onto multiple lines from bottom to top.
There are some visual demos of flex-wrap here.

flex-flow
This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

.container {
  flex-flow: column wrap;
}
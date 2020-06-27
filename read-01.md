# Welcome To READ 01

# SMACSS 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmjbHTw1EtjLPxji36Kg0pXGx3usksp9TtXEazXxy3G56zXM4&s)

<hr>

``“SMACSS is becoming one of the most useful contributions to front-end discussions in years” * I’ve been analyzing my process (and the process of those around me) and figuring out how best to structure code for projects on a larger scale. What I've found is a process that works equally well for sites small and large.Learn how to structure your CSS to allow for flexibility and maintainability as your project and your team grows.``

## SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS


# Responsive Web Design .

![](https://platinait.ca/blog/wp-content/uploads/2019/02/Responsive-Web-Design.jpeg)


## Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.

``The responsive web design term itself was coined, and largely developed, by Ethan Marcotte. A lot of what is covered in this lesson was first talked about by Ethan online and in his book Responsive Web Design, which is worth a read.``

 * Flexible Layouts 

 Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media. The first part, flexible layouts, is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly

 * Flexible Grid

Let’s see how this formula works inside of a two column layout. Below we have a parent division with the class of container wrapping both the section and aside elements. The goal is to have have the section on the left and the aside on the right, with equal margins between the two. Normally the markup and styles for this layout would look a bit like the following.


# What is “Float”?

![](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/web-layout.png?resize=540%2C240&ssl=1)

## Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”. Here is an example of that.


## In page layout programs, the boxes that hold the text can be told to honor the text wrap, or to ignore it. Ignoring the text wrap will allow the words to flow right over the image like it wasn’t even there. This is the difference between that image being part of the flow of the page (or not). Web design is very similar.


# What are floats used for?


## Aside from the simple example of wrapping text around images, floats can be used to create entire web layouts.


## Floats are also helpful for layout in smaller instances. Take for example this little area of a web page. If we use float for our little avatar image, when that image changes size the text in the box will reflow to accommodate:


<hr>


# Context 


## A block level element is as wide as the parent it’s inside (width: auto;). We can think of it as 100% wide. The wrapper for a grid probably don’t have much to do with semantics, it’s just a generic wrapper, so a div is fine.


# Columns


## Let’s start with a practical and common need: a main content area being 2/3 the width and a sidebar being 1/3 the width. We just make two column divs with appropriate class names.


# Clearing Context


## The parent element will collapse to zero height since it has only floated children. Let’s fix that by clearing it. These days all you need is this:

# Gutters

## The hardest part about grids is gutters. So far we’ve made our grid flexible by using percentages for widths. We could make the math all complicated and use percentages for gutters as well, but personally I don’t like percentage gutters anyway, I like fixed pixel size gutters. Plus, we’re trying to keep too much thinking out of this.



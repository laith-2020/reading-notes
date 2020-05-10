 # Headings and paragraph

 
## HTML has six "levels" of heading 

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSq1QyTNfMVGdIzE7W9teGxcSBPHrg7c4A8R30dkRJwDViI8itY&usqp=CAU)

 * < h1 >
 * < h2 > 
 * < h3 >
 * < h4 >
 * < h5 >
 * < h6 >

### <h1> is used for main headings
### <h2> is used for subheadings
### If there are further sections under the subheadings then the <h3> element is used, and so on...


# ParagraPHs

![img](https://i.ytimg.com/vi/n2KcEJ7-dtY/maxresdefault.jpg)

## < p > To create a paragraph, surround the words that make up the paragraph with an opening < p > tag and closing </ p> tag.

# Bold & iTalic

 * < b> By enclosing words in the tags < b> and </ b> we can make characters appear like **bold.**

 * < i> By enclosing words in the tags< i> and </ i> we can make characters appear like  *italic.*


## **< strong>**

### The use of the <strong> element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis. By default, browsers will show the contents of a <strong> element in **bold.** 


## *< em>*

### The < em> element indicates emphasis that subtly changes the meaning of a sentence.By default browsers will show the contents of an <em> element in italic.


<hr>

# Introduction to css


![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQt_1HgkAy6BTXQmJfrS81Mema1KeBrIARmYw_vIs04z1eyuM350w&s)

 **CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface**

 ## On the next page, you will see how CSS rules can also be placed in your HTML pages and we will discuss when you might want to do this
 
 # also there is Three way to do  a css design :

 * External 

 * Enternal 
 * Inline


<hr>

# inroduction to javascript 

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSaT8DpsOWn2MHzWDrOmTMRio2wXOVnQ2bzTfJz8Vp9wm-7Shci&s)

# Javascript

### ***JavaScript is the Programming Language for the Web.***
***JavaScript can update and change both HTML and CSS.***
***JavaScript can calculate, manipulate and validate data.***


## JavaScript Variables
### JavaScript variables are containers for storing data values.

- In this example, x, y, and z, are variables:

* Example
 `var x = 5;
 var y = 6;
 var z = x + y;`

# LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE

##  use JavaScript with a web page, you use the HTML `<script>` element to tell the browser it is coming across a `script` Its s re attribute tells people where  the JavaScript file is stored. 

    `<!DOCTYPE html>` 

    `<html>` 

    `<head>`

    `<title> Constructive &amp; Co.</ title>`

    `<link rel ="stylesheet" href="css/ cOl.css"/>`

    `</ head>`

    `<body>`

    `<hl>Constructive&amp;Co.</hl>`

    `<script src="js/ add-content.js"></ script> `

    `<p>For all orders and i nquiries please call <em>SSS-3344</ em></ p>`

    `</ body>`

    `</html>`


   ![image](https://img-a.udemycdn.com/course/750x422/851712_fc61_5.jpg)

  ### You may see JavaScript in the HTML between opening <script> and closing </script> tags (but it is better to put scripts in their own files). 

<hr>
  
  ![img](https://cdn.wallstreetmojo.com/wp-content/uploads/2019/03/Logical-operators-in-excel.png)
  
  # Comparison operators: evaluating Conditions

  ## USING COMPARISON OPERATORS  

  ### **At the most basic level, you can evaluate two variables using a comparison operator to return a t rue or f alse value.In this example, a user is taking a test, and the script tells the user whether they have passed this round of the test.The example starts by setting two variables: 1. pass to hold the pass mark 2. score to hold the users score**

  # Logical operators 

  ## Comparison operators usually return single calue of true or false .also logical operators allow you to compare the result of more than one comparison operator

  - && means and 
  - || means or 
  - ! means Not



![img](https://lh6.googleusercontent.com/proxy/V5lGYAHMEttHqJwzbxZSkKZ5qxZ2xOF0cxEXc0mClyX1g8mymrmzmGKrTpptqP1YdN-tc2CygZWpnxghgUWQtOAPlVeRreIJi0ZgJKOq5g)

  # Loops 

  ### the loops is check a condition , if the condition are true it will run a code inside the block , if not it will go out of it 

  ## THre Way to write a loop

  - For loop
  - While loop 
  - Do while loop 



![img](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)

### USING FOR LOOPS :

#### A for loop is often used to loop through the items in an array. 


![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/While-loop-diagram.svg/220px-While-loop-diagram.svg.png)

### USING WHILE LOOPS: 

####  while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.


![](https://media.geeksforgeeks.org/wp-content/uploads/20191118154342/do-while-Loop-GeeksforGeeks2.jpg)

### USING DO WHILE LOOPS  :

#### The key difference between a whi 1 e loop and a do whi 1e  loop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condition is met. 





# Introduction: Why good commit messages matter

## Style. Markup syntax, wrap margins, grammar, capitalization, punctuation. Spell these things out, remove the guesswork, and make it all as simple as possible. The end result will be a remarkably consistent log that’s not only a pleasure to read but that actually does get read on a regular basis.

## Content. What kind of information should the body of the commit message (if any) contain? What should it not contain?

 
 ## Metadata. How should issue tracking IDs, pull request numbers, etc. be referenced?

 
 # The seven rules of a great Git commit message
 

 1- Separate subject from body with a blank line

 2- Limit the subject line to 50 characters

 3- Capitalize the subject line

 4- Do not end the subject line with a period

 5- Use the imperative mood in the subject line

 6- Wrap the body at 72 characters

 7- Use the body to explain what and why vs. how

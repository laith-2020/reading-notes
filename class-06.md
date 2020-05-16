# welcome To READ 06 

## Understanding The Problem Domain Is The Hardest Part Of Programming

### There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

## Creat a object 

### CREATING· OBJECTS USING LITERAL NOTATION

**This example starts by creating an object using literal notation. 
This object is called hotel which represents a hotel called Quay with 40 rooms (25 of which have been booked)**

```var hotel = { name: 'Quay', rooms: 40, booked: 25, checkAvailability: function() { return this.rooms - this.booked; } } ; 
JAVASCRIPT 
var elName = document.getElementByld('hotelName'); elName.textContent =hotel .name; 
var elRooms = document.getElementByid{'rooms'); elRooms.textContent = hotel .checkAvailability();
```


## CREATING MORE OBJECT LITERALS

### Here you can see another object. Again it is called hote 1, but this time the model represents a different hotel. For a moment, imagine that this is a different page of the same travel website.The Park hotel is larger. It has 120 rooms and 77 of them are booked. The only things changing in the code are the values of the hot e 1 object's properties: • The name of the hotel • How many rooms it has • How many rooms are booked 

```var hotel = { name: 'Park', room s: 120, booked : 77, 
c03/js/object-l iteral2.js 
checkAvailabi lity: function() { return this.rooms - this.booked; } } ; 
var elName = document .getElementByid('hotelName'); elName.textContent =hotel .name; 
var el Rooms = document .getElementByid( 'rooms') ; e1  Rooms . text Content = hote 1 . checkAvai l ability();
```  


## The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 


### THE DOM TREE IS A MODEL OF A WEB PAGE 

**As a browser loads a web page,
 it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.**
 
BODY OF HTML PAGE 
<html> <body> <di v id="page"> <hl id="header">List</hl> <h2>Buy groceries</h2> <ul > <li id="one" class="hot"><em>fresh</em> figs</li> <li id="two" class="hot">pine nuts</l i> <l i id="three" class="hot">honey</li> <l i id="four">balsamic vinegar</l i> < / ul > <script src="js/l i st.js"></scri pt> < /div> </ body> </html >
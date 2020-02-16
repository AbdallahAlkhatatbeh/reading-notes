**This is bold text**
1. Go to Markdown on GitHub
   - then Styling text
     - use **  the text **
     
   ### To format code or text into its own distinct block, use triple backticks.
   
     Some basic Git commands are:
```
git status
git add
git commit
```

#### You can create an inline link by wrapping link text in brackets [ ],
### and then wrapping the URL in parentheses ( )
can you go to Markdown on GitHub at [GitHub Help](help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#headings/).

#### To create a heading, add one to six # symbols before your heading text.


#### The number of # you use will determine the size of the heading.


# The largest heading
##### ( #The largest heading)



# Task lists
###To create a task list, preface list items with a regular space character followed by [ ].


###To mark a task as complete, use [x].

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request




my github account [Abdallah Alkhatatbeh](https://github.com/AbdallahAlkhatatbeh).




### to add Images in github pages 


## Format:! [Alt Text] ( url  )

### with (.) in spaces 
##### Ex :
![GitHub Logo](https://www.3arrafni.com/wp-content/uploads/2018/10/GitHub-logo-2-imagen.jpg)



###You can create tables by assembling a list of words and dividing them with
###hyphens - (for the first row), and then separating each column with a pipe |:


format | Syntax guide
------------ | -------------
** bold ** | **bold**
*italic * | *italic*
_ You ** can ** combine them_ | _You **can** combine them_


## without spaces


# Lists


### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
  #### use * for  Unordered Lists
  
###  Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
   #### use 1. for  Ordered Lists
   
   
   
   
  ## Strikethrough
##### Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
   
   ~~this~~

   ## Dynamic web pages with JavaScript

HOW HTML, CSS,
& JAVASCRIPT FIT
TOGETHER  ??? 

- <html>
CONTENT LAYER
. html files 

- {css}
PRESENTATION LAYER
. css files 

- j avascri pt()
BEHAVIOR LAYER
.js files 

## CREATING A BASIC JAVASCRIPT 

JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day. 


var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3> ');



### PLACING THE SCRIPT IN THE PAGE 

You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files). 


## Basic javascript instructions : 

- STATEMENTS 
- COMMENTS 


#### WHAT IS A VARIABLE?  

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 


### DATA TYPES 

- NUMERIC DATA TYPE 
- STRING DATA TYPE 
- BOOLEAN DATA TYPE 



#### USING A VARIABLE TO STORE A NUMBER 

var price;
var quantity;
var total;
price = 5;
quantity = 14;
total = price * quantity;
c02/j s/numeri c-vari ab 1 e .j s
var el = document.getElementByid( ' cost ');
el .textContent = '$' +total; 

*** and other uses for A VARIABLE :




## comparison operators : 

Evaluating conditions 

== is equal to 
!= is not equal to

=== sirict equal to
!==  not sirict equal to

> greater rhan 
< less than 


### structuring comparison operators : 

(sorce >= pass)



## logical operators 

- logical && 
- logical or 
- logical not 

### USING LOGICAL AND 

ex : 


c04/js/ logical-and.js
var scorel = 8; II Round 1 score
var score2 = 8; II Round 2 score
var passl 6; II Round 1 pass mark
var pass2 = 6; II Round 2 pass mark
II Check whether user passed both rounds , store result in variable
var passBoth = (scorel >= passl) && (score2 >= pass2);
II Create message
var msg = 'Both rounds passed: ' + passBoth;
II Write the message i nto the page
var el = document.getElementBy!d( 'answer') ;
el.textContent = msg; 


## loops 

- for 
- while 
- do while 

ex : 
for (var i =0; i<10; i++)

^ initilization   ...> var i =0;
^ condition ...> i<10;
^ update ...> i++ 

## USING WHILE LOOPS 


This loop will continue to run
for as long as the condition in
the parentheses is true. That
condition is a counter indicating
that, as long as the variable
i remains less than 10, the
statements in the subsequent
code block should run


ex :
c04/ js/while-1oop.js JAVASCRIPT
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg; 

### the end 
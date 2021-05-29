# HTML 
# List
## There are three type of list in HTML 
Ordered lists 
creating list organized by numbers it used in a several places like when we need write the steps a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section number.
### How to create order list  
Using (ol) tag Each item in the list is placed between an opening li tag and a closing
Li tag. (The li stands for list item.)

## Unordered lists
are lists that begin with a bullet point
### How create unordered lists
 The unordered list is created with the ul
element. Each item in the list is placed between an opening li tag and a li closing
tag. (The li stands for list item.)
## Definition lists
 are made up of a set of terms along with the definitions for each of those terms.
### How create definition lists
The definition list is created with
the dl element and usually
consists of a series of terms and
their definitions.
Inside the dl element you will
usually see pairs of dt and
dd elements.
#### dt
This is used to contain the term
being defined (the definition
term).
#### dd
This is used to contain the
definition.
note  Be careful to know the difference between defined & definition.  
definition. Is have longe description of the word of defined 

## Nested Lists
You can put a second list inside
an li element to create a sublist or nested list.

# CSS 
# Boxes
## Control the dimensions of your boxes

Units to manage the  dimensions
1.Pixels

2.Percentages

3.Ems

**pixel** have been the most popular method because they allow designers to accurately control their size.
### Property to control the dimensions
min-width, max-width

min-height, max-height

## Overflow
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
### Valus to control Overflow
1.hidden
This property simply hides any
extra content that does not fit in
the box.

2.scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.
On the left, you can see two
boxes whose contents expand
beyond their set dimensions. The
first example has the overflow
property with a value of hidden.
The second example has the
overflow property with a value
of scroll.
The overflow property is
particularly handy because some
browsers allow users to adjust
the size of the text to appear as
large or as small as they want. If
the text is set too large then the
page can become an unreadable
mess. Hiding the overflow on
such boxes helps prevent items
overlapping on the page
## Border, Margin & Padding
Border
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.
Margin
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes.
Padding
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.

To change border width using border-width
seclor
To change border style using border-style
seclor
To change border color using border-color
seclor

There are alot of value to changr width style coler of boder and how to desgin margin and pandding  you can see ib book from 312-319

# 322-329
# JS 
A script is made up of a series of statements. Each
statement is like a step in a recipe. 
Variables are used to temporarily store pieces of
information used in the script. 
# Decisions and Loops
## DECISIONS
Using the results of
evaluations, you can
decide which path your
script should go down. 
## LOOPS
There are also many
occasions where you will
want to perform the same
set of steps repeatedly. 

Conditional statements allow your code to make
decisions about what to do next.
Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
Logical operators allow you to combine more than one
set of comparison operators.
if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.
switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
Data types can be coerced from one type to another.
All values evaluate to either truthy or falsy.
There are three types of loop: for, while, and
do ... while. Each repeats a set of statements


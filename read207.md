



# A block-level element 
always takes up the full width available
A block level element has a top and a bottom margin, whereas an inline element does not.

# An inline element 
does not start on a new line. An inline element only takes up as much width as necessary.
# z-index
If you want to control which
element sits on top, you can use
the z-index property. Its value
is a number, and the higher the
number the closer that element
is to the front. For example, an
element with a z-index of 10
will appear over the top of one
with a z-index of 5
# float
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
Anything else that sits inside
the containing element will
flow around the element that is
floated.
When you use the float
property, you should also use the
width property to indicate how
wide the floated element should
be. If you do not, results can be
inconsistent but the box is likely
to take up the full width of the
containing element (just like it
would in normal flow)
 **float using  to Place Elements Side-by-Side**

# clear
The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand sides of a box. It can take
the following values:

## left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.
## right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.
## both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
## none
Elements can touch either side.
# Screen Sizes
Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.
## Screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens.
## Fixed Width Layouts
Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels
## Liquid Layouts
Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.
# Images

To add an image into the page
you need to use an *img* tage
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
- src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. 
- alt
This provides a text description
of the image which describes the
image if you cannot see it.
- title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.



# color
## property
### color
- rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
 - hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
- color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
-hue
This is expressed as an angle
(between 0 and 360 degrees).
- saturation
This is expressed as a
percentage.
- lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
# Text 

## property 

### Text-transform 

The text-transform property
is used to change the case of
text giving it one of the following
values:

- uppercase value
This causes the text to appear
uppercase.
- lowercase value 
This causes the text to appear
lowercase.
- capitalize value
This causes the first letter of
each word to appear capitalized.

### text-decoration

The text-decoration property
allows you to specify the
following values:

- none
This removes any decoration
already applied to the text.
- underline
This adds a line underneath the
text.
- overline
This adds a line over the top of
the text.
- line-through
This adds a line through words.
blink
This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).

### line-height

s use for the
vertical space between lines of
text.

### letter-spacing

### word-spacing

### text-align

The text-align property allows
you to control the alignment of
text.

- left value
This indicates that the text
should be left-aligned.
- right value
This indicates that the text
should be right-aligned.
- center value
This allows you to center text.
- justify value
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box

### vertical-align

 It is more commonly used with
inline elements such as img,
em, or strong elements. 

### text-indent

The text-indent property
allows you to indent the first
line of text within an element.
The amount you want the line
indented by can be specified in
a number of ways but is usually
given in pixels or ems.

### text-shadow

The text-shadow property has
become commonly used despite
lacking support in all browsers. 




## pseudo-elements.
 
:first-letter, :first-line

You can specify different values
for the first letter or first line of
text inside an element using
:first-letter and
:first-line. 

## pseudoclasse

Browsers tend to show links
in blue with an underline by
default, and they will change
the color of links that have been
visited to help users know which
pages they have been to.

- :link
This allows you to set styles
for links that have not yet been
visited.
- :visited
This allows you to set styles for
links that have been clicked on.
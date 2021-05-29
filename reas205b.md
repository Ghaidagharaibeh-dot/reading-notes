# WHAT IS AN OBJECT? 
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 
![syntax](https://scontent.famm10-1.fna.fbcdn.net/v/t1.15752-9/192178312_186303120038217_1675128315092481908_n.png?_nc_cat=107&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeFPYNOGaSW15r6RpkpNNrLQYrNpsBtKm8Fis2mwG0qbwXmrHhHXeN_brPab6NfKvnDv2VyFpFmg266Z5KzMlSte&_nc_ohc=Bl-g_welHisAX_Vmcfg&_nc_ht=scontent.famm10-1.fna&oh=1a89cb604c871b1a65729e21fe9a881a&oe=60D742B3) 

# Document Object Model
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window. 

When the browser loads a web page, it
creates a model of the page in memory.
The DOM specifies the way in which the
browser should structure this model using
When the browser loads a web page, it
creates a model of the page in memory.
The DOM specifies the way in which the
browser should structure this model.
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes. 
### nodes 
- THE DOCUMENT NODE

Every element, attribute, and piece of text in the
HTML is represented by its own DOM node.
At the top of the tree a document node is added; it
represents the entire page 
When you access any element, attribute, or text
node, you navigate to it via the document node. It is
the starting point for all visits to the DOM tree.

- ELEMENT NODES
HTML elements describe the structure of an HTML
page. (The h l to h6 elements describe what
parts are headings; the <p> tags indicate where
paragraphs of text start and finish; and so on.)
To access the DOM tree, you start by looking for
elements. Once you find the element you want, then
you can access its text and attribute nodes if you
want to
- ATTRIBUTE NODES 
Attribute nodes are not children of the element thar
carries them; they are part of that element. Once
you access an element, there are specific JavaScript
methods and properties to read or change that
element's attributes. For example, it is common to
change the values of cl ass attributes to trigger new
CSS rules that affect their presentation. 
- TEXT NODES 
Text nodes cannot have children. If an element
contains text and another child element, the child
element is not a child of the text node but rather
a child of the containing element. (See the em
element on the first l i  item.) This illustrates how
the text node is always a new branch of the DO

## select an element 
You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax
by using document.getElementByld  theb the name of tage between bractes

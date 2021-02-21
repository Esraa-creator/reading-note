If a variable is part of an object, it is called a
property
If a function is part of an object, it is called a method.

Like variables and named functions,
properties and methods have a
name and a va lue. In an object,
that name is called a key

If you had two objects on the
same page, you would create
each one using the same
notation but store them in
variables with different names.

The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window

The DOM specifies the way in which the
browser should structure this model using
a DOM tree.

Application Programming Interface (API).
User interfaces let humans interact with
programs; APls let programs (and scripts)
talk to each other

Every element, attribute, and piece of text in the
HTML is represented by its own DOM node.
At the top of the tree a document node is added; it
represents the entire page

Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser.

ATTRIBUTE NODES

The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree.

TEXT NODES
Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node.

The terms elements and element nodes are used interchangeably
but when people say the DOM is working with an element,
it is actually working with a node that represents that element

DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

When a DOM method can return more than one element, it returns a
Nodelist (even if it only finds one matching element).

Nodelists look like arrays and are numbered like
arrays, but they are not ac tually arrays; they are a
type of object called a collection.

When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM.

The textCon tent property allows you to
collect or update just the text that is in the
containing element (and its children).

Using the i nnerHTML property, you can access
and amend the contents of an element,
including any child elements

Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.

An element node can contain multiple text nodes and
child elements that are siblings of each other.

In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

Browsers offer tools for viewing the DOM tree .
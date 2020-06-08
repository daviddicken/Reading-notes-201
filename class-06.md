# Read: 06 - JS Object Literals; The DOM

### Objects:
* Objects group together sets of variables and functions.
* A variable in a object is called a property
* A function in a object is called a method

### DOM - Document Object Model
* The DOM specifies how browsers should create a model of an html page and how JS can access and update the content
* getElementById(); finds a element with a named ID
* getElements will always return a nodelist even if only one mathing node is found
* Nodes are parent nodes, child nodes, sibling nodes, ect
* previousSibling, nextSibling, firstChild, lastChild are used to travere the DOM
* Use nodeValue to get the content of a node.
example: document.getElementById('one').firstChild.nextSibling.nodeValue
* createElement() creates a new element node
* createTextNode() creates a new text node
* appendChild() adds your new node to the DOM tree
* To remove a element you need to 1) store the element to be removed in a variable 2) store the parent of that element in a variable 3) use the removeChild() method to remove element you selected
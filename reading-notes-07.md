# Reading 07

## HTML Tables

Tables in html contain rows and columns like any table. The best to conceptualize them is to think of each row as having its own number of columns, i.e. cells. Within angle brackets is 'table' for the whole table element, 'tr' for a row, 'td' for the cells (or columns), and 'th' which is like tr but for the headers.

To span across columns, use the 'colspan="some number"' attribute. For spanning across multiple rows, use the 'rowspan="some number"' attribute.

Tables can also be broken up into the 'thead', 'tbody', and 'tfoot' to further distiguish the different parts of the table. Other attributes that can be used are width, cellpadding, cellspacing.

## More on Objects

### Constructors

Constructor functions allow objects to be created that all share the same keys but can have different values for the keys as specified when using a constructor function. This saves time writing similar code and also acts as error mitigation.

The 'this.' notation acts as a placeholder for an object when the scope of that line is within the object itself.
When arrays are properties of objects, they can be referenced like normal using the index of a specific item within it.

There are built in objects and object properties. Window has document, history, location, navigator, and screen properties. Then there is DOM which is self-defining. And javascript also has its own extensive list of global objects. Within all of these objects are extensive libraries of helpful features that help make coding faster and cleaner.



#### [Home](README.md)
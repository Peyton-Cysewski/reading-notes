# Reading Notes 02

## Text

Certain text features have notation that is within angle brackets. Below are the types of changes that can be made to text with their indicators:
- Headings have six levels of priority: h1, h2, h3, h4, h5, h6
- Paragraphs: p
- Bold: b
- Italic; i
- Supersripts: sup
- Subscripts: sub

White space is collapsed within html. Line breaks are written as <br />. Horizontal rules are <hr />.

Other semantic markup is used to add effect to the the text:
- Emphasize: em
- Strong: strong

Quotations:
- Blockquotes: blockquote
- Quotes (shorter): q

Abbreviations/Acronyms:
- Abbreviation: <abbr title="Professor">Prof</abbr>
- Acronym: <acronym title="National Aeronautics and Space Administration">NASA</acronym>

Citations and Definitions:
- Cite: cite
- Define: dfn

Author Details:
- Address: address

Changes to Content
- Inserted: ins
- Deleted: del
- Strikethorugh s

## CSS Introduction

CSS, or Cascading Style Sheets, is commonly referred to as using the box method. This means that every element essentially has a box that surrounds it which defines where it takes up space on the screen and what area can be styled for each element. This is a good way of being able ot visual where every element will go and how it will behave once it is rendered.

The syntax for creating rules to change the style appears as a selector followed by curly braces. Within the braces will be a property, colon, a value, and end with a semi-colon.

Links are used to connect the style sheet to the html structure. The relationship between the files also needs to specified in this case to make the CSS file be interpreted correctly.

Since this is a top-down code, it is read in that order. Therefore, the most recent rule will alwasy have priority over any similar rules.

## JavaScript Introduction

JavaScript works by first declaring variables. This acts like creating different pieces that can be used in the code later on. The next step is to assign the variables certain values. These values can be numbers, strings, or boolean values. These can be set up individually or via shorthand all on the same line.

Arrays can be created and they store lists of variables. The list always starts at 0, not 1, and are accessed by referencing said index, starting from 0.

Once all the pieces are set up, a script can be written that tells the variable what to do and how to interact with one another. Since the variables hold the value they were assigned, they can be referenced by their variable name and still function as numbers, strings, or boolean values. For example, if var a = 3 and var b = 7, then if c = a * b and the varible c was to be displayed, it would show as 21. These types of expressions are made using operators, in this specific case, arithmetic operators. There are also string operators, comparison operations, and logical operators.

These operators are all used commonly with if statements and if-else statemtents.
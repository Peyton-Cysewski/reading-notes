# Reading Notes 03

## Lists

Lists exist to help order data. They come in two forms as a numbered or Ordered List and as bullets or Unordered List. Lists can also be nested by indenting and placing one inside of the former.
- Ordered: ol
- Unordered: ul
- Listed Items: li
- Defintion Lists: dl
    - Definition Term: dt
    - Definition: dd

## Boxes

Boxes are the framework through which different elements of an html page are organized and therefore styled. Boxes have basic dimensions of height and width which can be changed with specific measurements or percentages of the screen size. These can be limited with min-width, max-width, min-height, and max-height.

Overflowing content can be told to be hidden or accessed with scroll.

The box model contains the base content, then there is a padding, a border, and padding. Borders can have width specifications and styles. They can be indivually changed or there are shorthand methods that can set simpler styles in a single line. Padding is usually used ot make the content of the element more readable. They margins that are outsid eof the border are collapsed when multiple elements are present, meaning that the larger margin is used and the smaller ones are simply disregarded.

Boxes can be centered by setting the left and right margins to auto to have them equally spaced.

Inline block, a setting of display, makes blocks act like inline elements. The display: none; feature makes an element not appear on the page at all. Using visibility: hidden; makes the element invisible, but it leaves a blank space.

Border images are what happens when an image is used around the sides. It can be stretched, repeated, or rounded.

Box shadows can be placed around the image, but there is also an inset option to have it displayed inside the image border.

Borders can be rounded using border-radius with the radii of each corner the same or specified. There is also a way to make elliptically rounded corners using extra argumetns to make the sides of the corner different lengths.

## JavaScript Decisions

If statements check for certain conditions. If a specified conditio is met, then the codeblock contained in its curly braces is executed. Else statements have additonal conditions that the code proceeds to if the prior condition isn't met.

Switch statments only look for a single variable. The statement then looks for that instance of the variable that is the same and executes the code block beneath it. Typically, break statements are added to leave after that code block, but if there isn't a break statement, then it will continue sequentially to the next code blocks.

JavaScript tries to run code through coercion by changing the data type rather than strictly reporting errors. Due to this, all data types have a truthy or falsy 'backup' boolean type. To be clear, this is NOT a true boolean value, but is a lightweight substitute. (For a table of strict versus loose boolean comparisions see JS book page 168)

Short circuit values are values that cause the expression to get a result and they return that value. It a truthy or falsy value, not a true boolean value.

## JavaScript Loops

For Loops have the keyword 'for', the condition (which includes a counter), and a code block in curley braces:
- for (variable i = 0; i < 10; i++)

While Loops do not need a counter to run. They will work as long as the condition is 'TRUE'. If a counter is being used, it needs to be added as a statement in the code block since there is no specified spot in its condition area like how there is with normal for loops.

Do-While Loops are almost the same as its predecessor, except it will always run the statement in the code block at least once, even if the condition was evaluated as 'FALSE'. The first increment happens after the first execution of the code block.




#### [Home](README.md)
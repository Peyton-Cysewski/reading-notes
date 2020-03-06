# Reading Notes 04

## Links

Links are made using the 'a' element. Within the opening tag there will be: href="". To link to another website page, the url is posted in the quotes. to link to anoher page on the same site, an html file can be posted there.

 A common practice is to put files in their own directories by category instead of a ton of uniquely named files. This way many can be named index.html, but they would be located in different directories, so it works. To access different files you can use their related directories by going into a child directory or parent directory, and so forth.

 To open up an email program to email someone you do href="mailto:example@gmail.com
 To open a link in a new window you add target="_blank" within the opening tag.
 To link within the same page you reference the id the same way it is done in CSS.
    Linking to a specific part of another web page works the same way, except the last directory is the id tag.

## Layout

Normal Flow: Every block is on it\'s new line.
Relative: New positioning relative to where the normal flow would be.
Absolute: Positioned as if it were not interacting with anything else.
Fixed: Type of absolute positioning that is relative to the window.
Floating Elements: Moves elements out of normal flow, but allow others to flow around it.

To make sure that the container of a floating element isn't a single pixel wide, use:
    overflow: auto; and width: 100%;

Overlapping elements may sometimes be in the wrong order. You can choose which appears on top with the z-index. The higher a number is compared to other z-index elements, the closer to the top of the overlapped elements it will appear.

Columns can be created by using a combination of floating boxes, specific widths, and id or class tags.

Different screen sizes and resolutions have made making websites more difficult since they likely have to work on all of them. It is typical for the top 600 or so pixels to be immediately visable so that the user can gauge the content. Layouts can be fixed, or they can be liquid, and change with the scaling.

Layout grids help with continuituy between web pages. Using these CSS frid frameworks are very common and helpful when making a uniform website.

You can used a modular approach for styles by having multiple style sheets, but it helps to import them into a single file, then link to the one main file.

## Functions

These are groupings of things that do specific tasks. They are declared by writing: function sayWords() {}. To call a function in javascript it just needs to be retyped: sayWords();

Functions can take parameters, which are like variable placeholdes to be used internally inside the codeblock of the function. They also return values, to be used outside the function. Typically they only return one value, but you can place multiple values in an array and return the array to in affect return multiple values. The values that are declared inside of a function only work in its local scope. If they are declared outside a function, then it has a global scope and can be referenced anywhere. It is important to keep track of global scope naming between even different javascript files.

## Pair Programming

The advantages of pair programming are varied, but it is useful because overall it is much more effecient. It allowed cleaner code to be written, the coders can learn from each other, it's easier to stay on track, and it improves social skills which are almost universally useful.











#### [Home](README.md)
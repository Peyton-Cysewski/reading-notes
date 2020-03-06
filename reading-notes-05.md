# Reading 05

## Images

Images are added to pages with the src="" method.
- `alt` is an attribute that has many uses. It is essentially a description of the picture.
- `title` is another attribute that dislays additonal info when a cursor hovers over the image.
- `height` and `width` are other specific attribute.

The location of an image on your page determines where and how it interacts with other elements. It can be placed outside of text-filled elements or within them, in which case it will act like an in-line element.

When saving or editing picture for use in websites, make sure they are of the right format (jpeg, gif, or png), make sure they are measured in pixels, and save them in the same dimensions of which will be used on the website.
- jpeg type are best with colorful pictures
- gif type are best with colors with large flat color areas like logos
    - they can be animated using a few different similar frames to create a simple animation. Note that is will increase its overall file size.

If possible, source images that are already of the right shape like portrait versus landscape. The images should be sized by pixels, since that will not result in the loss of resolution of the image. Vector images are not reliant of resolution, so their resolution won't be affected by scaling.

Transparent images have some specific rules and optimal situations. More info on html book page 118.

In html, the `<figure>` was created to allow an image to be associated with, in this case it is so the `<figcaption>` tag can know where to put a caption with the image.

## Color

Color has many different ways of being referenced. The RGB method is the most straightforward where a value between 0 ad 255 is listed for red, green, and blue. If specified, and aditional value of the color's opacity can also be referenced as the letter 'a'. There are also hex codes, used to display the color more succinctly, and some predefined names of color values like 'red' or 'yellow.'

Other elements of color are hue, as referenced by pointing to a place on a circle, 0-360 degrees, saturation, a scale of that color to full grayness, or lightness, a black to normal to white spectrum. As a sidenote, there is also simply just the value of brightness which is only a black to normal spectrum.

## Text

Terminology
- Serif: fonts that have details at the end of main strokes
- Sans-Serif: have straight ends to letters
- Monospace: all letters have the exact same width
- Cursive: can have joined characteristics or handwriting styles
- Fantasy: decorative font that is mainly used for titles
    (other info found in html book page 268)

Type
- `font-family` decided what font to render the type in. If a computer doesn't have the right one, then you can list alternatives
- `font-size` chooses size of the font in several different specifications
    - pixels, percentages, ems (relative to text size of the parent element)
- `@font-face` allows fonts to be downloaded externally, so long you have a liscence to use it. I src="" must be provided to show where to get it from

Font can come in formats that not every browser supports. This means that certain steps need to be taken in order for the browser to render the information correctly. The types should be supported in this order: .eot .woff .ttf/.otf .svg
    (more information in html book page 278)

More Text Properties
- `font-weight` changes the scale of boldness, if you will, of text
- `font-style` normal, italic, or oblique
- `text-transform` uppercase, lowercase, or capitalize
- `text-decoration` none, underline, overline, line-through, blink
- `line-height` changes the gap between the descender of one line to the ascender of another
- `letter spacing` or `word-spacing` changes the distance between words or letters (the kerning)
- `text-align` shift the text to a part of its element (left, right, center, justify)
- `vertical-align` only really used with inline elements
- `text-indent` indents text, but can also take a negative value
- `text-shadow` it creates a colored backdrop of the text
- `:first-letter` or `:first-line` not properties, but pseudo-elements that are specified at the end of a CSS selector
- `:link` or `:visited` sets styles for links that have and have not been visited
- `:hover` , `:focus` or `:active` changes the style of elements when they are either hovered over, clicked, or in 'focus' of the browser




#### [Home](README.md)
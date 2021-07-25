# The < canvas > element

- At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.

- The < canvas> element can be styled just like any normal image (margin, border, background…).

- As a consequence of the way fallback is provided, unlike the < img> element, the < canvas> element requires the closing tag (</ canvas>).



# Drawing shapes with canvas

- Unlike SVG, < canvas> only supports two primitive shapes: rectangles and paths 

**There are three functions that draw rectangles on the canvas:**
<ol>
<li>fillRect(x, y, width, height) :
Draws a filled rectangle.</li>
<li>strokeRect(x, y, width, height) :
Draws a rectangular outline.</li>
<li>clearRect(x, y, width, height) :
Clears the specified rectangular area, making it fully transparent.</li>
</ol>


# Applying styles and colors

- there are two important properties we can use:                  fillStyle and strokeStyle.

# Drawing text

The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.


- strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
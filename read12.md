 # Useage of canvas 
Using the element **canvas**  it looks like the img tag but dont have src tag it has width and hight , it can be stylied just like the image .
Fall back content 
Its so easy just just insert the alternate content inside the <canvas> element. Browsers that don't support <canvas> will ignore the container and render the fallback content inside it.
Note that you should use the closing tag 
The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown
The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The <canvas> element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRenderingContext2D
The script includes a function called draw(), which is executed once the page finishes loading; this is done by listening for the load event on the document. This function, or one like it, could also be called using window.setTimeout(), window.setInterval(), or any other event handler, as long as the page has been loaded first. 
Drowning shaps with canvas
HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed
Drawing  rectangular 
<canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths.
> Fellrect(x.y.width .hight)
# Drawing path.
1.  First, you create the path.
 
2. Then you use drawing commands to draw into the path.

3. Once the path has been created, you can stroke or fill the path to render it.

# Color.

there are two important properties we can use: fillStyle and strokeStyle
color is a string representing a CSS <color>, a gradient object, or a pattern object. We'll look at gradient and pattern objects later.
Drawing text .
Strok text (x,y, text,[max width]
There are some more properties which let you adjust the way the text gets displayed on the canvas:
1.Font value 
Text align
3. Direction
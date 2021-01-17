# image
control size of images 
> <img src="images/magnolia-large.jpg"
 >class="large" alt="Magnolia" />
><img src="images/magnolia-medium.jpg"
 >class="medium" alt="Magnolia" />
><img src="images/magnolia-small.jpg"
> class="small" alt="Magnolia" />
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download
# aligning images Using Css
1. 1: The float property is added to the class that was created to represent the size of the image (such as the small class in our example).
2. New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

### Centering images Using Css
1. On the containing element, you can use the text-align property with a value of center. 

2. On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

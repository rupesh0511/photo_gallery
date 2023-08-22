# photo_gallery
hosted link-

HTML

![Screenshot 2023-08-22 113003](https://github.com/rupesh0511/photo_gallery/assets/69234169/97761a21-0efd-42c9-a760-c3b5ede0ccc2)

'!DOCTYPE html': This declaration specifies that the document is an HTML5 document.



'html lang="en"': The opening tag for the HTML document. The lang="en" attribute indicates that the document's primary language is English.



'head': This section contains metadata about the document, such as character encoding, the viewport configuration, and the document title.



'meta charset="utf-8"': Sets the character encoding of the document to UTF-8, which supports a wide range of characters.


'meta name="viewport" content="width=device-width, initial-scale=1.0"': Defines the viewport settings for responsive web design. It ensures that the page adapts to the device's width and sets the initial zoom level to 1.0.


'title'Photo Gallery'/title': Sets the title of the web page, which appears in the browser's title bar or tab.


'link rel="stylesheet" href="./styles.css"': This tag links an external CSS stylesheet to the HTML document. The href attribute specifies the path to the stylesheet, which is named "styles.css." This stylesheet is used to define the page's styles and layout.


'body': The main content of the web page is contained within this tag.



'header class="header"': This is a header section that typically contains introductory content or navigation elements.



'h1'css flexbox photo gallery'/h1': An h1 (header 1) tag is used to define the main heading of the page. In this case, it is "css flexbox photo gallery."


'div class="gallery"': This div element with the class "gallery" is used to create a container for a photo gallery.



'img src="URL" alt="imageX"': A series of <img> (image) tags are used to display images in the gallery. Each <img> tag has a src attribute that specifies the image's source URL, and an alt attribute that provides alternative text for accessibility.


Here's a breakdown of the image tags:



'img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/1.jpg" alt="image1"': Displays the first image with an alternative text of "image1."


'img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/2.jpg" alt="image2"': Displays the second image with an alternative text of "image2."


... (similarly for images 3 to 9)



CSS


![Screenshot 2023-08-22 113010](https://github.com/rupesh0511/photo_gallery/assets/69234169/d62ad22f-3c93-4b36-84a8-2de5872a3460)
![Screenshot 2023-08-22 113022](https://github.com/rupesh0511/photo_gallery/assets/69234169/e8225c9e-ec1d-45fd-a734-2e8c0fb367a6)

' * { box-sizing: border-box; }': This rule sets the box-sizing property for all elements on the page to "border-box," which ensures that an element's padding and border are included in its total width and height.



' body { margin: 0; font-family: sans-serif; background: #f5f6f7; }': This rule styles the body element, setting the following properties:



'margin: 0;': Removes any default margin from the body.


'font-family: sans-serif;': Sets the font family for text content to a generic sans-serif font.


'background: #f5f6f7;': Sets the background color of the body to a light grayish-blue.


' .header { text-align: center; text-transform: uppercase; padding: 32px; background-color: #0a0a23; color: #fff; border-bottom: 4px solid #fdb347; }':

This rule styles an element with the class "header," commonly used for headers at the top of web pages. It includes:



'text-align: center;': Centers the text within the header.


'text-transform: uppercase;': Converts the text to uppercase.


'padding: 32px;': Adds 32 pixels of padding to the header, providing space around its content.


'background-color: #0a0a23;': Sets the background color to a dark blue.


'color: #fff;': Sets the text color to white.


'border-bottom: 4px solid #fdb347;': Adds a 4-pixel solid border at the bottom of the header with a light orange color.


' .gallery { display: flex; flex-direction: row; flex-wrap: wrap; justify-content: center; align-items: center; gap: 16px; max-width: 1400px; margin: 0 auto; padding: 20px 10px; }':

This rule styles a container with the class "gallery," likely used for displaying images in a gallery format. It includes:



'display: flex;': Makes the container a flex container.


'flex-direction: row;': Sets the direction of flex items to be in a row.


'flex-wrap: wrap;': Allows flex items to wrap to the next row when there's not enough horizontal space.


'justify-content: center;': Centers the flex items horizontally within the container.


'align-items: center;': Centers the flex items vertically within the container.


'gap: 16px;': Adds 16 pixels of space between flex items.


'max-width: 1400px;': Sets the maximum width of the container to 1400 pixels.


'margin: 0 auto;': Centers the container horizontally on the page.


'padding: 20px 10px;'

: Adds 20 pixels of padding on the top and bottom and 10 pixels on the left and right of the container.


' .gallery img { width: 100%; max-width: 350px; height: 300px; object-fit: cover; border-radius: 10px; }': This rule styles the images within the gallery. It includes:



'width: 100%;': Makes the image take up 100% of its container's width.


'max-width: 350px;': Sets a maximum width of 350 pixels for the image.


'height: 300px;': Sets a fixed height of 300 pixels for the image.


'object-fit: cover;': Scales and crops the image to cover the entire container, maintaining its aspect ratio.


'border-radius: 10px;': Adds rounded corners with a 10-pixel radius to the image.


' .gallery::after { content: ""; width: 350px; }': This rule generates an empty content pseudo-element after the gallery container. It includes:



'content: "";': Adds an empty content area.


'width: 350px;': Sets the width of this empty content area to 350 pixels, providing additional spacing after the gallery.



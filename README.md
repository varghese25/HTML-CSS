
## HTML Text Formatting(04-12-2024)




<br>______________________________________________________________________________________________________________<br>

## HTML Headings (03-12-2024)
HTML headings are defined with the <h1> to <h6> tags.<br>
<h1> defines the most important heading. <h6> defines the least important heading.<br>
Example<br>
<h1>Heading 1</h1><br>
<h2>Heading 2</h2><br>
<h3>Heading 3</h3><br>
<h4>Heading 4</h4><br>
<h5>Heading 5</h5><br>
<h6>Heading 6</h6><br>

## Bigger Headings<br>
Each HTML heading has a default size. However, you can specify the size for any heading with the style attribute, using the CSS font-size property:<br>



## HTML Paragraphs<br>
Example<br>
<p>This is a paragraph.</p><br>
<p>This is another paragraph.</p><br>


## HTML Display<br>
You cannot be sure how HTML will be displayed.<br>

Large or small screens, and resized windows will create different results.<br>

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.<br>

The browser will automatically remove any extra spaces and lines when the page is displayed:<br>



## HTML Styles<br>
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.<br>
<p>I am normal</p><br>
p style="color:red;">I am red</p> // single Qutoes accepted<br>
<p style="font-size:50px;">I am big</p><br>



## HTML Horizontal Rules<br>

<!DOCTYPE html><br>
<html><br>
<body><br>

<h1>This is heading 1</h1><br>
<p>This is some text.</p><br>
<hr>  // hr element is used to separate content (or define a change) in an HTML page: __________________________ this line show under pargraph tag<br>

Note: The <hr> tag is an empty tag, which means that it has no end tag.<br>


<h2>This is heading 2</h2><br>
<p>This is some other text.</p><br>
<hr> // hr element is used to separate content (or define a change) in an HTML page:<br>




## HTML Line Breaks<br>
The HTML <br> element defines a line break.<br>
Use <br> if you want a line break (a new line) without starting a new paragraph:<br>


<!DOCTYPE html><br>
<html><br>
<body><br>

<p>This is<br>a paragraph<br>with line breaks.</p><br>

</body><br>
</html><br>

The <br> tag is an empty tag, which means that it has no end tag.<br>



## The HTML <pre> Element<br>

The HTML <pre> element defines preformatted text.<br>
The text inside a <pre> element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:<br>

<!DOCTYPE html><br>
<html><br>
<body><br>

<p>The pre tag preserves both spaces and line breaks:</p><br>

<pre><br>
   My Bonnie lies over the ocean.<br>

   My Bonnie lies over the sea.<br>

   My Bonnie lies over the ocean.<br>
   
   Oh, bring back my Bonnie to me.<br>
</pre><br>

</body><br>
</html><br>



## Background Color<br>
The CSS background-color property defines the background color for an HTML element.<br>

<!DOCTYPE html><br>
<html><br>
<body style="background-color:blue;"><br> // Tag to remember

<h1>This is a heading</h1><br>
<p>This is a paragraph.</p><br>

</body><br>
</html><br>



Example<br>
## Set background color for two different elements:<br>

<!DOCTYPE html><br>
<html><br>
<body><br>

<h5 style='background-color: yellow'>this is a heading</h5><br>
<p style="background-color: red"> This a a Paragraph</p><br>

</body><br>
</html<br>




## Text Color<br>
The CSS color property defines the text color for an HTML element:<br>

<!DOCTYPE html><br>
<html><br>
<body><br>

<h5 style='color: yellow'>this is a heading</h5><br>
<p style="color: red"> This a a Paragraph</p><br>

</body><br>
</html<br>




## Fonts<br>
The CSS font-family property defines the font to be used for an HTML element:<br>


<!DOCTYPE html><br>
<html><br>
<body><br>

<h5 style='font-family:verdana;'>this is a heading</h5><br>
<p style="font-family:courier;'"> This a a Paragraph</p><br>

</body><br>
</html<br>




## Text Size<br>
The CSS font-size property defines the text size for an HTML element:<br>
<!DOCTYPE html><br>
<html><br>
<body><br>

<h5 style='font-size:300%;'>this is a heading</h5><br>
<p style="font-size:150%;'"> This a a Paragraph</p><br>

</body><br>
</html<br>



## Text Alignment<br>
The CSS text-align property defines the horizontal text alignment for an HTML element:<br>

<!DOCTYPE html><br>
<html><br>
<body><br>

<h5 style="text-align:center;">Center this is a heading</h5><br>
<p style="text-align:center;"> Center This a a Paragraph</p><br>

</body><br>
</html<br>




<br>______________________________________________________________________________________________________________<br>


## HTML Links(02-12-2024)
HTML links are defined with the <a> tag:<br>
Example<br>
<a href="https://www.w3schools.com">This is a link</a><br>

## HTML Images<br>
The source file (src), alternative text (alt), width, and height are provided as attributes:<br>
Example<br>
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142"><br>

## How to View HTML Source<br>
Click CTRL + U in an HTML page, or right-click on the page and select "View Page Source". This will open a new tab containing the HTML source code of the page.<br>

## Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.<br>


## HTML Elements
An HTML element is defined by a start tag, some content, and an end tag.<br>
The HTML element is everything from the start tag to the end tag:.<br>
<tagname>Content goes here...</tagname>.<br>



Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!<br>



## Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).All HTML documents consist of nested HTML elements.<br>
The following example contains four HTML elements (<html>, <body>, <h1> and <p>):<br>
Example<br>
<!DOCTYPE html><br>
<html><br>
<body><br>

<h1>My First Heading</h1><br>
<p>My first paragraph.</p><br>

</body><br>
</html><br>

## HTML is Not Case Sensitive
HTML tags are not case sensitive: <P> means the same as <p>.<br>



## HTML Attributes<br>
1. All HTML elements can have attributes<br>
2. Attributes provide additional information about elements<br>
3. Attributes are always specified in the start tag<br>
4. Attributes usually come in name/value pairs like: name="value"<br>

## The href Attribute<br>
The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:<br>
Example<br>
<a href="https://www.w3schools.com">Visit W3Schools</a><br>


## The src Attribute<br>
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:<br>

Example<br>
<img src="img_girl.jpg"><br>


The width and height Attributes <br> 
https://www.w3schools.com/html/html_attributes.asp


















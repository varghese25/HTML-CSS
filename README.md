<br>______________________________________________________________________________________________________________<br>
## HTML Styles - CSS ( 18-12-2024)
CSS stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.


## Inline CSS
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;">A Blue Heading</h1> <!-- Inline CSS -->

<p style="color:red;">A red paragraph.</p>

</body>
</html>


## Internal CSS

<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>



External CSS
An external style sheet is used to define the style for many HTML pages.

To use an external style sheet, add a link to it in the <head> section of each HTML page:


## index.html

!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

## styles.css
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}



<br>______________________________________________________________________________________________________________<br>

## HTML RGB and RGBA Colors
An RGB color value represents RED, GREEN, and BLUE light sources.

An RGBA color value is an extension of RGB with an Alpha channel (opacity).



<br>______________________________________________________________________________________________________________<br>
## HTML Colors (17-12-2024)
<!DOCTYPE html>
<html>
<body>
   <h1 style="background-color:Salmon;">Salmon</h1>
</body>
</html>

Note: HTML supports 140 standard color names.
Background Color
You can set the background color for HTML elements:


## Background Color
You can set the background color for HTML elements:

<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:DodgerBlue;">Hello World</h1>

<p style="background-color: Salmon;"> Varghese Baby
</p>

</body>
</html>


## Text Color
<!DOCTYPE html>
<html>
<body>

<h3 style="color:Tomato;">Hello World</h3>

<p style="color:DodgerBlue;">
Varghese Baby </p>

<p style="color:MediumSeaGreen;">Shannon, Evan.</p>

</body>
</html>



## Border Color
You can set the color of borders:

<!DOCTYPE html>
<html>
<body>

<h1 style="border: 2px solid Tomato;">Serah Benjamin</h1>

<h1 style="border: 2px solid DodgerBlue;">Shannon Varghese</h1>

<h1 style="border: 2px solid Violet;">Evan Varghese</h1>

</body>
</html>



## Color Values
In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three <div> elements have their background color set with RGB, HEX, and HSL values:



<!DOCTYPE html>
<html>
<body>

<p>Same as color name "Tomato":</p>

<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

<p>Same as color name "Tomato", but 50% transparent:</p>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

<p>In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.</p>

</body>
</html>




<br>______________________________________________________________________________________________________________<br>
## HTML Text Formatting(16-12-2024)

<!DOCTYPE html>
<html>
<body
<p><b>Hello World!!</b></p>
<p><i>Hello World!!</i></p>
<p><sub>Hello World!!</sub> And <sup>InterNet World!!</sup></p> //Sub - subcriptcript and superscript
</body>
</html>


HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text



## HTML <blockquote> for Quotations
<!DOCTYPE html>
<html>
<body>

<p>Here is a quote from WWF's website:</p>

<blockquote> / is used as a indentation/ 
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>

</body>
</html>


## HTML <q> for Short Quotations
<!DOCTYPE html>
<html>
<body>

<p>Browsers usually insert quotation marks around the q element.</p>

<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p> /it q used as Qutation/ 

</body>
</html>



## HTML <abbr> for Abbreviations

<!DOCTYPE html>
<html>
<body>

<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>

</body>
</html>


## HTML <address> for Contact Information

<!DOCTYPE html>
<html>
<body>

<p>The HTML address element defines contact information (author/owner) of a document or article.</p>

<address>
Written by John Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

</body>
</html>


## HTML <cite> for Work Title

<!DOCTYPE html>
<html>
<body>

<p>The HTML cite element defines the title of a work.</p>
<p>Browsers usually display cite elements in italic.</p>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

</body>
</html>


## HTML <bdo> for Bi-Directional Override
BDO stands for Bi-Directional Override.

The HTML <bdo> tag is used to override the current text direction:


<!DOCTYPE html>
<html>
<body>

<p>If your browser supports bi-directional override (bdo), the next line will be written from right to left (rtl):</p>

<bdo dir="rtl">This line will be written from right to left</bdo>

</body>
</html>

## HTML Comments
You can add comments to your HTML source by using the following syntax:
<!-- Write your comments here -->

## Add Comments
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->



## Hide Content

<p>This is a paragraph.</p>

<!-- <p>This is another paragraph </p> -->

<p>This is a paragraph too.</p>

## Hide a section of HTML code:

<p>This is a paragraph.</p>
<!--
<p>Look at this cool image:</p>
<img border="0" src="pic_trulli.jpg" alt="Trulli">
-->
<p>This is a paragraph too.</p>


## Hide Inline Content

<p>This <!-- great text --> is a paragraph.</p>


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


















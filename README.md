# HTML 
### What is html?

- Hyper text markup language.
- html creating web pages.
- html serces of element.
- html element tell borwser how to dispaly the content.

### 1.Element

1. Element.

- Start tag content End tag.
- h1,p,div

2. Empty Element.

- Only Start tag.
- br,hr,img

### 2.Attribute

- All html Element can have Attribute.
- Attribute are providing addtional information.
- Attribute are always spacifed in start tag.
- Attribute usually come in name/value name="value".

* eg:-href ,src, style, width, higth...

### 3.Type of Element

1. Block level Element.

- block level element start a new line.
- block level element take up full width.
- block level elenment has a take top and a bottom margin.

* eg:- div, p, h1, hr, ul, li

2. Inline Element.

- Inline element don't start a new line.
- Inline elemnt only takes up as much width.

* eg:- span, button, img, br, input

### 4.Css

- Cascading Style Sheets.
- It can control the layout of multiple web pages all at once.

1. Inline.
2. Internal.
3. External.

### 5.Form

- collection of user input

1. Form Attribute.
2. Form Element.
3. Form Input type .
4. Form Input Attribute.

***
***
***









# HTML (www.w3schools.com)

### 1.What is html?
- Hyper Text Markup Language.
- HTML is standard markup language for creating Web pages.
- HTML consists of a series of elements.
- HTML elements tell the browser how to display the content.

- markup language list (html, json, docBook etc..)
### 2.HTML Structure Explained

~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <p>My first paragraph.</p>
    </body>
</html>
~~~

- `<!DOCTYPE html>` document type declaration.this document is an HTML5 document and helps browsers to display web pages correctly. not case sensitive
- `<html></html>` this element is root element of an HTML page.
- `<head></head>` this element contains meta data/meta information about the HTML page. 
    + meta data( data that provides information about other data / data that describes other data / information about data)
- `<title></title>` title of the HTML page(show on bowser's title bar).
- `<body></body>` element defines the document's body. it will be displayed in a browser

### 3. Element
- `<tagName> contant here..</tagName>`
- start tag ,some content and end tag 
- every elements have Start-tag and End-tag but some elements have no end-tag(like `<hr>, <br>`). those elements are called empty elements
- All the HTML elements/tags are case-insensitive.
- Element dispaly type inline and block .
 
### 4. Attributes
- All elements can have Attributes.
- Attributes provide additional information about elements
- Attributes are always specified in the start tag.
- Attributes usually come in name/value pairs like: name="value".
- HTML attributes are generally classified as required attributes, optional attributes, standard attributes, and event attributes [HTML Attributes](https://en.wikipedia.org/wiki/HTML_attribute)

> "You should practice 'event attributes' "

### 5. Tags

#### 1. Heading `<h1></h1>`
- headings are defined with the `<h1>` to `<h6>` tags.
- Browsers automatically add some white space (a margin) before and after a heading
- Search engines use the headings to index the structure and content of your web pages.

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

#### 2. Paragraphs `<p></p>`
- `<p>This is a paragraph.</p>`
- A paragraph always starts on a new line.
- browsers automatically add some white space (a margin) before and after a paragraph.
- you cannot change the display by adding extra spaces or extra lines in your HTML code
- The browser will automatically remove any extra spaces and lines when the page is displayed
```
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```
#### 3. Horizontal Rules `<hr>`

- `<hr>` displayed as a horizontal rule.
- `<hr>` tag is a empty tag. 

#### 4. Line Breack `<br>`

- `<br>` is a line breack tag.
- if you want a new line without starting a new paragraph.
- `<br>` is a empty tag. 

#### 5.preformatted `<pre></pre>`

- `<pre>` element defines preformatted text. 
- displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

- The Poem Problem:-poem will display on a single line.
```
<p>
 this is item paragraph.

 this is item 2 paragraph.
 
 this is item 2 paragraph.
</p>
```

- poem will not display on a single line. so use `<pre>`
```
<pre>
 this is item paragraph.

 this is item 2 paragraph.
 
 this is item 2 paragraph.
</pre>
```
#### 6. Style

- `style` is an attribute.
- Used to add styles to an attribute.

```
<tagName style="property:value;">
<p style="color:blue;">this is style</p>
```

#### 7. Formatting Elements
-  display special types of text.
- `<b></b>`  Bold text
- `<i></i>`  Italic text
- `<em></em>`  Emphasized text
- `<del></del>`  Deleted text
- `<ins></ins>`  Inserted text
- `<sub></sub>`  Subscript text
- `<sup></sup>`  Superscript text
- `<small></small>`  Smaller text
- `<strong></strong>`  Important text
- `<Marked></Marked>`  Italic text


#### 8. Quotation 
- `<blockquote>` 
    + for Quotations
    + section that is quoted from another source
- `<q>`
    + short quotation.
    + Browsers normally insert quotation marks around the quotation.
- `<abbr>`
    + defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
    + Marking abbreviations can give useful information to browsers, translation systems and search-engines.
    + Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.
- `<address>`
    + tag defines the contact information for the author.
    + The contact information can be an email address, URL, physical address, phone number, social media handle, etc.
    + element usually renders in italic.
- `<cite>`
    + tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
    + element usually renders in italic.
- `<bdo>`
    + BDO stands for Bi-Directional Override.
    + tag is used to override the current text direction.

#### 9. Comments

- comments are not displayed in the browser but  help document
- more than one line.
`<!-- Write your comments here -->`
- Hide Inline Content
`<p>This <!-- great text --> is a paragraph.</p>`


#### 10. Color
- colors are specified with predefined color name, RGB, RGBA, HSL, HSLA, HEX
1. Color Name
    + All modern browsers support the 140 color names
    + [Color name](https://www.w3schools.com/colors/colors_names.asp)
    + To display red: red

2. RGB 
    + RGB - RED,Green,Bule 
    + formula:- rgb(red, green, bule).
    + Each parameter pass 0 to 255.
    + To display black: like this rgb(0,0,0)
    + To display white: like this rgb(255,255,255) 
    + To display red: like this rgb(255,0,0) 

3. RGBA 
    + Formula:- rgba(red, green, blue, alpha)
    + RGB color values with an Alpha(opacity) channel
    + alpha parameter is a number 0.0 (fully transparent) to 1.0 (not transparent at all).
    +  To display red: rgba(255, 99, 71, 0.8)

4. HEX
    + hexadecimal color is specified with: #rrggbb
    + 00 and ff (same as decimal 0-255).
    + hexadecimal mean(0 to 9 - a to f) total 16 decimal number
    + highest value (ff) and lowest value (00)
    + To display red: #ff0000

5. HSL
    + HSL stands for hue, saturation, and lightness.
    + Formula:- hsl(hue, saturation, lightness).
    + Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
    + Saturation is a 0% (shade of gray) to 100% (full color). 
    + Lightness is 0% (black) to 100% (white).
    + To display red: hsl(0, 100%, 50%)

6. HSLA 
    + HSL color values, with an Alpha(opacity) channel
    + Formula:- hsla(hue, saturation, lightness, alpha)
    + alpha parameter is a number 0.0 (fully transparent) to 1.0 (not transparent at all).
    + To display red:hsla(0, 100%, 50%, 0.5)

#### 11. Styles - CSS
- CSS stands for Cascading Style Sheets.
- It can control the layout of multiple web pages all at once.
- Quicker Development Time
- CSS can be added to HTML documents in 3 ways
    1. Inline - by using the style attribute inside HTML elements.
    2. Internal - by using a `<style>` element in the `<head>` section.
    3. External - by using a `<link>` element to link to an external CSS file.
#### 12. Images
- `<img>` tag is used to embed an image in a web page.   
- Images are not technically inserted into a web page; images are linked to web pages.
- The `<img>` tag creates a holding space for the referenced image.
- The `<img>` tag is empty, it contains attributes only.
- The `<img>` tag has two required attributes:
    1. src - Specifies the path to the image.
    2. alt - Specifies an alternate text for the image


```
<img src="url" alt="alternatetext">
```
- Images in Another Folder
    `<img src="/image/monkey.jpg" alt="Monkey" style="width:100px;height:150px;">`

- Images on Another Server/Website
    `<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">`
    
- Image as a Link
    ```
    <a href="https://translate.google.com/">
        <img src="/image/monkey.jpg" alt="Monkey" style="width:42px;height:42px;">
    </a>
    ```
##### 1. Image map.   
- `<map>` tag defines an image map. An image map is an image with clickable areas.The areas are defined with one or more `<area>` tags. `usemap` attribute of the <img> element to point to an image map
- A clickable area is defined using an `<area>` element
- Shape
    + rect 
    + circle 
    + poly 
    + default 
```
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
```
##### 2. Background Image.
-  background image on an HTML element, use the HTML style attribute and the CSS background-image property.
```
<p style="background-image: url('abc.jpg');">
```  

##### 3. picture 
- `<picture>` element allows you to display different pictures for different devices or screen sizes.
- `<picture>` element gives web developers more flexibility in specifying image resources.
-  The `<img>` element is used by browsers that do not support the `<picture>` element, or if none of the `<source>` tags match.
```
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
```
#### 13. Favicon 
- A favicon is a small image, so it should be a simple image with high contrast.
- A common name for a favicon image is "favicon.ico"

#### 14. Table
- Table cells inside rows and columns.
- `<table></table>` crate table.
- `<tr></tr>` mean by table row.
- `<th></th>` mean by table heading.
- `<td></td>` mean by table colum/cell
##### 1.Borders
1. border -  add a border, use the CSS border property on table, th, and td elements
2. border-collapse - avoid having double borders.set the CSS "border-collapse" property to "collapse".
3. Style Table Borders
4. Round Table Borders - "border-radius" property, the borders get rounded corners.
5. Dotted Table Borders - "border-style" property, you can set the appearance of the border
    - dotted     
    - dashed     
    - solid     
    - double     
    - groove     
    - ridge     
    - inset     
    - outset     
    - none     
    - hidden
6. Border Color - "border-color" property, you can set the color of the border.
```
<table>
    <tr>
        <th>Hading</th>
    </tr>
    <tr>
        <td>cell</td>
    </tr>
</table>
```
##### 2.Sizes
1. Use the "style" attribute with the "width" or "height" properties to specify the size of a table, row or column.
2. Using a percentage as the size unit for a width means how wide will this element be compared to its parent element, which in this case is the `<body>` element.

##### 2.Headers
1. Align Table Headers -  use the CSS "text-align" property.
2. Header for Multiple Columns - use the "colspan" attribute on the `<th>` element.
3. Table Caption - add a caption that serves as a heading for the entire table.use the `<caption>` tag.The `<caption>` tag should be inserted immediately after the <table> tag.

##### 3. Padding & Spacing
- tables can adjust the padding inside the cells, and also the space between the cells.
1. Cell Padding
    + Cell padding is the space between the cell edges and the cell content.
    + By default the padding is set to 0.
    + add padding on table cells, use the "CSS padding" property
        - padding-top
        - padding-bottom
        - padding-left
        - padding-right 
2. Cell Spacing
    + Cell spacing is the space between each cell.
    + By default the space is set to 2 pixels.
    + To change the space between table cells, use the "CSS border-spacing" property on the table element
    
##### 3. Colspan & Rowspan
- tables can have cells that span over multiple rows and/or columns.
1. Colspan
    + Cell span over multiple columns, use the "colspan" attribute.
2. Rowspan
    + Cell span over multiple rows, use the "rowspan" attribute.

#### Can you? 
1. What is HTML?
2. Can you explain HTML structure?
3. What is the Element? sytax and example? howmany type?
4. What is Attributes? howmuch classified Attributes?
5. Heading?
6. Paragraphs?
7. Horizontal Rules?
8. Line Breack?
9. preformatted?
10. Style?
11. Formatting Elements? ten format?
12. Quotation? six Quotation?


















































































### Reference link

- `https://www.w3schools.com/whatis/whatis_roadmap.asp`
- `https://blog.kritikapattalam.com/html-roadmap`
- `https://transitionintotech.com/learn-html/`
- `https://careerhigh.in/post/roadmap_to_learn_html_css_and_javascript_for_beginners`
- `https://roadmap.sh/`
- `https://github.com/topics/roadmap?l=html`






***
***
# My HTML

***
***

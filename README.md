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

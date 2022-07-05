# <> HTML5 and CSS3 <>

<br>

> HTML stands for HyperText Markup Language. It is used to design web pages using the markup language. HTML is the combination of Hypertext and Markup language. Hypertext defines the link between the web pages and markup language defines the text document within the tag that define the structure of web pages.

<br>

## What is HTML used for ?
HTML is used to create the structure of web pages that are displayed on the World Wide Web (www). It contains Tags and Attributes that are used to design the web pages. Also, we can link multiple pages using Hyperlinks.

<br>

## HTML Basic Format Page Structure
The basic structure of an HTML page is laid out below. It contains the essential building-block elements (i.e. doctype declaration, HTML, head, title, and body elements) upon which all web pages are created.



<br>
<p align=center>
<img src=../gif_img/HTML_basic_structure.png width=400px>
<p>
<br>

* `<DOCTYPE! html>` – A doctype or document type declaration is an instruction that tells the web browser about the markup language in which the current page is written. It is not an element or tag. The doctype declaration is not case-sensitive.

* `<html>` – This tag is used to define the root element of HTML document. This tag tells the browser that it is an HTML document. It is the second outer container element that contains all other elements within it.

* `<head>` – This tag is used to define the head portion of the HTML document that contains information related to the document. Elements within the head tag are not visible on the front-end of a webpage.

* `<body>` – The body tag is used to enclose all the visible content of a webpage. In other words, the body content is what the browser will show on the front end.

<br>

## HTML Selectors
> Selectors or tags are the elements of an HTML document.

<br>

Selectors may or may not have content, When selectors have content, it's necessary to delimit the content with `<selector> content </selector>`.
When the selector has no content, it's a good practice to write `<selector/>`.

<br>
 
## Structure of a selector
* With content:

`<SelectorName possibleAttribute1 = "value1" otherPossibleAttribute= "value2"> content </SelectorName> ` 

* Without content:

`<OtherSelectorWithoutContent/>`

<br>

## HTML Attributes
> Attributes are defined individually in each selector and can only be declared in the first part of the selector.

<br>

## `<h1>` to `<h6>` tags

The `<h1>` to `<h6>` tags are used to define HTML headings.

`<h1>` defines the most important heading. 

`<h6>` defines the least important heading.

<br>

### Example:

```html
<h1>text h1</h1>
<h2>text h2</h2>
<h3>text h3</h3>
<h4>text h4</h4>
<h5>text h5</h5>
<h6>text h6</h6>
```

Output:

<h1>text h1</h1>
<h2>text h2</h2>
<h3>text h3</h3>
<h4>text h4</h4>
<h5>text h5</h5>
<h6>text h6</h6>


<br>

## `<p>` tag

The `<p>` tag defines a paragraph.

Browsers automatically add a single blank line before and after each `<p>` element.

### Example 

```html
<p style="text-align:right">This is some text in a paragraph.</p>
```

Output: 

<p style="text-align:right">This is some text in a paragraph.</p>

<br>

## `<br>` tag

The `<br>` tag inserts a single line break.

The `<br>` tag is useful for writing addresses or poems.

The `<br>` tag is an empty tag which means that it has no end tag.

### Example

```html
<p>Be not afraid of greatness.<br>
Some are born great,<br>
some achieve greatness,<br>
and others have greatness thrust upon them.</p>

<p><em>-William Shakespeare</em></p>
```

Output 

<p>Be not afraid of greatness.<br>
Some are born great,<br>
some achieve greatness,<br>
and others have greatness thrust upon them.</p>

<p><em>-William Shakespeare</em></p>

<br>

##  `<hr>` tag
The `<hr>` tag defines a thematic break in an HTML page (e.g. a shift of topic).

The `<hr>` element is most often displayed as a horizontal rule that is used to separate content (or define a change) in an HTML page.

### Example

```html
<hr style="width:50%;text-align:left;margin-left:0">
```
Output: 

<hr style="width:50%;text-align:left;margin-left:0">

<br>


## Font changers

Font changers are used to style the text.

## `<b>` tag

The `<b>` tag specifies bold text without any extra importance.

### Example

```html
<p>This is normal text - <span style="font-weight:bold;">and this is bold text</span>.</p>
```

Output:
<p>This is normal text - <span style="font-weight:bold;">and this is bold text</span>.</p>

<br>

## `<i>` tag

The `<i>` tag defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

### Example

```html
<p><i>Lorem ipsum</i> is the most popular filler text in history.</p>
```

Output:

<p><i>Lorem ipsum</i> is the most popular filler text in history.</p>

<br>

## `<s>` tag
The `<s>` tag specifies text that is no longer correct, accurate or relevant. The text will be displayed with a line through it.

The `<s>` tag should not be used to define deleted text in a document, use the `<del>` tag for that.

### Example

```htl
<p><s>Only 50 tickets left!</s></p>
<p>SOLD OUT!</p>
```

Output:

<p><s>Only 50 tickets left!</s></p>
<p>SOLD OUT!</p>

<br>

## `<u>` tag
The `<u>` tag represents some text that is unarticulated and styled differently from normal text, such as misspelled words or proper names in Chinese text.

### Example

```html
<p>This is some <u>mispeled</u> text.</p>
```

Output:

<p>This is some <u>mispeled</u> text.</p>

<br>

## Lists tags

The `<li>` tag is used to define each list item.

The `<ol>` tag defines an ordered list. An ordered list can be numerical or alphabetical.

The `<ul>` tag defines an unordered (bulleted) list.

### `<ol>` example

```html
<ol style="list-style-type:upper-roman">
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ol>
```

Output:
<ol style="list-style-type:upper-roman">
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ol>

### `<ul>` example

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

Output:

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>


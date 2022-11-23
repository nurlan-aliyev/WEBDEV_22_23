
# HTML  Elements
An HTML element is defined by a start tag, some content, and an end tag.

----------

## HTML Elements

The HTML  **element**  is everything from the start tag to the end tag:

`<tagname>Content goes here...</tagname>`

Examples of some HTML elements:

`<h1>My First Heading</h1>`

`<p>My first paragraph.</p>`

## Never Skip the End Tag

Some HTML elements will display correctly, even if you forget the end tag:

```
<html>  
<body>  
  
<p>This is a paragraph  
<p>This is a paragraph  
  
</body>  
</html>
```

**However, never rely on this! Unexpected results and errors may occur if you forget the end tag!**

----------

## Empty HTML Elements

HTML elements with no content are called empty elements.

The  `<br>`  tag defines a line break, and is an empty element without a closing tag:

`<p>This is a <br> paragraph with a line break.</p>`

## HTML is Not Case Sensitive

HTML tags are not case sensitive:  `<P>`  means the same as  `<p>`.

The HTML standard does not require lowercase tags, but W3C  **recommends**  lowercase in HTML, and  **demands**  lowercase for stricter document types like XHTML.

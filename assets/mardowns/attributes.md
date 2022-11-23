# HTML  Attributes
HTML attributes provide additional information about HTML elements.

----------

## HTML Attributes

-   All HTML elements can have  **attributes**
-   Attributes provide  **additional information**  about elements
-   Attributes are always specified in  **the start tag**
-   Attributes usually come in name/value pairs like:  **name="value"**

----------

## The href Attribute

The  `<a>`  tag defines a hyperlink. The  `href`  attribute specifies the URL of the page the link goes to:

`<a href="https://www.google.com">Visit Google</a>`

## The src Attribute

The  `<img>`  tag is used to embed an image in an HTML page. The  `src`  attribute specifies the path to the image to be displayed:

`<img src="chain_bridge.jpg">`
There are two ways to specify the URL in the  `src`  attribute:

**1. Absolute URL**  - Links to an external image that is hosted on another website. Example:  `src="https://media.istockphoto.com/id/490305484/photo/chain-bridge-budapest.jpg?s=612x612&w=0&k=20&c=jYtQHYZcAf6MwYpqIFy7t6TEzm8cpGpHT_XdvFdmFQo="`.

**Notes:**  External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

**2. Relative URL**  - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="chain_bridge.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/chain_bridge.jpg".

**Tip:**  It is almost always best to use relative URLs. They will not break if you change domain.

----------

## The width and height Attributes

The  `<img>`  tag should also contain the  `width`  and  `height`  attributes, which specify the width and height of the image (in pixels):

`<img src="chain_bridge.jpg"  width="500"  height="600">`

## The alt Attribute

The required  `alt`  attribute for the  `<img>`  tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the  `src`  attribute, or if the user uses a screen reader.

`<img src="chain_bridge.jpg"  alt="Budapest Chain Bridge">`

## The style Attribute

The  `style`  attribute is used to add styles to an element, such as color, font, size, and more.

### Example

`<p style="color:red;">This is a red paragraph.</p>`

## The lang Attribute

You should always include the  `lang`  attribute inside the  `<html>`  tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

```
<!DOCTYPE html>  
<html lang="en">  
<body>  
...  
</body>  
</html>
```

Country codes can also be added to the language code in the  `lang`  attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:

```
<!DOCTYPE html>  
<html lang="en-US">  
<body>  
...  
</body>  
</html>
```

## The title Attribute

The  `title`  attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

`<p title="I'm a tooltip">This is a paragraph.</p>`

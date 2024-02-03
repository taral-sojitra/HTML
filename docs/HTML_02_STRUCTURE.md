# STRUCTURE OF AN HTML DOCUMENT

When constructing your HTML document, you can use certain tags to establish its structure. The `<h1>` to `<h6>` tags signify different heading levels, with `<h1>` being the highest level and `<h6>` being the lowest level.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

The `<p>` tag is used to create a paragraph.

```html
<p>This is a paragraph.</p>
```

The `<div>` tag can be used to segment and style different areas of the document. It also acts as a parent container for other elements within the document.

Example:

```html
<div class="about-us">
  <h1>About Us</h1>
  <p>Welcome to the About Us section!</p>
</div>
<div class="contact-us">
  <h1>Contact Us</h1>
  <p>Contact us at 0123456789</p>
</div>
```

The `<span>` tag is similar to `<div>` but is used as an inline container.

```html
<p>Hello <span class="span1">World!</span></p>
```

The `<br/>` tag is used to insert line breaks in the document. It does not require a closing tag.

```html
<p>Welcome to<br/>Taral Sojitra Git-repo</p>
```

The `<hr/>` tag is used to create a horizontal line. It also does not require a closing tag.

```html
<p>Welcome to<hr/>Taral Sojitra Git-repo</p>
```

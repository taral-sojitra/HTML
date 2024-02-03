# STRUCTURE OF A HTML DOCUMENT

While constructing your HTML document, you can use certain tags to establish its structure. The `<h1>` to `<h6>` tags signify different heading levels, with `<h1>` being the highest level and `<h6>` being the lowest level.

```html
<h1> Code Help </h1>
<h2> Code Help </h2>
<h3> Code Help </h3>
<h4> Code Help </h4>
<h5> Code Help </h5>
<h6> Code Help </h6>
```

You use the `<p>` tag to create a paragraph.

```html
<p> This is a paragraph </p>
```

The `<div>` tag can be employed to segment and style different areas of the document. It also acts as a parent container for other elements within the document.

This is how it works:

```html
<div class="About Us">
  <h1> This is the About Us section </h1>
  <p> Welcome to the About Us section! </p>
</div>
<div class="Contact Us">
  <h1> This is the Contact Us section </h1>
  <p> Contact us on 0123456789 </p>
</div>
```

We also have the `<span>` tag. This is similar to `<div>` but you use it as an inline container.

```html
<p> Hello <span class="span1"> World! </span></p>
```

There's the `<br/>` tag, which we use to insert line breaks in the document. This tag does not require a closing tag.

```html
<p> Welcome to <br/> Code Help </p>
```

The `<hr/>` tag is used to create a horizontal line. It also has no closing tag.

```html
<p> Welcome to <hr/> Code Help </p>
```


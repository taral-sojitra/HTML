# HTML COMPONENTS

- `<html>` tag: This tag acts as a container for every other element in the document except the `<!DOCTYPE html>` tag.
- `<head>` tag: Includes all the document's metadata.
- `<title>` tag: Defines the title of the document which is displayed in the browser's title bar.
- `<body>` tag: Acts as a container for the document's content that gets displayed on the browser.

This is how it all comes together:

```html
<!DOCTYPE html>
<html lang="en">
 <head>
 <title> Code Help HTML Cheat Sheet </title>
 </head>
<body> .... </body>
</html>
```

`<!DOCTYPE html>` specifies that we are working with an HTML5 document.

The following tags contribute extra information to the HTML document:

- `<meta>` tag: This tag can be used to define additional information about the webpage.
- `<link>` tag: Used to link the document to an external resource.
- `<style>` tag: Used for defining styles for the document.
- `<script>` tag: Used to write code snippets (usually JavaScript) or to link the document to an external script.

```html
<head>
 <meta charset="UTF-8" />
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <link rel="stylesheet" href="style.css" />
 <title>Code Help HTML Cheat Sheet</title>
 <style>
 *{
 font-size: 40px;
 }
 </style>
 <script>
 alert ('message');
 </script>
</head>

# HTML COMPONENTS

- `<html>` tag: Acts as a container for every other element in the document except the `<!DOCTYPE html>` tag.
- `<head>` tag: Includes all the document's metadata.
- `<title>` tag: Defines the title of the document displayed in the browser's title bar.
- `<body>` tag: Acts as a container for the document's content displayed on the browser.

Example:
```html
<!DOCTYPE html>
<html lang="en">
 <head>
 <title> HTML Cheat Sheet </title>
 </head>
<body> .... </body>
</html>
```

`<!DOCTYPE html>` specifies an HTML5 document.

Extra information tags:
- `<meta>` tag: Defines additional information about the webpage.
- `<link>` tag: Links the document to an external resource.
- `<style>` tag: Defines styles for the document.
- `<script>` tag: Contains code snippets (usually JavaScript) or links to external scripts.

Example:
```html
<head>
 <meta charset="UTF-8" />
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
 <link rel="stylesheet" href="style.css" />
 <title>HTML Cheat Sheet</title>
 <style>
 *{
 font-size: 40px;
 }
 </style>
 <script>
 alert ('message');
 </script>
</head>
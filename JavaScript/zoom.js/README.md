# How
You must add zoom.js and zoom.css to your html file like this:
```html
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="zoom.css">
<script defer src="zoom.js"></script>
<title> testing zoom.js </title>
</head>
```
zoom.js dependent on transition.js. for adding this js to your html,
you can use [bootstrap.js](https://github.com/drk-drg/WPL/blob/main/Frameworks/BootStrap/js/bootstrap.js)

you must add `data-action="zoom"` to your image like this:
```html
<img src="..." data-action="zoom">
```
# by who?
By [@fat](https://github.com/fat)

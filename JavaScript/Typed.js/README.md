# how
First add typed.min.js to your html file,

Then create a div with any class and:
```html
<div class="...">
<span id="typed"></span>
</div>
```
put this to html.

And create another div with... :
```html
<div id="typed-strings">
<p>...</p>
<p>...</p>
<!--- you can add more paragraphs if you want --->
</div>
```
``replace the dots with your phrases.``

then put it in html.

Now add some scripts:
```html
<script>
    var typed = new Typed('#typed', {
      stringsElement: '#typed-strings',
      typeSpeed: 85,
      loop: true,
    });
</script>
```
you can change the speed of text by editing the
`typeSpeed` in the script above.
# CDN
```html
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
```
*CDN is for typed.js not typed.min.js*

# by who?
<a href="https://github.com/mattboldt/typed.js/" target="_blank">typed.js github page</a>

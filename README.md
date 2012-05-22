jquery-ui-google-buttons
===================

jQueryUI buttons styled as in Google products, with more colors.

###Author
Francesco Pontillo

###Description:
The CSS provided here lets you make any jQuery button in a HTML page a **Google-like button**. Simply add to your element the `g` class and you're done.

More classes are available:

 * Color classes:
   * none: default light grey
   * `red`
   * `blue`
   * `green`
   * `orange`
   * `grey`
   * `ice`
   * `brown`
 * Size classes:
   * none: default
   * `small`
 * Display classes:
   * none: default, `inline-block`
   * `block`
 
![Example](/frapontillo/jquery-ui-google-buttons/raw/master/res/example.png)

###How to use

You need to reference:

 * [jQuery](http://jquery.com/)
 * [jQuery UI](http://jqueryui.com/) (js and css)
 * `jquery-ui-1.8.20.pontillo.g.css` and the desired colors:
   * `jquery-ui-1.8.20.pontillo.g.red.css`
   * `jquery-ui-1.8.20.pontillo.g.blue.css`
   * `jquery-ui-1.8.20.pontillo.g.green.css`
   * `jquery-ui-1.8.20.pontillo.g.orange.css`
   * `jquery-ui-1.8.20.pontillo.g.grey.css`
   * `jquery-ui-1.8.20.pontillo.g.ice.css`
   * `jquery-ui-1.8.20.pontillo.g.brown.css`
   
Then, create an element and apply the `g` class, the desired color, size and display.
 
Checkout the `example.html` page to see the demo in action.

```html
	<div>
		<div class="button g">default button</div>
		<div class="button g red">red button</div>
		<div class="button g blue">blue button</div>
		<div class="button g green">green button</div>
		<div class="button g orange">orange button</div>
		<div class="button g grey">grey button</div>
		<div class="button g ice">ice button</div>
		<div class="button g brown">brown button</div>
	</div>
```

```javascript
	$(function() {
		$(".button").button();
	});
```

## License

Released under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

Copyright (c) 2012 Francesco Pontillo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
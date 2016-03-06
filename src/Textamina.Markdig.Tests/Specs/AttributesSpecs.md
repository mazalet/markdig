# Extensions

This section describes the different extensions supported:

## Attributes

Attributes can be attached to a previous inline element or the current block if the previous inline element is a literal. Attributes can be:

- An id element, starting by `#` that will be used to set the `id` property of the HTML element
- A class element, starting by `.` that will be appended to the CSS class property of the HTML element
- a `name=value` or `name="value"` that will be appended as an attribute of the HTML element


```````````````````````````````` example
# This is a heading with an an attribute{#heading-link}

[This is a link](http://google.com){#a-link .myclass data-lang=fr data-value="This is a value"}

This is a heading{#heading-link2}
-----------------
.
<h1 id="heading-link">This is a heading with an an attribute</h1>
<p><a href="http://google.com" id="a-link" class="myclass" data-lang="fr" data-value="This is a value">This is a link</a></p>
<h2 id="heading-link2">This is a heading</h2>
````````````````````````````````
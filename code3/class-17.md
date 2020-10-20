# MUSTACHE and FLEXBOX
## Javascript Templating
Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
The template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client
## Mustache
Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.
mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.
## Flexbox
### Properties for the Parent (flex container) :
* **display** :
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.
* **flex-direction** : This establishes the main-axis, thus defining the direction flex items are placed in the flex container. Flexbox is (aside from optional wrapping) a single-direction layout concept. Think of flex items as primarily laying out either in horizontal rows or vertical columns.
* **flex-wrap** : By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.
### Properties for the Children
* **order** : By default, flex items are laid out in the source order. However, the order property controls the order in which they appear in the flex container.
* **flex-grow**: This defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion. It dictates what amount of the available space inside the flex container the item should take up.



# 201 Reading 04

## HTML Links, JS Functions, and Intro to CSS Layout

These topics matter quite a bit, as you need links on a webpage to navigate beyond the first. JavaScript functions are non-stop and basically the reason to use them. and CSS Layout has been absolutely nightmare-ish - hopefully some of these tips will help!

### HTML Links

To create a basic link, we wrap text inside of an `<a href=""></a>` tag.
The `href=""` attribute will contain the link (aka google.com)
Some ways we can ensure links are accessible is adding support information, like a title. `<a href="" title="">NameOfLink</a>` would display a title when hovering over the link with your mouse. Another option would be to make a header a link - it would be very accessible to the eye then! Try something like `<a href=""><h1>Titlehere</h1></a>`

### CSS Layout

Normal flow in CSS is the way webpage elements lay themselves out without any changes to their layout.

#### Block-level vs Inline

Block-level elements are laid out in the *block flow direction* which is based on the parent's writing mode. Each element appears on a new line below the last one, with each one separated by whatever margin is specified. Block level elements are laid out vertically (Mozilla.org)

Inline elements don't appear on new lines, that all sit on the same line along with any adjacent or wrapped text content, as long as there is space to do so within the width of the parent block element. Overflowing content moves down to a new line (Mozilla.org)

Static positioning is the default behavior for positioning.

The **absolute positioning** removes the element from normal document flow, so other positions may auto adjust. The element will sit on its own layer separate from everything else. This is great because its an isolated UI feature that won't interfere with the other elements on the page. It attaches itself to the inital containing block.

**Fixed positioning** works exactly the same as absolute but with one key difference: absolute positioning fixes an element in place to its nearest positioned ancestor (or iinital containing block if there isn't one) whereas fixed positioning usually fixes an element in place relative to the visible portion of the viewport (Mozilla.org) This means you can create useful UI items that are fixed in place.

### Learn JS

A function declaration states what the function does - such as running a specific script. The function invocation INVOKES that script, or runs it, in the place the invocation was placed.

Parameters are values that need to be included in the function parentheses, which the function needs to do its job. Some parameters may be optional and you won't have to specify them, they will adopt a default behavior. An argument is actually just another word for parameters. They can also be called properties, or attributes.

### Misc

Two benefits of pair programming that could help me on my coding journey would be social skills and job interview readiness! I've always had a lot of social anxiety so working closely with people and getting to expand my personal horizons would be very helpful, I think!

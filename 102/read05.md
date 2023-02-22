# Reading 05

## CSS: Style Those Webpages

The purpose of CSS (Cascading Style Sheets) is quite simple yet amazingly complex. In summary - it adds style to your website. But the things you can do are beyond a simple color change and text resize (although you can do those too!)

There are three ways to add CSS:

- External CSS: These can be defined as a link within the element inside of the HTML itself! For example `<link rel=stylesheet href=mystyle.css>` would fetch the CSS inside of the `mystyle.css` file.
- Internal CSS: This type of sheet can be used if one single HTML page has a unique style. These can be defined inside the `<style>` element inside the `<head>` of an HTML page. For example you could add changes with

>`<style>`
>
>`body {`
>
>`background-color: green;`
>
>`}`
>
>`</style>`

- Inline CSS: This style can be used to apply a unique style to a single element. For this you can add the formatting directly into the HTML but you lose the advantage of a style sheet (mixing content and presentation!) so don't use this often. An example below:

>`<h1 style="color:red;text-align:top;>This is a heading</h1>`

Multiple stylesheets can be used! If they are, they have a cascading order:

1. Inline Style
2. External and internal style sheets
3. Browser Default

An example of CSS used to give all `<p>` elements into red text could look something like

>`p{`
>
> `color: #FF0000;`
>
> `}`

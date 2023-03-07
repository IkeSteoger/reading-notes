# 201 Reading 01

## Getting Started

### Getting Started

#### HTTP: A poem

The Browser - seeking a webpage
The DNS server - providing the true address
The HTTP Request - asking for a copy of the webpage
The Approval - Access to the website is granted
The Display - Last but not least, you see the webpagey goodness!

HTML, CSS, and JS files are parsed (or accessed) in a specific order:
> 1. HTML file is parsed
>
> 2. CSS files are found for `<link>` elements & JavaScript files are found for `<script>` elements - then parsed.
> 
> 3. Browser builds tree & applies styles from CSS & executes the JavaScript.

The best way to find images to add to a website is using Google Images but make sure to change to the *Creative Commons licenses* in the **Usage rights* options.

The difference of a string vs a number in JavaScript is very small but important change.
let = "32"; this is a string (notated by the quotation marks)
let = 32; this is a number
Strings can be reassigned into numbers but numbers are not strings.

A variable in JavaScript is a storage container that holds values. They are very important in JavaScript because they can be reused to call back a variable later but with whatever varied value was entered or requested.

### Intro to HTML

An HTML attribute contains surplus info about the element that won't actually appear in the content itself. Ex: `class="nature-images"`

The anatomy of an HTML element has an **opening tag**, the **content** and a **closing tag**. Opening tag tells you which type of element this is. The content isinformation for the element. And the closing tag matches the opening tag, closing the element.

The `<article>` tag is a self-containted composition in a webpage which can be independently distributed or reused. The `<section>` tag is a generic standalone section of a document and should often have a heading. An `<article>` tag could hold several `<section>` tags within it.

A typical website will have `<header>` `<main>` `<footer>` elements but often also include `<nav>` `<aside>` and others.

**Metadata** can influence SEO in many ways, often by including a description that has keywords relating to the content of your page so they appear higher when searched via the web (Google, Bing, etc). 

The `<meta>` tag can be include elements such as `name` and `content` which would appear directly on search engines in the Title & description of the website. You could tag the author & the title of the webpage, but also meta tag the description of the website. Ex `<meta name="Ike" content="Intro to HTML">`

### Misc.

The first step & most important step to designing a website is asking yourself - what exactly do I want to accomplish?

The reason to use a `<h1>` element over a `<span>` element is proper semantics - it will look like a top level heading but not receive the extra benefits afforded to the `<h1>` tag. There are many benefits to proper semantics like this one, such as: SEO, screen readers, and finding blocks of code to edit without digging too much.

Two things that require JavaScript in the browser is creating dynamically updating content & controling multimedia (think YouTube!)
The way to add JavaScript to an HTML document is using the `<script></script>` tag and link to a separate .js file or you could do inline JavaScript, which can get a bit messy but works well in a pinch!
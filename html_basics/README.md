# HTML Basics
This document contains notes about basic HTML development.

## HTML Elements
The following sections demonstrate different kinds of *HTML elements* that can be added to a webpage. 

### Create a Paragraph
A paragraph can be created by using the `<p>` tags:

```html
<p>
  This is a paragraph of text
</p>
```

### Create a Link
A link to an address can be created by using the ```<a>``` tags, which are also known as *anchor elements*. In the following example, `href`, which is short for *hypertext reference*, is known as an *HTML attribute* and defines where you would like the link to lead.

```html
<a href="www.youtube.com">
  Link to YouTube
</a>
```

A link can be opened in a new tab by setting the `target` HTML attribute to `_blank`:

```html
<a href="www.youtube.com" target="_blank">
  Link to YouTube
</a>
```

### Create a Button
A simple button can be created by using `<button>` tags:

```html
<button>
  Meow
</button>
```

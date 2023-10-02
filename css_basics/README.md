# CSS Basics
This document contains notes about basic CSS development.

## The Style HTML Element
The CCS properties associated with an HTML element can be modified in an `.html` file, rather than an external `.css` file, by utilizing a `<style>` element and binding it to another element, such as a button. 

CSS attributes are organized as key-value pairs, made up of a *CSS Property* and a *CSS Value*.

In the following example *all* buttons on the page will be altered, rather than just a specific one:

```html
<style>
  button {
    color: white;
    background-color: red;
  }
</style>
```

In order to modify a specific element or group of elements, the `class` HTML attribute can be used:

```html
<style>
  .make-noise-button {
    color: blue;
    cursor: pointer;
  }
</style>

<button class="make-noise-button">
  Meow
<button>
```

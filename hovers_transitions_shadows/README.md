# Hovers, Transitions, and Shadows

## Pseudo-classes

A pseudo-class can add extra properties to a given class under certain circumstances. For example, they can apply properties when a button is hovered over or a button is clicked.

In the following example, `.submit-button:hover` is a pseudo-class that applies properties when the button, `submit-button` is hovered over. The `.submit-button:active` pseudo-class applies properties when the button is clicked.

```html
<style>
  .submit-button {
    color: white;
    background-color: black;
  }

  .submit-button:hover {
    background-color: green;
  }

  .submit-button:active {
    background-color: blue;
  }
</style>

<button class="submit-button">
  Click me
</button>
```

## Transitions

In order to create an animated effect, a `transition` property can be applied to an element.

In the following example, a `transition` property is applied that will make any change in `opacity` for `submit-button`, caused by its pseudo-classes, take 0.15 seconds to change.

This creates the effect of animating the opacity of the button when a defined action is performed.

```html
<style>
  .submit-button {
    color: white;
    background-color: black;
    transition: opacity 0.15s;
  }

  .submit-button:hover {
    background-color: green;
  }

  .submit-button:active {
    background-color: blue;
  }
</style>

<button class="submit-button">
  Click me
</button>
```

## Shadows

A shadow can be applied to an element by using the `box-shadow` CSS property and animated using the `transition` class, as in the previous example.

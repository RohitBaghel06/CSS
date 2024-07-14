# CSS
This is my CSS Git repository.


## CSS Style Types
- The three types of CSS are external, internal, and inline. 
- External CSS is a file that HTML files will link to.
- Internal CSS is specified at the beginning of an HTML document.
- Inline CSS is written for a specific element in the HTML document.


## CSS Color Properties
- The color CSS property sets the foreground color value of an element's text and text decorations, and sets the currentcolor value.
- There are five types of Color properties in the css
- ColorName, rgb, hsl, hsla #VALUE, hwb
```
h1 {
    color: rebeccapurple;
}
h2 {
    color: #00a400;
}
color: rgb(214, 122, 127);
color: hsl(30deg 82% 43%);
color: hsla(237deg 74% 33% / 61%);
color: hwb(152deg 0% 58% / 70%);
```


## CSS Text Properties
- Text properties allow you to control everything from the appearance and position of text, to resizing behavior and OpenType features.
- text-align, font-weight, text-decoration, line-height, letter spreading, etc.

## Selector in CSS
- In CSS, selectors are used to target the HTML elements on our web pages that we want to style.
- It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.

### Types of Selectors
- Type(Normal) selectors target an HTML element such as an <h1>
```
h1 {
}
```

- ID selectors target an element that has a specific value for its id attribute:
```
#unique {
}
```

- Class selectors target an element that has a specific value for its class attribute:
```
.box {
}
```

### Attribute Selectors
- This group of selectors gives you different ways to select elements based on the presence of a certain attribute on an element:
```
a[title] {
}
```

### Pseudo-Classes
- Pseudo-classes, which style certain states of an element. 
-  The :hover pseudo-class for example selects an element only when it is being hovered over by the mouse pointer:
```
a:hover {
}
```

### Pseudo-Elements
- Pseudo-elements, which select a certain part of an element rather than the element itself.
- For example, ::first-line always selects the first line of text inside an element (a <p> in the below case), acting as if a <span> was wrapped around the first formatted line and then selected.
```
p::first-line {
}
```

### Combinators
- The final group of selectors combine other selectors in order to target elements within our documents.
- The following, for example, selects paragraphs that are direct children of <article> elements using the child combinator (>):
```
article > p {
}
```


# HTML & CSS Concepts
<br />

## Render Engines

These are software programs that transform the code that we write into a language that the browser can understand.

## HTML Elements

A HTML document its build with a group of elements call **tags**, these tags could be:

- **Paired tags:** Are those that has an opening and closing tag, example:

```html
<p></p>
<footer></footer>
```
- **Self closing:** Are those that doesn't have a closing tag, just an Opening but with a slash before close the tag, example:
 
```html
<br />
<hr />
<img />
```

#### HTML Attributes

They are declares inside the tag, these could be:

- class
- id
- data
- src
- placeholder

As well, some tags has its owns attributes, example:

```html
<div class="some-class" id="some-id"></div>
```

#### Semantic HTML

This allows to know to browsers how your website is structurated and helps to improve in the searching engine.
Some of the tags are:

- **header:** Defines the header of a web page or section
- **nav:** Defines the navigation bar with links
- **section:** Defines a section within a web page

> For more info visit this [link](https://htmlreference.io/)

## CSS Anatomy

A CSS sentences is a declaration to define some specific styles to a HTML tag. The sentence is made up of:

- **Selector:** Defines the element or bunch of elements where the styles will be.
- **Property:** It is the style's name.
- **Value:** It's the value that the property has.

Example:

```css
h1{
    font-size: 1px;
    color: blue;
}
```

### Selectors

We have basic and combinators:

- **Basic ones:** We have: Type (div), Class (class="something"), ID (id="some"), Attribute (a[href="some"]), universal(*)

- **Combinator ones:** We have: decendents (div p), direct child (div > p), adjacent element - 'brother' (div + p), brothers (div ~ p)

> [CSS colors reference](https://htmlcolorcodes.com/es/nombres-de-los-colores/)

### Pseudoclasses & Pseudoelements



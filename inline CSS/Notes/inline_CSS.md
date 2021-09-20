# CSS
CSS stands for Cascading Style Sheets. The main purpose of CSS is to design a web page. CSS helps to make the web page more attractive. 
We can implement CSS in HTML file in three different ways:
- Inline CSS: CSS codes locate inside the body element in HTML
- Internal CSS: CSS codes locate outside the body element inside a particular element called `<style>`
- External CSS: CSS codes locate outside the HTML file. 
# Inline CSS
- Ideal CSS implementation approach for very simple web pages. 
- `style` attribute takes care of the CSS part.
- We can structure and design the web page at the same time.
- Not an ideal implementation approach for a complex web page. 

Syntax
``` html
<h1 style = "color: green; font-family: arial"> Hello World </h1>
```
From the syntax above:
- `style` attribute can contains any CSS property.
- `color` and `font-family` are the properties that indicate the aspects of the element you want to change. 
- `green` is the value of the `color` property. And `arial` is the value of `font-family`.
- Therefore, In the `<h1>` element the text `Hello World` will be appear on the web page as arial font with color green.

sample:

![image](./helloWorldtext.png "output")






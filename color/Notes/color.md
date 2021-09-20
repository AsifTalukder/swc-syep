# Color
To make your website attractive and brings your page to life, `color` property plays an important role. By using `color` property we can specify the color for texts, borderlines and background inside an element. `background-color` property allows us to specify the color for background of the page or a certain parts of the web page.

## Ways to specify color in CSS
We can specify color in CSS using three different way:
- Color Names
- Hex Codes
- RGB Values

## Color Name:
The simplest way we can specify the color value is using color name. We exactly put the color name in english that we want to use. There are 147 predefined color names that are recognized by the browser. For example: `color: green`. The browser will automatically recognize the color green.  

Syntax
``` htmnl
h1{
    color: blue;
}
```
## Hexadecimal Codes
- We can use hexadecimal number to indicate colors. There're are six digit code that are represent the amount of red, green, blue in a color. 
- A hex code contains: #RRGGBB, where RR indicates amount of Red, GG indicates amount of green and BB indicates amount of blue. 
- All values must be between 00 too FF. 
- For example, `color: #ff0000` represents red. Because, red component is set to its highest value where others set to 00. 

Syntax 
``` html
h1{
    color: #00ff00;
}
```
##  RGB Values
- Every color on computer screen is created by mixing amount of red, green and blue.
- We can create color by indicating amount of red, green and blue by using rgb() function.
- rgb function contains three parameter. First parameter indicate the amount of red, second parameter indicate amount of 
  green and third parameter indicate the amount of blue. For example: `color:rgb(80,100,20)`

 Syntax:
 ``` html
   h2{
       color: rgb(100, 80, 90);
   }
   ``` 

Sample:
``` html
h1{
    color:cadetblue
}
h2{
    color: #00008b
}
h3{
    color: rgb(80,20,50);
}
```
output:

![image](./sample1_output.png "output")

# Background Color:
We can specify background color for each HTML elements. CSS sees each HTML elements as a box and we can specify the background color for elements by using `background-color` property.
- We can specify the background color three way as we did for text color. 
- Most browser set white background color by default. Therefore, if we don't specify any background color it will be appear white. 
- We can specify whole webpage's background color by using the `background-color` property inside `<body>` element.

Sample
``` html
 <!-- specifying background color by using color names -->
body{
    background-color:wheat;
}
h1{
    background-color:#9ac893;
}
<!-- specifying background color by using hex codes -->
h2{
    background-color: #4169e1;
}
<!-- specifying background color by using RGB values -->
h3{
    background-color: rgb(141, 85, 192);
}
```
Output

![image](./sample2_output.png "output")

## Hexadecimal Colors with Transparency
To add transparency in background color we add two additional digit between 00 and FF.

Sample
``` html 
#notran{
    background-color:#ff0000;
}
#tran{
    background-color: #ff000080;
}
```
output

![image](./sample3_output.png "output")


     
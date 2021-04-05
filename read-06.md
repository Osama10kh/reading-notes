# Introducing CSS
CSS allows you to create rules that specify how the content of an element should appear and  allows you to create rules that control the way that each individual box.
with css you can style 
* boxes such as, width and hight, borders, back ground color and IMG position.
* Text such as, Typeface, Size, Color, Italics, bold, uppercase, lowercase.
* Specific There are also specific ways in which you can style certain elements such as lists, tables, and forms.

*CSS works by associating rules with HTML elements.*
A CSS rule contains two parts: a selector and a declaration:

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTu-NWaLuRPCKkC3JtpL3sxgzDvHBCuUe7YEw&usqp=CAU)

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in onedeclaration, each separated by a semi-colon.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQxIjfoWtjIFTOc2zJNrcWIhXMWNFpmBr-YtA&usqp=CAU)

# Using External CSS
```html
* <link> : The <link> element can be used in an HTML document to tell the browser where to find the CSS, and it 
lives inside the <head> element. It should use three attributes

* href: This specifies the path to the CSS file.

* type: This attribute specifies the type of document being linked to.

* rel This specifies the relationship 
between the HTML page and 
the file it is linked to. The value 
should be stylesheet when 
linking to a CSS file.
```

# Using Internal CSS
```html
* <style> : You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page.
```
# CSS Selectors
 CSS selector that allow you to target rules to specific elements in an HTML document, CSS selectors are case sensitive, so they must match element names and attribute values exactly.
 * Examples:
 ```html
  * Type Selector : h1, h2, h3 {}Targets the <h1>, <h2> and  <h3> elements

  * ID Selector : #introduction {}Targets the element whose 
   id attribute has a value of introduction.

  * Class Selector : .note {}Targets any element whose class
   attribute has a value of notep.note {}Targets only <p>  elements whose class attribute has a value of note.
```
# Color
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
* rgb values : These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,200,300).
*  hex codes : These are six-digit codes that 
represent the amount of red, green and blue in a color, 
preceded by a pound or hash # sign. For example: #ee3e80.
* color names There are 147 predefined color names that are recognized by browsers. For example: Dark.

**background-color**
background-color is a property sets the color of the background for that box.You can specify your choice of 
background color in the same three ways.

**color**
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.

* Hue :Hue is near to the colloquial idea of color.
* Saturation: Saturation refers to the amount of gray in a color.
* Brightness:Brightness (or "value") refers 
to how much black is in a color. 

**opacity**
CSS3 introduces the opacityproperty which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5is 50% opacity and 0.15 is 15% opacity).
**HSL Colors**
 to specify colors using hue, saturation, and lightness values.
 the lightness is Lightness is the amount of 
 white (lightness) or black (darkness) in a color. 

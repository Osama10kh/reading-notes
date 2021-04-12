# Basics of HTML, CSS & JS

## text
tags (known as markup) to the contents of the page. These tags allow browsers to show users the appropriate structure for the page.
```html
* Headings
HTML has six "levels" of 
headings: <h1> to <h6>

* Paragraphs
To create a paragraph, surround the words that make up the paragraph with an opening <p>tag and closing </p> tag.

* Bold & Italic
<b> for bold & <i>for italic

* Superscript & Subscrip
The <sup> element is used to contain characters that should be superscript. ex: 4<sup>th</sup> ---> 4^th.
<sub>  is used to contain characters that should be subscript. It is commonly used with foot notes.

* Line Breaks & Horizontal Rules
to add a line break inside the middle of a paragraph you can 
use the line break tag <br />.
To create a break between themes you can add a 
horizontal rule between sections using the <hr /> tag.
```
## Visual Editors & Their Code views
* Visual editors resemble word processors.
* Code views show you the code created by the visual editor. 
## Semantic Markup
text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages.


```html
The use of the <strong> element indicates that its content has strong importance.

The <em> element indicates emphasis that subtly changes 
the meaning of a sentence.

* for Quotations use <blockquote> for longer or <q> for shorter.

* use <cite> for referencing a piece of work.
The <dfn> element is used to indicate the defining instance of a new term.

* The <address> element is used to contain contact details for the author of the page.

* The <ins> element can be used to show content that has been inserted into a document.

* <del> element can show text that has been deleted from it.

* The <s> element indicates something that is no longer 
accurate or relevant.

```

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

## Using External CSS
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

## Using Internal CSS
```html
* <style> : You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page.
```
## CSS Selectors
 CSS selector that allow you to target rules to specific elements in an HTML document, CSS selectors are case sensitive, so they must match element names and attribute values exactly.
 * Examples:

```html
  * Type Selector : h1, h2, h3 {}Targets the <h1>, <h2> and  <h3> elements

  * ID Selector : #introduction {}Targets the element whose 
   id attribute has a value of introduction.

  * Class Selector : .note {}Targets any element whose class
   attribute has a value of notep.note {}Targets only <p>  elements whose class attribute has a value of note.
```    

## How Css Rules Cascade
If there are two or more rules that apply to the same element, which will take precedence?
* LAST RULE
* SPECIFICIT
  * If one selector is more specific than the others, the    more specific rule will take precedence.
* !IMPORTANT
  * add !important after any property value to indicate that it should be considered more important than other rules.

## Why use External Style Sheets?
* All of your web pages can share the same style sheet, This means that the same code does not need to be repeated in every page.
* the site will load faster, If you want to make a change to how your site appears, you only need to edit the one CSS file and all of your pages will be updated.
* The HTML code will be easier to read and edit .

# Basic JavaScript structer
* STATEMENTS : A script is a series of instructions that a computer can follow one-by-one. 
* COMMENTS :  to explain what your code does. They help make your code easier to read and understand. // & /*text*/
* VARIABLE : A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. 
  * ex: var (name);
  * to assign a value : var (name) = value;

## DATA TYPES 
* STRING : ('value')
* BOOLEAN : TRUE or FULSE
* NUMERIC : number

*you can chang the value of the variable  ex :*
* var name = 22;
* var name = 50;
* the value changed from 22 to 50.

## RULES FOR NAMING VARIABLES
* It must not start with a number. 
*  not use a dash(-) or a period (.) in a variable name. 
*  keywords or reserved words.
* All variables are case sensitive.
* Use a name that describes the kind of information that the 
variable stores.
* If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. 

## arrays
An array is a special type of variable. It doesn't just store one value; it stores a list of values.

ex : var colors; 

colors ['white', 'black', ' custom']; 


## INDEX VALUE 
* 0 'white ' 
* 1 'black' 
* 2 'custom'

## OPERATORS
* ASSIGNMENT OPERATORS
* COMPARISON OPERATORS 
* ARITHMETIC OPERATORS 
  * ADDITION +
  * SUBTRACTION -
  * DIVISION /
  * MULTIPLICATION *
  * INCREMENT + +
  * DECREMENT --
  * MODULUS %
* LOGICAL OPERATORS 
* STRING OPERATORS 

# desisions & loop
there are two components to a desisions:
* an expression is evaluated
* a conditional statements
## ## comparison operators:
to evaluate a situation comparing one value in the script to what you expect it might be.
* is equal to ==
  * use to compares two values 
* is not equal to !=
  * use to compares two values
* strict equal to ===
  * use to compares two values to check that both the data type and value are same.
* strict not equal to !==
  * use to compares two values to check that both the data type and value are same.
* greater than >
  * to check if the number on the lift is grater than the number on the right.
* less than <
  *  to check if the number on the lift is less than the number on the right.

**when we add "=" operator to ">" or "<" will checks if number on right equal the number on lift addition to greater than or less.**

### sructer comparision operater
* (operand  'comp.operator'  operand)
* ex : value1 > value2)

# logical operators:
comparision operators return single values (true or false).
* logical AND &&
  * to test more than one condition. (if one of the conditions is false, return false)
* logical OR ||
  * test at least one condition. (if one of the expressions evaluates to true, return true  )  
* logical NOT !
  * this operator take a single boolian value and inverts it.

## if statements
if statement check if the condition True, other statements code are executed.
* ex : if (condition) {

    code( );

} else if (condition) {

    code();

} else {

    code();
}


## SWITCH STATEMENTS
starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 

* var value(1) 
* switch (value) { 
* case '1': 
* msg= 'num1' ; 
* break; 
* case '2': 
* msg = 'num2' ; 
* break;  
* default : 
* msg = 'non'; 
* break; 

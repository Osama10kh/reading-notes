# Process & design:
Every website should be designed for the target audience, r. It is therefore very important to understand who your target audience is, when you know who your visitors are, you need to consider why they are coming, you need to work out what information they need in order to achieve their goals quickly and effectively.This information can help guide your site designs.
* site maps:
  after knowing what needs to appear on site, start to organize the nformation into sections or pages:
  
  example:

  ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtBRm66p1j9uy5S5lHXnVmr7NQPhAaa6fksA&usqp=CAU)

* WireFrames:
A wireframe is a simple sketch of the key 
information that needs to go on each page of a 
site, and it is like a first step to make a website.

  example:

  ![](https://www.experienceux.co.uk/wp-content/uploads/2015/06/wireframe_example_small.jpg)

* use contrast to create a visual hierarchy that gets 
across your key message and helps users find what they are looking for.
  * size 
  * color 
  * style

* Visual hierarchy refers to the order in which your eyes perceive what they see, It is created by adding visual contrast between the items being. 
displayed.

* Grouping related pieces of information together can make a design easier to comprehend, like:
  * Proximity
  * Closure
  * Continuance
  * White Space
  * color
  * Borders

# Designing Navigation:
the Site navigation helps people find where they want to go,and also helps them understand what your site is about and how it is organized. 
principles of Navigation:
  * Concise
  * Clear
  * Selective
  * Context
  * Interactive
  * Consistent

# Structure:
the main structer of html conatains <html>, <body> (opening tags) and     </body>,</html> (closing tags), these are called HTML elements.
HTML Uses Elements to Describe the Structure of Pages.

example:

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgbX8BKbvnkxVK2NHd0P55XxbuGHG2XN_GxftDFR_cwGhRGy3BPe3dRtkpmKK3Rzt82XM&usqp=CAU)

* Tags tell you something about the information that lies between their opening and closing tags.
* Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

* head element.This contains information about the page  You will usually find a title element inside the head element.

* The contents of the title element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit
* about body tag we created Everything inside this element is shown inside the main browser window.

# HTML5 Layout:
web page authors used 'div' elements to group 
together related elements on the page Authors used class or id attributes 
to indicate the role of the div element in the structure of the page.
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEyKVgCLXFwx0oJ4tLhfXos8u04y1QvCo1nA&usqp=CAU) 

```html
The <header> and <footer> elements can be used for:

* The main header or footer that appears at the top or bottom of every page on the site.
* A header or footer for an individual <article> or <section> within the page.
* The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.
* The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
* The <aside> element has two purposes, depending on whether it is inside an <article> element or not.
* The <section> element groups related content together, and typically each section would have its own heading.
* The purpose of the <hgroup> element is to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.
* <figure> element It can be used to contain any content that is 
referenced from the main flow of an article as, images, Videos, Graphs, etc.
*  <a> element around a block level element that contains child elements. This allows you to turn an entire block into a link.
```
# HTML5 LAYOUT Example:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML5 Layout</title>
 <body>
  <header>  

  <nav>  
    <article>

      <figure> 

      </figure>

 
    </article> 
  </nav>  
  <footer>

  </footer>

 </body>
</html>
```
# Extra Markup:
```html
* <!DOCTYPE html> declaration to tell a browser which version of HTML the page is using.

* <!-- -->  to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:

* <p id=""></p> Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page.

* <p class=""></p> HTML element can also carry a class attribute. Sometimes, it is a way to identify several elements as being different from the other elements on the page. rather than uniquely identifying one element within a document.

* <h1>, <p>, <ul>, and <li>. examples of block level elements, they elements will always appear to start on a new line in the browser window. 

* <a>, <b>, <em>, and <img>. examples of inline elements,they will always 
appear to continue on the same line as their neighbouring elements.

* <div> element allows you to group a set of elements together 
in one block-level box.

* <span> element acts like an inline equivalent of the <div>element, The most common reason why people use <span> elements is so that they can control the appearance of the content of these elements using CSS.

* <iframe> An iframe is like a little window that has been cut into your page — and in that window you can see another page.

# Information About Your Pages:

* The <meta> element lives inside the <head> element and contains information about that web page.

* description
* keywords
* robots
* author
* pragma
* expires
```
# Escape Characters:
There are some characters that are used in and reserved by HTML code.
 * (<) Less-than sign
 * (>) Greater-than sign
 * (") Quotation mark
 * (©) Copyright symbol
 * (') Right single quote
 * (”) double quote
 


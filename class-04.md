# Links

```html
Links are created using the
<a>
  element t which has an attribute called href. The value of the href attribute
  is the page that you want people to go to when they click on the link., they
  allow you to move from one web page to another.known as an absolute URL. ex:
  <a href="http://www.link.com">link</a> When you are linking to other pages
  within the same site, you do not need to specify the domain name in the URL.
  You can use a shorthand known as a relative URL.</a
>
```

### Email Links

To create a link that starts up the user's email program and addresses an email to a specified email address, you use the 'a' element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

### Opening Links in a New Window

If you want a link to open in a new window, you can use the target attribute on the opening 'a' tag. The value of this attribute should be \_blank.

### Linking to a Specific Part of the Same Page

```html
To link to an element that uses an id attribute you use the
<a>
  element again, but the value of the href attribute starts with the # symbol,
  followed by the value of the id attribute of the element you want to link to.
  In this example,
  <a href="#top"
    >links to the
    <h1>
      element at the top of the page whose id attribute has a value of top.
    </h1></a
  ></a
>
```

# Layout

### Key Concepts in Positioning Elements

- Building Blocks

  - Block-level elements (start on a new line)
  - Inline elements (flow in between surrounding text)

  ![](data:image/png;base64,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)

  ### Containing Elements

  If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

  ### Controlling the Position of Elements

  - Normal flow
  - Relative Positioning
  - Absolute positioning
    **box offset : is a properties to tell the browser how far from the top or bottom and left or right it should be placed.**
  - Fixed Positioning
  - Floating Elements

### Normal Flow

you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:position: static;

### Relative Positioning

You can indicate that an element should be relatively positioned using the position property with a value of relative.

### Absolute Positioning

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.

### Fixed Positioning

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.

### Floating Elements

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing
element as possible, A lot of layouts place boxes next to each other. The float property is commonly used to achieve this.

### Clearing Floats

The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.

### Screen Sizes & resolution

your design needs to be able to work on a range of different sized screens, and Resolution refers to the number of dots a screen shows per inch

### CSS Frameworks

CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

### Multiple Style Sheets (import)

Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts, colors and so on. by using @import url("path")

### Multiple Style Sheets (link)

```html
On this page you can see the other technique for including multiple style
sheets. Inside the
<head>
  element is a separate
  <link />
  element for each style sheet.
</head>
```

# functions, methods and objects

### function

Functions let you group a series of statements together to perform a specific task.

- function(name)(parameter){
  (code);
  }

- declaring the function by using the function keyword, then the name of the function
- calling a function by typing the name of the function
- declaring a function needs information by giv it parameters inside the function inside parentheses and when you call it you need to write a parameters inside parentheses

### VARIABLE SCOPE

The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.

- LOCAL VARIABLES
- GLOBAL VARIABLES

# 6 Reasons for Pair Programming

pair programming commonly involves two roles:

- the Driver is the programmer who is typing coding, manages the text editor, switching files, version control
- the Navigator uses their words to guide the Driver but does not provide any direct input to the computer, how an algorithm might be converted in to code, while scanning for typos or bugs.

### four fundamental skills that help anyone learn a new programming language:

- Listening
- hearing
- interpreting
- vocabulary

### Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

1. Greater efficiency
   when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code.
1. Engaged collaboration
   if two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
1. Learning from fellow students
   working with a teammate can expose developers to techniques they otherwise would not have thought of.
1. Social skills
   When working with someone who has a different coding style, communication is key, Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills.
1. Job interview readiness
   For most roles, the ability to work with and learn from others and stellar communication skills are as important to a company than specific technical skills. Pair programming strengthens all of those skills.
1. Work environment readiness
   pairing works can hit the ground running at a new job, with one less hurdle to overcome.

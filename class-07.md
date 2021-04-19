# domain

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

# Tables

A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

## Basic Table Structure

- The table element is used to create a table. The contents of the table are written out row by row.
- tr tag. (The tr stands for table row.)
- td element. (The td stands for table data.)
- th element is used just like the td element but its purpose is to represent the heading for either a column or
  a row.

_You can make cells of a table span more than one row or column using the rowspan and colspan attributes._

# Long Tables

- thead The headings of the table should sit inside the thead
  element
- tbody The body should sit inside the tbody element.
- tfoot The footer belongs inside the tfoot element.

# Functions, Methods, and Objects

## constructor object

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvTAK28bBYoVslnh_DWg99XfRIUM1qp_NPcw&usqp=CAU)

the new keyword and the object constructor creat a blank object.

## updating an object

to update the value of property use dot notation or square brackets.

## creating many objects

you can use a function as a tamplet for creating objects. creat the tamplate with properties and methods.

## ADDING AND REMOVING PROPERTIES

You do this using the dot notation To delete a property, you use the keyword delete, and then use dot notation to identify the property or method you want to remove from the object.

## THIS (A KEYWORD)

The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.

## A METHOD OF AN OBJECT

When a function is defined inside an object, it becomes a method. In a method, this refers to the containing object.

## FUNCTION EXPRESSION AS METHOD

If a named function has been defined in global scope, and it is then used as a method of an object, this refers to the object it is contained within.

## STORING DATA

In JavaScript, data is represented using name/value pairs.
To organize your data, you can use:

- VARIABLES
- ARRAYS
- INDIVIDUAL OBJECTS
- MULTIPLE OBJECTS

**arrays are objects**

## WHAT ARE BUILT-IN OBJECTS?

Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.

## STRING O BJECT

Whenever you have a value that is a string, you can use the properties and methods of the String object on that value.
ex:

- PROPERTY: length

  - DESCRIPTION: Returns number of characters in the string
    in most cases

- METHOD: trim()
  - Removes whitespace from start and end of string

## DATA TYPES REVISITED

1. String
2. Number
3. Boolean
4. Undefined
5. Nul
6. object

## MATH OBJECT

The Math object has properties and methods for mathematical constants and functions.

- Math. round()
- Math. sqrt (n)
- Math. ceil ()
- Math. floor()
- Math. random()

## DATE OBJECT (AND TIME)

- getDate()
- getDay ()
- getFullYear()
- getTime()
- getHours ()
- getTimezoneOffset ()

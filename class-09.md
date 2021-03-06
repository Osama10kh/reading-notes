# Forms and JS Events

# Forms

the term 'form' has referred
to a printed document that contains
spaces for you to fill in information.

## Form Controls

- ADDING TEXT:
  - Text input
  - Password input
  - Text area
- Making Choices:
  - Radio buttons
  - Checkboxes
  - Drop-down boxes
- Submitting Forms:
  - Submit buttons
  - Image buttons
- Uploading Files:
  - File upload

## Form Structure

Form controls live inside a
form element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

## Text Input

The input element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.

_another input:_

- Password Input
- Text Area
- Radio Button
- Checkbox
- Drop Down List Box
- File Input Box
- Image Button
- Labelling Form Controls

* Email & URL Input
* Search Input

## Form Validation

when web that give users messages if the form control has
not been filled in correctly; this is
known as form validation.

# Lists, Tables and Forms

## list-style-type

- Unordered Lists
  - disc
  - circle
  - square
- Ordered Lists
  - decimal
  - lower-alpha & upper-alpha
  - lower-roman & upper-roman

## Table Properties

- border-top, border-bottom
- :hover
- text-align
- padding
- Give cells padding
- Distinguish headings
- Align numerals

## Cursor Styles

- auto
- crosshair
- default
- pointer
- move
- text
- wait
- help
- url("cursor.gif");

# Events

## DIFFERENT EVENT TYPES

- UI EVENTS
  - load: Web page has finished loading
  - unload: Web page is unloading (usually because a new page was requested)
  - error: Browser encounters a JavaScript error or an asset doesn't exist
  - scroll User has scrolled up or down the page
- KEYBOARD EVENTS
  - keydown: User first presses a key (repeats while key is depressed)
  - keyup User releases a key
  - keypress Character is being inserted (repeats while key is depressed)
- MOUSE EVENTS
  - click: User presses and releases a button over the same element
  - mouseup: User releases a mouse button while over an element
  - mouseover: User moves the mouse over an element (not on a touchscreen)
  - mouseout: User moves the mouse off an element (not on a touchscreen)
- EVENTS TRIGGER SCRIPTS
  - FOCUS EVENTS
  - focus / focus in :focus / focus in
  - blur / focusout: Element loses focus
  - FORM EVENTS
  - input
  - change
  - reset
  - copy
  - select

## HOW EVENTS TRIGGER JAVASCRIPT CODE

1. Select t he element node(s) you want the script to respond to.
1. Indicate which event on the selected node(s) will trigger the response
1. State the code you want to run when the event occurs.

![](data:image/png;base64,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)

## THE EVENT OBJECT

When an event occurs, the event object tells
you information about the event, and the
element it happened upon.

## EVENT DELEGATION

Creating event listeners for a lot of elements
can slow down a page, but event flow allows
you to listen for an event on a parent element.

## CHANGING DEFAULT BEHAVIOR

The event object has methods that change:
the default behavior of an element and how
the element's ancestors respond to the event.

- prevent Default()
- stopPropagation()
- USING BOTH METHODS

## DIFFERENT TYPES OF EVENTS

- USER INTERFACE EVENTS
- FOCUS & BLUR EVENTS
- MOUSE EVENTS
- KEYBOARD EVENTS
- FORM EVENTS
- MUTATION EVENTS
- HTM LS EVENTS

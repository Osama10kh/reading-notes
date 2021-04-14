# Images

```html
To add an image into the page you need to use an <img /> element and inside it
src="" This tells the browser where it can find the image file alt="" This
provides a text description of the image You can also use the title attribute
with the <img /> element to provide additional information about the image.
```

## Height & Width of Images

- height This specifies the height of the image in pixels.
- width This specifies the width of the image in pixels.

Where an image is placed in the code will affect how it is displayed. Here are three examples of image placement that produce different results.

## Aligning Images Horizontally

align chapter-05/aligning-images-horizontally.html HTMLThe align attribute was commonly used to indicate how the other parts of a page should flow around an image. The align attribute can take these horizontal values:

- left
- right

## Three Rules for Creating Images

- Save images in the right format
- Save images at the right size
- Use the correct resolution

## Tools to Edit & Save Images

The most popular tool amongst web professionals is Adobe Photoshop.

- Other Software
- Adobe Fireworks
- Pixelmator
- PaintShop Pro
- Paint.net
- Online Editors
- www.photoshop.com
- www.pixlr.com
- www.splashup.com
- www.ipiccy.com

## Cropping Images

When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible.

- PORTRAIT
- ANDSCAPE

## Animated GIFs

Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations.

## Figure and Figure Caption

```html
*
<figure>
  Images often come with captions.
  <figure>
    element to contain images and their caption so that the two are associated *
    The
    <figcaption>
      element allow web page authors to add a caption to an image.
    </figcaption>
  </figure>
</figure>
```

# Color

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

- rgb values : These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,200,300).
- hex codes : These are six-digit codes that
  represent the amount of red, green and blue in a color,
  preceded by a pound or hash # sign. For example: #ee3e80.
- color names There are 147 predefined color names that are recognized by browsers. For example: Dark.

**background-color**
background-color is a property sets the color of the background for that box.You can specify your choice of
background color in the same three ways.

**color**
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.

- Hue :Hue is near to the colloquial idea of color.
- Saturation: Saturation refers to the amount of gray in a color.
- Brightness:Brightness (or "value") refers
  to how much black is in a color.

**opacity**
CSS3 introduces the opacityproperty which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5is 50% opacity and 0.15 is 15% opacity).
**HSL Colors**
to specify colors using hue, saturation, and lightness values.
the lightness is Lightness is the amount of
white (lightness) or black (darkness) in a color.

# Text

The properties that allow you to control the appearance of text can be split into two groups:

- Those that directly affect the font
- Those that would have the same effect on text no matter what font you were using

## Typeface Terminology

- Serif
- Sans-Serif
- Monospace

## Weight

- Light
- Medium
- Bold
- Black

## Style

- Normal
- Italic
- Oblique

## Stretch

- Condensed
- Regular
- Extended

## Techniques That Offer a Wider Choice of Typefaces

There are several ways to use fonts other than those listed on the previous page. However, typefaces are subject to copyright, so the
techniques you can choose from are limited by their respective licenses.

- font-family
- font-face
- Service-based Font-Face

## Specifying Typefaces

- font-family
  - The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
- Size of Type
  - font-size
    - The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:
      - pixels
      - percentages
      - ems
- More Font Choice
  - @font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to
    specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.
    - font-family
    - src
    - format

## Font Format

- Bold
- rticle

## UpperCase & LowerCase

The text-transform property is used to change the case of text giving it one of the following values:

- uppercase
- lowercase
- capitalize

## text-decoration

- none
- underline
- overline
- line-through
- blink

## letter-spacing, word-spacing

Kerning is the term typographers use for the space between each letter. You can control the space between each letter with the letter-spacing property.

## text-align

- left
- right
- center
- justify

## text-indent

The text-indent property allows you to indent the first line of text within an element.

## text-shadow

The text-shadow property has become commonly used despite lacking support in all browsers.

## Styling Links

- link This allows you to set styles for links that have not yet been visited.
- visited This allows you to set styles for links that have been clicked on.

### Responding to Users

- hover This is applied when a user hovers over an element with a pointing device such as a mouse.
- active This is applied when an element is being activated by a use
- :focus This is applied when an element has focus. Any element that you can interact with

## Attribute Selectors

- Existence
- Equality
- Space
- Prefix

# JPEG vs PNG vs GIF

- Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth
- Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges
- GIF format for images that contain animations.

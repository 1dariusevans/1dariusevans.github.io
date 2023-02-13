Topic: Cascading Style Sheets (CSS)

CSS allows you to create great-looking web pages

What is CSS purpose?
CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML. Presenting a document to a user means converting it into a form usable by your audience. 

CSS can be used for very basic document text styling — for example, for changing the color and size of headings and links. It can be used to create a layout. It can even be used for effects such as animation.

<https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS>

How to apply CSS?

There are three ways of inserting a style sheet:
External CSS
Internal CSS
Inline CSS

    External CSS:
    With an external style sheet, you can change the look of an entire website by changing just one file! Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section. An external style sheet can be written in any text editor, and must be saved with a .css extension. The external .css file should not contain any HTML tags.

    Internal CSS:
    An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the <style> element, inside the head section.

    Inline CSS:
    An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Cascading Order 

What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

Inline style (inside an HTML element)
External and internal style sheets (in the head section)
Browser default

Source: <https://www.w3schools.com/css/css_howto.asp>

## Things I want to know more about:
Actually using the CSS in all three ways to see which one suits me the best. 



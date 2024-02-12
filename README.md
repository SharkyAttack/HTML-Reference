# Practice-html
 practicing with html and css


<HTML NOTES>

----------------------------------------------------------------
ELEMENTS
----------------------------------------------------------------
<ElementName></ElementName> <-All elements have an opening and closing tag.
<p>My cat is <strong>very</strong> grumpy.</p> <-example: elements can be nested within elements.

Void Elements are elements that don't have a closing tag.
- <area <!--defines an area inside animage map that has predefined clickable areas. -->
    alt="sting of text to describe element if image cannot be displayed"
    coords=""
        rect=""
        poly=""
        circle=""
    download=""
    href=""
    ping=""
    referrerpolicy=""
    rel=""
    shape=""
    target=""
- <base> <- specifies the base URL to use for all relative URLs in a document. Only 1 base can be used.
- <br> <- line break
- <col> <- used as a child for <colgroup>
- <embed> <-embeds external content at specific point in document.
- <hr> <-a thematic break between paragraph-level elements for change in scene, topic, or shift in topic.
- <img> <-embeds image
- <input> <-interactive element to accept data from user.
- <link> <-used to link resources to document (Favicon, stylesheets, etc...).
- <meta> <- represents metadata that cannot be represented by other meta-related elements.
- <param> <- Deprecated.
- <source> <-Media or Image Source element - specifies one or more media resources.
- <track> <- Child of <audio> and <video>
- <wbr> <- creates a break in a word.
html does not use self-closing tags but you can use them for the elements to be compatible with XML, XHTML, and SVG.
- Example of self closing tag: <input type="text" /> or <circle cs="50" cy="50" r="5-" />
----------------------------------------------------------------

----------------------------------------------------------------
Attributes
----------------------------------------------------------------
Elements can have attributes.
attributes may be ignored if they serve no purpose.
----------------------------------------------------------------

----------------------------------------------------------------
Web Page
----------------------------------------------------------------
<!DOCTYPE html>         <-specifies Document type.
<html><html/>           <-Surrounds html whole document.
<head>                  <-Container for everything you want to include in the document that doesn't appear in the doc.
    <title></title>     <-This shows up on browser tab.
<body>                  <-Everything visible in document
</body>
</head>           

----------------------------------------------------------------
- Typing Special characters (Reference): https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references
- Comments: <!-- comments here -->
- 
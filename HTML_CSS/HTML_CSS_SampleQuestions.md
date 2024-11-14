# Basic Web Techniques

## Reading Assignment 2: WWW and HTML
Mido Zieser-Zerenko
3ACIF/T

### Html

#### 1. Name the components of html elements properly
Element, Start-tag, Content, End-tag, Attributes, Nesting, Comments

---
#### 2. Identify void elements and how they are denoted
"Self-closing elements": They do not have a closing tag and have no content
Area, base, br, col, embed, hr, img, input, link, meta, source, 

---
#### 3. Identify attributes
Written inside the Start-Tag as a name-value pair

&lt;a href="www.com" target="_blank"&gt;Click&lt;/a&gt;

---
#### 4. Write down the correct ``DOCTYPE`` declaration for html 5
&lt;!DOCTYPE html&gt;

---
#### 5. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
   &lt;article&gt;This is an article content.&lt;/article&gt;

   - Body (``<body>``)
   &lt;body&gt;This is the content of the body.&lt;/body&gt;

   - line break (``<br/>``)
   &lt;br/&gt;

   - Headings (``<h1>``, ...)
   &lt;h1&gt;Main Heading&lt;/h1&gt;
   &lt;h2&gt;Subheading&lt;/h2&gt;

   - Section with meta-information (``<head>``)
    &lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="description" content="This is a webpage description"&gt;
    &lt;title&gt;My Page Title&lt;/title&gt;
    &lt;/head&gt;

   - Top level element (``<html>``)
   &lt;html lang="en"&gt;Content of the page&lt;/html&gt;

   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   &lt;img src="Team.jpg" alt="Team Image"&gt;

   - Paragraph (``<p>``)
   &lt;p&gt;This is a paragraph of text.&lt;/p&gt;

   - Section (``<section>``)
   &lt;section&gt;This is a section of content.&lt;/section&gt;

   - Label appearing in the title bar (``<title>``)
   &lt;title&gt;My Webpage Title&lt;/title&gt;

   - Link to other pages (``<a>``)
   &lt;a href="https://www.example.com"&gt;Visit Example&lt;/a&gt;

   - Comment
   &lt;!-- This is a comment. --&gt;

   - Head with title and meta elements
    &lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;My Page Title&lt;/title&gt;
    &lt;/head&gt;

---

## Css

#### 1. Name the components of a css rule properly
Selector (targets elements) and declarations => properties(color, alignment) and values
Selector and declaration in {}   
Property; Value; separated

---
#### 2. Use combinators properly: direct child, descendant, adjacent sibling, sibling
Combinators, the relationship between selectors. 
Descendant (empty): div p -> all p elements in div
Child (>): p > div, only direct children
Adjacent sibling(+): h1 +p, the first p that follows h1
General sibling(~): h1 ~ p, all p elements that are siblings of h1 and come after

---
#### 3. Specify colors by color names and in hexadecimal notation
- .red {
    color: red; 
    background-color: #FF0000; 
        }

- .blue {
    color: blue; (name)
    background-color: #0000FF;
        }



---
#### 4. Declarations for color, background color
ABC {background-color: yellow;}
XYZ {color: red;}

---
#### 5. Pseudo classes for the ``<a>`` element
Special keywords for special states of elements (interactive)
Hover, First-Child, n-th Child, Focus (input field)

---
#### 6. Declaration for background image
element { background-image: url('path/img.jpg'); }

---
#### 7. Declaration for text alignment (left, right, center, justify)
{ text-align: right/left/center/justify; }
justify: stretch text to fit container

---
#### 8. Declaration for text decoration (overline, underline, line-through)
{text-decoration: underline/overline/line-through;}
Can be combined by adding two keywords separated by a space
(also: text-decoration-color/-style/-thickness)

---
#### 9. Declaration for text transformation (uppercase, lowercase, capitalize)
{text-transform: value/uppercase/lowercase/capitalize/none;}

---
#### 10. Identify the difference between serif and sans-serif fonts
Serif has little overhanging elements on the edge of the letters and sans-serif has straight edges

---
#### 11. Declarations for font families
{font-family: 'Times New Roman', 'Fallback Font1', '...', serif/sans-serif/monospace; }

---
#### 12. Declarations for font style normal and italic
{font-style: italic/normal/oblique}

---
#### 13. Declarations for font sizes
{font-size: 24px; }

---
#### 14. Declarations for font weights
{ font-weight: bold; }

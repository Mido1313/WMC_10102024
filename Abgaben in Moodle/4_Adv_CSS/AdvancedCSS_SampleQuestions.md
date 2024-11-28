# Sample Questions - Basic Web Techniques - Advanced CSS

## Box Model

### 1. Block elements have which kind of characteristics?
Take up the entire width of their parent container and start on a new line.
Example: article, section, p, h1-6, div

---

### 2. Inline elements have which kind of characteristics?
Do not start on a new line and only take up as much width as their content
requires. Examples: img, strong, em, span

---
### 3. What is the margin of an Html element? Where can one find it?
Space outside the border, separating this element from others

---
### 4. What is the padding of an Html element? How does it differ from margin?
 Space between the content and the border. It's inside the border the margin is on the outside

---

## Classes and Ids

### 1. Write down a selector for a certain class
.classname {
    /* CSS properties */
}


---
### 2. Write down a selector for a certain html element of a certain class
element.classname {
    /* CSS properties */
}dv_

---
### 3. Write down a selector for a certain id

(HTML) ID: <br>
&lt;div id="myElement"&gt; (...)
    &lt;/div&gt;

 (CSS) IDSelector: <br>
#myElement { <br>
    background-color: lightblue; 
    <br>padding: 10px;
}


---
### 4. Write down a selector for a certain html element of a certain id

div#myElement { <br>
    background-color: lightblue; <br>
    padding: 10px;
}

---
### 5. Write down the start tag of a certain html element with a specific class.
&lt;div class="myClass"&gt;


---
### 6. Write down the start tag of a certain html element with a specific id.
&lt;div id="myElement"&gt;


--- 
### 7. Do classes select one or more elements?
In HTML and CSS, classes are used to select multiple elements, 
but they can also be used to target a single element. 
It depends on how many elements are assigned the same class name.

---
### 8. Do ids select one or more elements?
Only one element

---
### 9. How often can classes / ids occur on one page?
Class: <br> Can be used multiple times on a single page.
A class can be assigned to many elements, 
and the same class can appear on any number of elements.

IDs: <br> Should be unique on a page.
An ID must only be assigned to one element on a page, 
according to the HTML specification. 
This means that no two elements can have the same ID 
in the same HTML document.

---

## Floating

### 1. Write down the css declaration to make an html element float to the left
element {
    float: left;
}

---
### 2. Make an html element stop floating around another (for a specific direction)


.clear-left {
    clear: left;
}

.clear-right {
    clear: right;
}


### (for all directions)

.clear-both {
    clear: both;
}

---


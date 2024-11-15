# Basic Web Techniques - Lists and Tables

## Html for Lists
---
1. Start tags for
   - an ordered list
      <br> &lt;ol&gt; &lt;li&gt;
   - an unordered list
   <br> &lt;ul&gt; &lt;li&gt;
   - a description list
   <br> &lt;dl&gt; &lt;dt&gt; &lt;dd&gt;
   - a list item
   <br> &lt;li&gt;
   - a description term
   <br> &lt;dt&gt;
   - a description data
   <br> &lt;dd&gt;
   ---
## Css for Lists
---
#### 1. Make bullet a square
ul {list-style-type: square; }

---
#### 2. Make bullet an image named "my-bullet.png"
ul {list-style-type: url('path/of/image.png'); }

---
#### 3. Make bullet an uppercase roman number
ul {list-style-type: upper-roman; }

---
#### 4. Set bullet position to be inside the list item's text flow
ul {list-style-position: inside; }

---
#### 5. Set bullet position to be outside the list item's text flow
ul {list-style-position: outside; }

---

## Html for Tables
---
#### 1. Start tags for
   - a table
     &lt;table&gt;
   - a table row
     &lt;tr&gt;
   - a table header
     &lt;thead&gt;
   - a table header cell
     &lt;th&gt;
   - a table body
     &lt;tbody&gt;
   - a table cell
    &lt;td&gt;
   - a table footer
   &lt;tfoot&gt;
   - a table footer cell
   &lt;tfoot&gt; &lt;tr&gt; &lt;td&gt;
---
## Css for Tables
---
#### 1. Black dotted border of 1 px width.
th, td { border: 1px dotted/solid black; }

---
#### 2. Solid border of 1 px width having a red color and rounded corners
border: 1px solid red;
border-radius: 8px;

---
#### 3. Merge the borders of table cells so that they appear as one line
table {border-collapse: collapse; }

---

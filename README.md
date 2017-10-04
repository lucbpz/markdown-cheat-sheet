THE ULTIMATE MARKDOWN CHEAT SHEET
===
Hello everyone! I just needed a Markdown cheat sheet and neither of the ones here resolved my problems when I had to write my article, so I decided to create my own. Really simple and condensed so you don't have to go to other resource to complete your writing!

Some of the features may not be available as they are from Extended Markdown.

Download my cheat sheet here!
https://www.cheatography.com/lucbpz/cheat-sheets/the-ultimate-markdown/

I suggest using VS Code and the extension "Auto-Open Markdown Preview".

---

# HEADERS


```
Heading Level 1
========
Heading Level 2
------­-----
Another way:
# Header1
## Header2
### Header3
...
```

Heading Level 1
========

Heading Level 2
--------

Another way:
# Header1
## Header2
### Header3

---

# PARAGRAPHS < p >

```
Paragraphs are lines of text
(single returns are collapsed into a space)

Blank lines indicate a new paragraph
```

Paragraphs are lines of text
(single returns are collapsed into a space)

Blank lines indicate a new paragraph

---

# TEXT EFFECTS

```
**bold**
*italic*
~~strikethrough~~
```
**bold**
*italic*
~~strikethrough~~

---

# CODE 

```
Simple html < code > text: `code`

Code block (< pre >) in a certain language:
``` javascript
if (isBad) {
return false
}
```

Simple html < code > text: `code`

Code block (< pre >) in a certain language:
``` javascript
if (isBad) {
return false
}
```

---

# HORIZONTAL RULE < hr />

```
---
- - -
```
---

---

# LINKS & LINK TO A SECTION

```
[Text that will link to a websit­e.]­(h­ttp­://­www.we­b.com)
[Text that will link to the section images](#images)

This will link the text to the "­Images­" header. Use - instead of spaces for the link.
You can also organize all your links like this:
[math.s­ta­cke­xch­ang­e.c­om][1]
[link.n­um­ber.tw­o][2]

[1]: http:/­/ma­th.s­ta­cke­xch­ang­e.com/
[2]: http:/­/we­bsi­te.com
```

[Text that will link to a website](http://www.web.com)

[Text that will link to the section images](#images)

This will link the text to the "­Images­" header. Use - instead of spaces for the link.
You can also organize all your links like this:

[math.s­ta­cke­xch­ang­e.c­om][1]

[link.n­um­ber.tw­o][2]

[1]: http:/­/ma­th.s­ta­cke­xch­ang­e.com/
[2]: http:/­/we­bsi­te.com

---

# IMAGES

```
![Image of dog](https://upload.wikimedia.org/wikipedia/commons/8/8a/Too-cute-doggone-it-video-playlist.jpg)
```

![Image of dog](https://upload.wikimedia.org/wikipedia/commons/8/8a/Too-cute-doggone-it-video-playlist.jpg)

---

# UNORDERED LIST < ul > < li >

```
* First bullet
* Second bullet
* * Second.1 bullet
```
* First bullet
* Second bullet
* * Second.1 bullet

---

# ORDERED LIST < ol > < li >

```
1. First item
2. Second item
3. Third item
```
1. First item
2. Second item
3. Third item

---

# TABLES 

```
| Item | Value | Qty |
| :------- | ----: | :---: |
| Computer | $1600 | 5 |
You can specify alignment with : at one or both sides
```
| Item | Value | Qty |
| :------- | ----: | :---: |
| Computer | $1600 | 5 |
You can specify alignment with : at one or both sides

---

# ADDING ICONS

```
<i class=­"­ico­n-f­ile­"­></­i> Create a document

This would add the icon  before the text
```
<i class=­"­ico­n-f­ile­"­></­i> Create a document

This would add the icon  before the text

---

# KEYBOARD KEYS

```
<kbd>Ctrl+Shift+F1</kbd>
```
<kbd>Ctrl+Shift+F1</kbd>

---

# TABLE OF CONTENTS

```
You can insert a table of contents using the
marker 

[TOC]
```
You can insert a table of contents using the
marker 

[TOC]

---

# FOOTNOTES 

```
You can create footnotes like
this[^footnoteName].

[^footnoteName]: Here is thetext of the
footnote.

Every time you create a footnote it
automatically sets the text at the bottom of the
page and link them together
```
You can create footnotes like
this[^footnoteName].

[^footnoteName]: Here is thetext of the
footnote.

Every time you create a footnote it
automatically sets the text at the bottom of the
page and link them together

---

# DEFINITION LIST

```
Belongs to this term
: This definition

First, write the syntax for the definition
```
Belongs to this term
: This definition

First, write the syntax for the definition

---

# FLOWCHARTS

```
st=>start: Start
e=>end
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...
st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
You can have more info at: http://flowchart.js.org/
```
st=>start: Start

e=>end

op1=>operation: My Operation

sub1=>subroutine: My Subroutine

cond=>condition: Yes

or No?:>http://www.google.com

io=>inputoutput: catch something...

st->op1->cond

cond(yes)->io->e

cond(no)->sub1(right)->op1

You can have more info at: http://flowchart.js.org/

---

# SEQUENCE DIAGRAMS

```
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
You can have more info at: https://bramp.github.io/js-sequence-diagrams/
```

Andrew->China: Says Hello

Note right of China: China thinks\nabout it

China-->Andrew: How are you?

Andrew->>China: I am good thanks!

You can have more info at: https://bramp.github.io/js-sequence-diagrams/

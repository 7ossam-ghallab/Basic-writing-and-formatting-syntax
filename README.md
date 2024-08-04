<h1><mark style="background-color: #444;">Headings</mark></h1>

`# A first-level heading` !!(It needs to be written from the start of the line)
# A first-level heading  


`## A second-level heading` !!(It needs to be written from the start of the line)
## A second-level heading 

`### A third-level heading` !!(It needs to be written from the start of the line)
### A third-level heading 

<hr>

<h1><mark style="background-color: #444;">Styling text</mark></h1>

`**Bold** or __Bold__`  ====>> **Bold** or __Bold__

`*Italic* or _Italic_ ` ====>> *Italic* or _Italic_

`~~Strikethrough~~`  ====>> ~~Strikethrough~~

`**Bold and nested _italic_**`  ====>> **Bold and nested _italic_**

`***All bold and italic***`  ====>> ***All bold and italic***	

`This is a <sup>superscript</sup> text`  ====>> This is a <sup>superscript</sup> text  | 2<sup>4</sup>

`This is a <sub>subscript</sub> text`  ====>> This is a <sub>subscript</sub> text  | H<sub>2</sub>O

<hr>

<h1><mark style="background-color: #444;">Quoting</mark></h1>

### TEXT
`> Text that is a quote` !!(It needs to be written from the start of the line)
> Text that is a quote

### CODE
1. Line Of Code

``Use `git status` to list all new or modified files that haven't yet been committed.``

Use `git status` to list all new or modified files that haven't yet been committed


2. Block Of Code

* Without Highlighting

````
```
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World";
  return 0;
}
```
````
```
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World";
  return 0;
}
```


* With Highlighting

````
```c++
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World";
  return 0;
}
```
````
```c++
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World";
  return 0;
}
```

<hr>

### LINK

`This site was built using [GitHub Pages](https://pages.github.com/).`

This site was built using [GitHub Pages](https://pages.github.com/).

<hr>

### IMAGES

`![Hello World](<img decoding="async" src="https://via.placeholder.com/300x250/333/FFF?text=Hello+World" alt="">)`


![Hello World](https://via.placeholder.com/300x250/333/FFF?text=Hello+World)


`<img alt="Hello World" src="https://via.placeholder.com/300x250/333/FFF?text=Hello+World">`


<img alt="Hello World" src="https://via.placeholder.com/300x250/333/FFF?text=Hello+World">

<hr>

### Lists

```
- George Washington
* John Adams
+ Thomas Jefferson
```
Result 
- George Washington
* John Adams
+ Thomas Jefferson


```
1. James Madison
2. James Monroe
3. John Quincy Adams
```
Result 
1. James Madison
2. James Monroe
3. John Quincy Adams


```
1. First list item
TAB - First nested list item
2TABS   - Second nested list item
```
Result 
1. First list item
    - First nested list item
        - Second nested list item

<hr>

### Alerts

```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<hr>

### Hiding content with comments

`<!-- This content will not appear in the rendered Markdown -->`

<!-- This content will not appear in the rendered Markdown -->

<hr>

### Ignoring Markdown formatting

`Let's rename \*our-new-project\* to \*our-old-project\*.`

Let's rename \*our-new-project\* to \*our-old-project\*.

<hr>

### Task lists

```
- [x] Task one
- [ ] Task two 
- [ ] Task three
```
- [x] Task one
- [ ] Task two 
- [ ] Task three

<hr>

### Using emojis

`:white_heart:`
:white_heart:

<hr>

### Footnotes

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

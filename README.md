Markdown/formatting required blocks
---

Open [RAW](https://github.com/AbsurdlySuspicious/markdown-showcase/blob/master/README.md?plain=1) to see actual formatting

- [Headings](#headings)
- [Heading H1](#heading-h1)
  - [Heading H2](#heading-h2)
    - [Heading H3](#heading-h3)
      - [Heading H4](#heading-h4)
        - [Heading H5](#heading-h5)
          - [Heading H6](#heading-h6)
- [Paragraph](#paragraph)
- [Text inline styles: emphasis, etc.](#text-inline-styles-emphasis-etc)
  - [Sub- and superscript (GFM)](#sub--and-superscript-gfm)
- [Page divider](#page-divider)
- [Lists](#lists)
  - [Un-numbered](#un-numbered)
  - [Numbered](#numbered)
  - [Checbox lists](#checbox-lists)
- [Code](#code)
  - [Code block](#code-block)
  - [Inline code](#inline-code)
- [Quotes](#quotes)
  - [Default block-quote](#default-block-quote)
  - [Nested block-quotes](#nested-block-quotes)
  - [Note quotes (GFM)](#note-quotes-gfm)
  - [Icon quotes (Proposal)](#icon-quotes-proposal)
- [Tables](#tables)
  - [Simple tables](#simple-tables)
  - [Complex table (GFM)](#complex-table-gfm)
- [Spoilers / foldables (GFM)](#spoilers--foldables-gfm)
    - [Sir, Prize!](#sir-prize)
- [Images](#images)
- [Alignment](#alignment)
  - [Images + text](#images--text)
  - [Text only](#text-only)


[ Actual example starts below this line ]

# Headings

# Heading H1
content
## Heading H2
content
### Heading H3
content
#### Heading H4
content
##### Heading H5
content
###### Heading H6
content

# Paragraph

Single line paragraph

Multi-line paragraph  
with arbtrary linefeeds like  
this

Multi-line paragraph with auto linefeeds/hyphenation: Lorem ipsum odor amet, consectetuer adipiscing elit. Vivamus ipsum odio mauris consequat odio dapibus. Vitae nisl ullamcorper augue nulla consectetur eu placerat netus phasellus. Augue ad justo in fermentum tristique. Mollis vivamus arcu, velit tristique rhoncus volutpat sed sed! Posuere eu suscipit dictum enim ex id inceptos dolor? Ornare volutpat augue tempor ligula nostra eros commodo? Aliquet orci class potenti gravida inceptos class.

# Text inline styles: emphasis, etc.

Normal text and **bold text** and *italic text* and `inline monospace text`

Em*phas*is in a mi**dd**lle o**f** a w*or*d

Combined emphasis: **bold**, *italic*, ***italic bold***, *italic with **bold** in the middle*, **bold with *italic* in the middle**

Links [with text](https://google.com) and raw (auto) url links: https://google.com

## Sub- and superscript (GFM)

SuperScript<sup>You *can* use **markdown** in ***superscript***</sup>

SubScript<sub>You *can* use **markdown** in ***subscript***</sub>

13<sup>37</sup>

# Page divider

Before divider

---

After divider

# Lists

## Un-numbered

- Un-numbered
  - Nested
    - List
      - even more nested
        -  more more nested
- Can have multi-  
  line content
  - And nested content
  - And nested  
    multiline content 
- `and nested inline` **sty**l*es*

## Numbered

1. Numbered list
   1. Nested as well
      1. Really nested
         1. Very nested
            1. Very very nested
      2. 3rd level 2nd line
      3. 3rd level 3rd line
   2. 2nd level 2nd line
   3. 2nd level 3rd line
2. 1st level 2nd line
3. 1st level 3rd line
4. Can have multiline  
   content as well
   1. Nested  
      Too


## Checbox lists

- [ ] Checkbox item
- [x] Checked checkbox item
  - [ ] Nested
  - [x] Nested checked
    - [ ] Very nested
    - [x] Very nested checked
- [ ] Another

# Code

## Code block

```
Monospace block as ordinary text without formatting
Can be multiline without double-spacing
No other markdown works inside
# asd 
*qwe*
```

```python
def __meme__():
    """
    Code block with syntax highlight (python)
    """
```

```javascript
var meme = 1337 // Code block with syntax highlight (js)
console.log(meme)
```

```html
<html>
    <!-- Code block with syntax highlight (html) -->
</html>
```

## Inline code

See `Text inline styles` above. Inline code can't have syntax highlight `<html></html>`

# Quotes

## Default block-quote

Single-line:

> Single-line quote

> Muliline quote  
> Foo bar baz

## Nested block-quotes

> 1st level quote
> > 2nd level quote some othe guy said something  
> > multiline
>
> and more shit below
>
> > 2nd level again
> > > and even 3rd level idc anymore  
> > > yeee
> >
> > back to 2nd level  
> > qwe
>
> > separate 2nd level  
> > right next to previous
>
> 1st again

## Note quotes (GFM)

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

## Icon quotes (Proposal)

TBD

# Tables

## Simple tables

| Column 1                      | Column 2       | Column 3                |
| ----------------------------- | -------------- | ----------------------- |
| all cols                      | are            | left aligned by default |
| can have *embedded*           | **formatting** | and `code`              |
| And cells can be<br>multiline | foo            | bar                     |


| Column 1               |           Column 2            |                Column 3 |
| :--------------------- | :---------------------------: | ----------------------: |
| Left aligned col       |        center aligned         |           right aligned |
| Lorem ipsum odor amet, | consectetuer adipiscing elit. | Vivamus ipsum  dapibus. |
| 3rd                    |             line              |                    meme |
| 4th                    |             line              |                  foobar |

## Complex table (GFM)

 <table>
  <tr><th>HTML</th><th>Tables</th><th colspan="2">Are Possible</th></tr>
  <tr><th colspan="2">Dessert:</th><td>Jello</td><td>Whirrled</td></tr>
  <tr><td colspan="4" align="center">And more flexible</td></tr>
  <tr><td colspan="4" align="center">since you can use colspan</td></tr>
  <tr><td>And</td><td rowspan="2" colspan="2" align="center">rowspan</td><td>To</td></tr>
  <tr><td>Also</td><td>Boot</td></tr>
 </table>

# Spoilers / foldables (GFM)

GFM spoiler:

<details><summary><b>Click here</b> for a <i>surprise</i>!</summary>

   
**I'm hidden till I'm not, then**
   
### Sir, Prize!
   
meme

**There's no indication for spoiler content end, but probably should be**

</details>

*Text after spoiler content*

<details><summary>Spoiler with divider at the end</summary>
foo  
bar
baz

divider:

---

</details>

*Text after spoiler content (2)*

# Images

Inline-style: ![alt text qwe asd](https://avatars.githubusercontent.com/u/42009457?s=40&v=4 "Hover text blah blah blah") (has hover text)

Regular image (small):

![alt text 2](https://avatars.githubusercontent.com/u/42009457?s=400&u=2dcba5c146315f82f802b8b58e92a4d6b82344b3&v=4)

Regular image (bigger):

![totally cool video](https://img.youtube.com/vi/dQw4w9WgXcQ/maxresdefault.jpg)

# Alignment

## Images + text

Center aligned image:

<p align="center">
<img src="https://picsum.photos/100/100">
</p>

---

<img align="left" width="100" height="100" src="https://picsum.photos/100/100">
left aligned image with text<br>
incl. multiline

<p style="clear: both;">

---

<img align="right" width="100" height="100" src="https://picsum.photos/100/100">
right aligned image with text<br>
incl. multiline

<p style="clear: both;">

---

<img align="right" width="100" height="100" src="https://picsum.photos/100/100">
<p align="right">
right aligned image<br>with right-aligned text<br>
incl. multiline
</p>

<p style="clear: both;">

---

## Text only

Center aligned:

<p align="center">Center aligned paragraph<br>Multiline</p>


Right aligned:

<p align="right">Right aligned paragraph<br>Multiline</p>

---
<p align="center"><b>END</b></p>

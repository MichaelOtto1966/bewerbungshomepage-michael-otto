---
title: Markdown Test
description: A simple test for markdown-it to see if Markdown parsing really works for this blog.
img: https://cdn.glitch.com/3c6dab22-6538-4353-88a5-4b27b47151ef%2Faachen_dom.jpg?v=1622109470341
date: 16.03.2022
---

This a test of all markdown possibilities:

---

## Headings

# h1 Heading 1

## h2 Heading 2

### h3 Heading 3

#### h4 Heading 4

##### h5 Heading 5

###### h6 Heading 6

---

## Horizontal Rules

---

---

---

---

## Emphasis

**This is bold text**

**This is bold text**

_This is italic text_

_This is italic text_

~~Strikethrough~~

---

## Links

[link text][1]

[link with title][2]

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

There is no way to open links in a new tab with markdown.

You have to write this: **`<a href="https://wiki.selfhtml.org" target="_blank">SelfHTML-Wiki</a>`** -> This Link opens a new Tab

---

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

---

## Indentation

indentation 1-1

indentation 1-2
indentation 2-1

---

## Lists

### Unordered

- Create a list by starting a line with `+`, `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    - Ac tristique libero volutpat at
    * Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
- Very easy!

### Ordered

#### Numers in sequence

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

#### Numers not in sequence

1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

---

## Images

![Minion][3]
![Stormtroopocat][4]

Like links, Images also have a footnote style syntax

![Alt text][5]

With a reference later in the document defining the URL location:

---

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

---

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code

Block code "fences"

```
Sample text here...
```

Syntax highlighting

```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

[1]: http://dev.nodeca.com
[2]: http://nodeca.github.io/pica/demo/ "title text!"
[3]: https://octodex.github.com/images/dinotocat.png
[4]: https://octodex.github.com/images/saritocat.png "The Stormtroopocat"
[5]: https://octodex.github.com/images/daftpunktocat-thomas.gif "The Dojocat"

---
title: Markdown Lightweight Markup Language
summary: Convenience and Simplicity
date: 2025-03-22
authors:
  - admin
tags:
  - Week
  - News
  - Blog
image:
  caption: 'Image credit: [Markdown](https://ru.wikipedia.org/wiki/Markdown#/media/%D0%A4%D0%B0%D0%B9%D0%BB:Markdown-mark.svg)'
---

Convenience and Simplicity

## Markdown

Markdown is a lightweight markup language created to indicate formatting in plain text, with maximum preservation of its human readability, and suitable for machine transformation into advanced publishing languages ​​(HTML, Rich Text, and others).

## History

Originally created in 2004 by John Gruber and Aaron Swartz, many of the ideas for the language were borrowed from existing email markup conventions. Markdown implementations convert Markdown text to valid, well-formed XHTML and replace left angle brackets ("<") and ampersands ("&") with the appropriate entity codes. The first implementation of Markdown was Gruber's Perl implementation, but many third-party implementations have appeared since then (see below). The Perl implementation is licensed under a BSD-type license. Markdown implementations in various programming languages ​​are included (or available as a plugin) in many content management systems.

## Syntax Examples

The following are examples of how to use Markdown, but this is not a complete guide. A full description of the language can be found on the official website. Characters that are normally treated as special in Markdown can be escaped with a backslash. For example, the sequence "\*" will output the "*" character, rather than indicating the start of selected text. Also, Markdown does not convert text inside "raw" XHTML blocks. Thus, you can include XHTML sections in a Markdown document by enclosing them in block-level tags.

## Text with emphasis or logical stress

```
*emphasis* (e.g., italics)
**strong emphasis** (e.g., bold)
```

## Program code

Code elements can be inline or multi-line blocks. Inline code is marked with the "`" (backtick) character.
An example of inline code is `Hello world!`. A multi-line code block is indented by 4 spaces or one Tab.

Below begins a multi-line code block

```
    <!doctype html>
    <html>
        <head>
            <!-- Заголовок документа -->
        </head>
        <body>
            <!-- Тело документа -->
        </body>
    </html>
```
Code block ended

## Strikethrough text

`need to do ~~one~~other thing`

## Lists

```
* bulleted list item
- another unordered list item
+ item bullets can be different
```

```
1. Numbered list item
2. Item #2 of the same list
9. Item #3 of the list — items are numbered sequentially, the number at the beginning of the line does not matter
```

## Headings

Headings are created by placing a pound sign before the heading text. The number of "#" signs corresponds to the heading level. HTML provides 6 levels of headings.

# First level heading
...
### Third level heading
...
###### Sixth level heading

## Quotes

> This text will be enclosed in HTML tags <blockquote></blockquote>

## Links

[Link text](http://example.com/ "Optional link title")



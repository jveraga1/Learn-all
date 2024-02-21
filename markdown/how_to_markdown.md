# `.md` File for learning (and keeping a template for future references) markdown.

This is just a comprehensive list of `markdown` features. There are further tools to use, but this should serve as a starting point for your own personal documentation.

``` 
A note on Flavors: the symbols used below are for Markdown for Github. There are other flavors that would use more simplified notation (instead of HTML) to render effects on .md text. 
```

## 1. Headings

In `markdown` you can have different sizes of heading. The symbol to use is `#` followed by the heading. Depending on the amount of `#` that you use, the size of the heading is going to be changed. Ex. one `#` gives you Heading1, the largest possible heading, two `#` gives you a smaller size or Heading2, and so on and so forth.

`Examples`

1. # Heading1
2. ## Heading2
3. ### Heading3
4. #### Heading4
5. ##### Heading5
6. ###### Heading6

## 2. Bold vs. Italics

\*\* some text \*\* will bold the text. **Ex.** **Hello World**

\* some text \* will italicized the text. **Ex.** *Hello World*

\*** some text \*** will bold and italicized the text. **Ex.** ***Hello World***

A comment for both `Bold` and `Italics`: with the notation above you can even bold (italicized) one letter within a word. **Ex.** H**ell**o W*orl*d

## 3. Strikethrough vs. Highlight

\~~ some text \~~ will strikethrough the text. **Ex.** ~~Hello World~~

\<mark> some text \</mark> will highlight the text. **Ex.** <mark> Hello World </mark>

## 4. Superscript vs. Subscript

\<sup> some text \</sup> will superscript the text. **Ex.** X<sup>2</sup>

\<sub> some text \</sub> will subscript the text. **Ex.** H<sub>2</sub>O

## 5. emojis

:smile: will render into happy face. however, this is not supported by Git. Alternatively, you could simply copy and paste and the emoji and this flavor of markdown will render it.

❌ Element of list 1  
✅ Element of list 1

## 6. Rendering Code

\` some code \` will render the text as code. **Ex.** `def func(arg1, arg2):`

\`\`\` some code \`\`\` renders blocks of code. **Ex.**

```
def func(arg1, arg2):
    var = arg1 + arg2
    return var
```

## 7. Links

[This is a link to address in parenthesis](https://www.google.com)

## 8. Images

**Notation:** \!\[alt text](path to that image)

![Markdown Sheet Cheat](/Users/jeveragar/Documents/Developer/git_repos/Learn-all/markdown/ex_image.png)

## 9. Blockquotes

`\> some text` will create a block wih the text. **Ex.**

> Some Text
>> You can also nest the text
>>> And even triple next the text

## 10. Horizontal Rule

\*** will create a horizontal line to separate text. **Ex.**

Some Text
***
Some Text but Separated

## 11. Lists

Number followed by a period will give you a list. **Ex.**

`Ordered List`
1. Item1
2. Item2
3. Item3

`Unordered List`
* Item1
* Item2
* Item3
    * To nest the list use 4 `spaces` or a `tab`

There are all sorts of combinations you can create for lists.

## 12. Tables

**A few Comments:** for the dashes that separate headers and contents of table, you need to have at least three. To align to the right, put a `:` as shown below. To center, put a `:` around the `-`.

| Column1 | Column2 |
| :-------: | -------: |
| C1Elem1 | C2Elem1 |
| C1Elem2 | C2Elem2 |
| C1Elem3 | C2Elem3 |

## 13. CheckLists or TaskLists

To create check lists, you need square brackets and two spaces in between \[  \] followed by the text.

- [  ] CheckList Element 1  
- [x] CheckList Element 2

# Resources:

1. [Link Crash Course that sources all this information. ](https://www.youtube.com/watch?v=_PPWWRV6gbA)
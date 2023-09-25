# Basic writing and formatting syntax

## Headings
To create a heading, add one to six `#` symbols before your heading text. The number of `#` you use will determine the hierarchy level and typeface size of the heading.
```
# A first-level heading
## A second-level heading
### A third-level heading
```

## Lists
```
- George Washington
* John Adams
+ Thomas Jefferson
```
- George Washington
* John Adams
+ Thomas Jefferson

```
1. James Madison
1. James Monroe
1. John Quincy Adams
```
1. James Madison
2. James Monroe
3. John Quincy Adams
```
1. First list item
   - First nested list item
     - Second nested list item
```
1. First list item
   - First nested list item
     - Second nested list item

## Task lists
```
- [ ] todo
- [x] todo
- [ ] todo
```
- [ ] todo
- [x] todo
- [ ] todo


## Quoting text
```
Text that is not a quote

> Text that is a quote
```
Text that is not a quote

> Text that is a quote


## Supported color models
```The background color is `#ffffff` for light mode and `#000000` for dark mode.```
The background color is `#ffffff` for light mode and `#000000` for dark mode.

Color	| Syntax	      | Example                 | Output                |
--------|-----------------|-------------------------|-----------------------|
HEX     | ``#RRGGBB``     | ``#0969DA``             | #0969DA               |
RGB     | ``rgb(R,G,B)``  | ``rgb(9, 105, 218)``    | rgb(9, 105, 218)      |
HSL     | ``hsl(H,S,L)``  | ``hsl(212, 92%, 45%)``  | hsl(212, 92%, 45%)    |


## Code Blocks
### php
<pre>
<?php
    echo "Hello world!";
?>
</pre>

### html
<html>
    <title>Hello</title>
    <body>
        <p>Hello World</p>
    </body>
</html>


## Using emoji
`@octocat :+1: This PR looks great - it's ready to merge! :shipit:` <br>
@octocat :+1: <br>
@octocat :+2: <br>
@octocat :+3: <br>
@octocat :+4: <br>
@octocat :+5: <br>

## Icons
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40' style='background: red; color:green;'>](https://github.com/suhag10)


## Paragraphs
You can create a new paragraph by leaving a blank line between lines of text.


## Footnotes
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


## Alerts
```
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.
```
> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

## Hiding content with comments
`<!-- This content will not appear in the rendered Markdown -->`

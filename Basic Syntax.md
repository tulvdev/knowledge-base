# Headings
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6


Heading level 1
===============

Heading level 2
---------------
# Paragraphs
I really like using Markdown.

# Bold
I just love **bold text**.

I just love __bold text__.

# Italic
Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.
# Bold
A*cat*meow

# Bold and Italic
This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text

# Blockquotes
> Dorothy followed her through many of the beautiful rooms in her castle.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Nested Blockquotes
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Blockquotes with Other Elements
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# Lists
## Ordered Lists
1. First item
2. Second item
3. Third item
4. Fourth item

1. First item
1. Second item
1. Third item
1. Fourth item

1. First item
8. Second item
3. Third item
5. Fourth item

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered Lists
- First item
- Second item
- Third item
- Fourth item

* First item
* Second item
* Third item
* Fourth item

+ First item
+ Second item
+ Third item
+ Fourth item

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
## Starting Unordered List Items With Numbers
- 1968\. A great year!
- I think 1969 was second best.


* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.


* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.


1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

# Images
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
# Lists

You can nest an unordered list in an ordered list, or vice versa.

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

# Code

At the command prompt, type `nano`.

# Escaping Backticks

``Use `code` in your Markdown file.``

# Code Blocks

    <html>
      <head>
      </head>
    </html>

# Horizontal Rules

***

---

# Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

# Adding Titles

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

# URLs and Email Addresses
<https://www.markdownguide.org>
<fake@example.com>

# Formatting Links
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

# An Example Putting the Parts Together
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

# Images

![alt text](image.png)

# Characters You Can Escape
`
*
_
{ }
[ ]
< >
( )
#
+
-
.
|

# Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Alignment

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

# Fenced Code Blocks

```java
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

# Strikethrough

~~The world is flat.~~ We now know that the world is round.

# Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

# Highlight

I need to highlight these ==very important words==.

I need to highlight these <mark>very important words</mark>.
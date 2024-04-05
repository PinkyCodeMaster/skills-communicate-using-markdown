# Markdown Cheat Sheet

This is a cheat sheet for Markdown syntax to help you quickly find and remember commands for various formatting options.

## Headings

Headings are created by adding one or more `#` symbols before your heading text. The number of `#` you use will determine the size of the heading.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```


## Links

To create a link, wrap the link text in brackets ([]) and then follow it immediately with the URL in parentheses ().

```markdown
[GitHub](http://github.com)
```

## Images

Images are like links, but they include a leading exclamation mark (!), followed by the alt text in brackets, and then the URL of the image in parentheses.

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```markdown
![This is an image](http://url/to/image.png)
```

## Blockquotes

For quoting text, you can use the `>` character before the text.

```markdown
> This is a blockquote.
```

## Code

For inline code, wrap the text with backticks (`). For larger blocks of code, use triple backticks (```) or indent four spaces.

```markdown
`Inline code` with backticks
```

```
# This is a block of code
print('Hello, Markdown!')
```

## Lists

Markdown supports ordered (numbered) and unordered (bulleted) lists.

### Unordered List

```markdown
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```

### Ordered List

```markdown
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

- [x] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

# Markdown Notes
These are notes I took while studying from
* [Scrimba's Learn Markdown Course](https://scrimba.com/learn/markdownblog)
* [MarkdownGuide.org](https://www.markdownguide.org/basic-syntax/)
* [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
* [GitHub Basic Formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Blog post on quality README files](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)



as a part of my effort to improve [my GitHub](https://github.com/JoeDukes/) README.md files.

<!-- # H1 //commented out bc it screws up the file structure for the table of contents that GitHub automagically creates when there are 2 or more headings-->
## Headings (H2)
Headings begin with 1 - 7? octothorpes
### H3 etc

## Horizontal Rule
A horizontal rule is a blank new line and then 3 dashes

---

## Formatting
* Use 1 asterick on each side for *italics*
* Use 2 astericks on each side for **bold**
* Use 3 astericks on each side for ***bold italic***
* Use 2 tildas on each side for ~~strikethrough~~
* Use triple back ticks on each side for ```code```
* Use asterick, dash, or plus at the start of a line followed by a space for unordered lists
    1. Use numbers with a dot at the start of a line and then a space for ordered lists
    1. And indent for indented new list
    1. Like this one here

## Blockquotes
> "Let's add a quote here by using a >"

### blockquotes with paragraphs
> A longer quote
> with multiple lines
> designate a new paragraph by putting an empty line
>
> with the > on the empty line


## Links and Images
[My link text](https://www.mylink.org "My title text.")

<!-- This is the normal way to do images but if the size sucks then just use an image tag with alt and width/height
![Alt text](./images/image-icon.jpg "Title text")
-->

<img src="./images/image-icon.jpg" alt="image icon" width="50">

### An image as a link
Put the entire image tag inside the link text square brackets

[![Alt Text](./images/image-icon-small.jpg "Image title text")](https://www.mylink.org "Link title text")

### Automatic links
Just add your link into the normal text https://LikeHere.org

### README Section/Heading Links
You can hover over a header in a README file to see the link icon and copy the link to that location in the README
[Like this README Section](https://github.com/JoeDukes/markdown-notes/tree/main#readme-sectionheading-links)

## Emails
Emails are just the email inside a tag aka inside <>, so <github@dukesmail.com>

## Emojis
Use colon on each side of the emoji name :grinning:

[Github Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

## Checklists
Use a dash and then square brackets with a space for undone and with an x for checked
- [ ] First item
- [x] Done item
- [ ] Another item

## Tables
* Top row will be your table headers
* Use | to demark your cells and then just add rows with appropriate spacing
* Second row will have dashes for the width of the cell and use the colon on the side you want to align the cell
* Be sure to 

| Left | Center | Right |
| :--- | :----: | ----: |
| 1    | 2      | 3     |

## Alerts
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
```

## Badges
I'm not sure what this is about but looks cool. They can be obtained/built at [shields.io](https://shields.io/)

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

### Icons
SVG Icons for badges or other stuff

[Simple Icons](https://simpleicons.org/)

<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>GitHub</title><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/></svg>

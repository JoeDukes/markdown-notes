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
* Use 1 asterisk on each side for *italics*
* Use 2 asterisks on each side for **bold**
* Use 3 asterisks on each side for ***bold italic***
* Use 2 tildas on each side for ~~strikethrough~~
* Use triple back ticks on each side for ```code```
* You can highlight the syntax in a code block by identifying the language after the first 3 ticks ```` ```csharp... ````
    ```csharp
        public static void main(string[] args){
            Console.Writeline("Hello World!);
        }
    ```
    A list of the [commonly supported languages](https://markdown.land/markdown-code-block)
* Use asterisk, dash, or plus at the start of a line followed by a space for unordered lists
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

## Badges and Icons
### Badges
I'm not sure what this is about but looks cool. They can be obtained/built at [shields.io](https://shields.io/)

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

### Icons
SVG Icons for badges or other stuff

[Simple Icons](https://simpleicons.org/)

* Download the SVG file and save in your images folder
* Open the file in an editor, like VSCode, and add ```fill="#FFFFFF"``` or whatever color you want the icon to be inside the svg tag
* Add the icon using the img tag, not the markdown, and include a width in the img tag ```<img src="./images/github.svg" alt="GitHub Icon" width="50">```

<img src="./images/github.svg" alt="GitHub Icon" width="50">

## Collapsed Sections
* Use the ```<details>``` tag followed by a ```<summary``` tag to include a collapsed section
* Put a blank line between details, summary, and your text
* Use ```<details open>``` to have it expanded by default

<details>

<summary>Collapsed Section</summary>

#### Heading
With some text and stuff

</details>

### You can nest collapsed sections within collapsed sections
```
<details>
<summary>Section A</summary>
<details>
<summary>Section A.B</summary>
<details>
<summary>Section A.B.C</summary>
<details>
<summary>Section A.B.C.D</summary>
  Done!
</details>
</details>
</details>
</details>
```
<details>
<summary>Section A</summary>
<details>
<summary>Section A.B</summary>
<details>
<summary>Section A.B.C</summary>
<details>
<summary>Section A.B.C.D</summary>
  Done!
</details>
</details>
</details>
</details>

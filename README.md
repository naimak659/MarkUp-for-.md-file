<h1 align="center">Markdown: A Beginner's Guide to<br> Writing README.md Files</h1>

Markdown is a lightweight markup language used for formatting text in a simple and intuitive way. README.md files play a crucial role in software development projects, serving as a hub for project documentation, instructions, and information. This guide equips beginners with the knowledge and skills to effectively utilize Markdown syntax to create clear, concise, and visually appealing README.md files.

## use of Markdown
1. Documentation (GitHub, GitLab, and Bitbucket)
2. Blogging (Medium and Ghost)
3. Note-taking (Notion, Evernote, Obsidian and Bear)
4. Messaging and Chat (Slack and Discord)
5. Writing Books and E-books (Leanpub and GitBook)

> KeyBoard Shortcuts written like this: ks( mac: ... , win/lin: ... )

# Let's Start

## content
1. [Headings](#headings)
2. [Text Styling](#text-styling)
3. [Quote](#quote)
4. [Quoting code](#quoting-code)
5. [Links](#links)

## Headings

To create a heading in Markdown, you can use one to six # symbols before your heading text. The number of # symbols you use will determine the hierarchy level and typeface size of the heading. 

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

#### output of heading:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Text Styling

```
**Bold text**  OR  __Bold text__  
*Italic text*  OR _Italic text_
~~Strikethrough~~
**Bold and nested _italic_**
***bold and italic***
```
#### output of text styling:

**Bold text**  OR  __Bold text__  `ks( mac: Command + B , win/lin: Ctrl + B )` <br>
*Italic text*  OR _Italic text_ `ks( mac: Command + I , win/lin: Ctrl + I )`<br>
~~Strikethrough~~ <br>
**Bold and nested _italic_** <br>
***bold and italic***

## Quote

You can write quote by using >

```
> Text that is a quote
```
#### output of quote: 

> Text that is a quote


## Quoting code

 Use single backticks (`) to highlight code or commands within a sentence in Markdown. The text within the backticks won't be formatted. 
```
Use single backticks (`) to `highlight code or commands` within a sentence in Markdown. The text within the backticks won't be formatted.
```

#### output of Quoting code:
Use single backticks ( \` ) to `highlight code or commands` within a sentence in Markdown. The text within the backticks won't be formatted.

To format code or text into its own distinct block, use triple backticks:
(as example i'm writing a css file)
``` 
```css

.element{
  color: #fff;
}
.```
```
#### output of Quoting code 2:
```css

.element{
  color: #fff;
}
```

(You can specify the programming language for syntax highlighting after the triple backticks. For example, to specify CSS formatting, you would write ` ```css ` followed by the code block.)

## Links

To create an inline link, enclose the link text in square brackets [ ], followed by the URL in parentheses ( ). Alternatively, use the Command+K keyboard shortcut. You can also paste a URL from your clipboard over selected text to instantly create a link.

```
This is my github account [naimak659](https://github.com/naimak659)
```
#### output of Link:
This is my github account [naimak659](https://github.com/naimak659) `ks( mac: Command + K , win/lin: Ctrl + K )`

## Relative links

You can simplify navigation within your repository by defining relative links and image paths in your rendered files. A relative link is defined relative to the current file's location. For instance, if your repository's root contains a README file and a docs/CONTRIBUTING.md file, the relative link from README to CONTRIBUTING.md might appear like this:
```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```
GitHub dynamically adjusts relative links and image paths based on the current branch, ensuring they always point to the correct location. The link or path is relative to the current file's location. Links starting with / are relative to the repository root. You can utilize various relative link operands, including ./ and ../, for precise navigation.

## Images

To display an image, use an exclamation mark (!), followed by square brackets ([ ]) containing the alt text (a brief description of the image), and then wrap the image link in parentheses (). Here's the format:
```
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
```
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## List

To create an unordered list in Markdown, you can start each item with either a hyphen (-), an asterisk (*), or a plus sign (+). Here's how you can do it:

```
- Item 1
* Item 2
+ Item 3
```
#### output of unordered list:
- Item 1
* Item 2
+ Item 3


To create an ordered (numbered) list in Markdown, you can precede each line with a number followed by a period (.). Here's how you can do it:
```
1. Item 1
2. Item 2
3. Item 3
```
#### output of unordered list:
1. Item 1
2. Item 2
3. Item 3

Markdown will automatically number the items sequentially based on the order in which you list them.

## Task lists

To create a task list in Markdown, you can use a hyphen and space followed by square brackets ([ ]) for incomplete tasks. To mark a task as complete, replace the empty square brackets with [x]. Here's how you can do it:

```
- [x] Task List
- [ ] Using Emojis
- [ ] Nested List
```
#### output of Task list:
- [x] Task List
- [ ] Using Emojis
- [ ] Nested List

## Emojis
You can add emojis to your writing in Markdown by typing :EMOJICODE:, where "EMOJICODE" represents the name of the emoji you want to use, enclosed in colons. This allows you to easily incorporate emojis into your text to add emphasis or convey emotions.

```
:wave: Welcome to ***My Awesome Project!*** :rocket:
```
#### output of Emojis:
:wave: Welcome to ***My Awesome Project!*** :rocket:


# Writing On GitHub - Practice

This is a demo project for me to practice the ["Writing on GitHub" instructions](https://docs.github.com/en/get-started/writing-on-github).

<!-- This is a comment. It is not visible on the published page. -->

# Headings

Use the pound sign to add heading formating. One pound sign for a Level 1 heading, all the way up to six pound signs for a Level 6 heading.

This is what the headings look like:

<img width="484" height="308" alt="image" src="https://github.com/user-attachments/assets/6067fa5f-e2af-4d60-9ca9-a04f9a899b4b" />

When headings are present, GitHub automatically generates a TOC which is accessible form the file header.

# Text styling

| Style | Code | Example Code | Output | 
|---|---|---|---|
| Bold | Surround text with ** or __ | `**Bold text**` | **Bold text** |
| Italic | Surround text with * or _ | `*Italic text*` | *Italic text* |
| Strikethrough | Surround text with ~ or ~~ | `~~Strikethrough text~~` | ~~Strikethrough text~~ |
| Bold and italic | Surround text with *** | `***Bold and italic text***` | ***Bold and italic text*** |
| Bold and nested italic | Surround text with ** and nested with _ | `**Bold _and italic text_**` | **Bold _and italic text_** |
| Subscript | Surround text with `<sub> </sub>` | `<sub>Subscript text</sub>` | <sub>Subscript text</sub> |
| Superscript | Surround text with `<sup> </sup>` | `<sup>Superscript text</sup>` | <sup>Superscript text</sup> |
| Underline | Surround text with `<ins> </ins>` | `<ins>Underlined text</ins>` | <ins>Underlined text</ins> |


# Tables

## Creating tables

Use pipes `|` and hyphens `-` to create tables in Markdown.

```
| Header one | Header two | Header three |
|---|---|---|
| Content | Content | Content |
| Content | Content | Content |
| Content | Content | Content |
| Content | Content | Content |
```

| Header one | Header two | Header three |
|---|---|---|
| Content | Content | Content |
| Content | Content | Content |
| Content | Content | Content |
| Content | Content | Content |

- You must include a blank line before the table.
- Pipes separate each column.
- The first row is the header row. The header text is bold and center aligned.
- Hyphens on the second row create the break between the header row and the content rows.
- There must be at least three hyphens in each column below the header row.
- You must have equal columns for each row in order for the table to corre
- The cells can vary in width and not not need to be perfectly alighned within the columns.
- You can use code blocks and text styling within tables.
- To include a pipe as content within your table, use a backslash before the pipe.

## Formatting tables

You can format the content in the table to be left, center, or right aligned by adding colons to the hyphens in the header row. See the following table for details.

```
| Default aligned | Left aligned | Center aligned | Right aligned | 
|---|:---|:---:|---:|
| Header row is `---` | Header row is `:---` | Header row is `:---:` | Header row is `---:` | 
| Default text, default aligned | Default text, left aligned | Default text, center aligned | Default text, right aligned |
| `Code text, default aligned` | `Code text, left aligned` | `Code text, center aligned` | `Code text, right aligned` |
| **Bold** text, default aligned | **Bold** text, left aligned | **Bold** text, center aligned | **Bold** text, right aligned | 
| _Italic_ text, default aligned | _Italic_ text, left aligned | _Italic_ text, center aligned | _Italic_ text, right aligned |
```

| Default aligned | Left aligned | Center aligned | Right aligned | 
|---|:---|:---:|---:|
| Header row is `---` | Header row is `:---` | Header row is `:---:` | Header row is `---:` | 
| Default text, default aligned | Default text, left aligned | Default text, center aligned | Default text, right aligned |
| `Code text, default aligned` | `Code text, left aligned` | `Code text, center aligned` | `Code text, right aligned` |
| **Bold** text, default aligned | **Bold** text, left aligned | **Bold** text, center aligned | **Bold** text, right aligned | 
| _Italic_ text, default aligned | _Italic_ text, left aligned | _Italic_ text, center aligned | _Italic_ text, right aligned |


# Lists

Various forms of lists can be used in GitHub.
- [Unordered lists](#unordered-lists)
- [Ordered lists](#ordered-lists)
- [Nested lists](#nested-lists)
- [Task lists](#task-lists)

When you start a list, GitHub automatically continues the list formatting for you when you press **Enter**. To remove the formatting and return to regular paragraph text, press **Delete**.

## Unordered lists

Use a dash, asterisk, or plus sign to format an unordered list.


```
- List item one uses a hyphen
- List item two uses a hyphen
* List item three uses a asterisk
* List item four uses a asterisk
+ List item five uses a plus sign
+ List item six uses a plus sign
```

- List item one uses a hyphen
- List item two uses a hyphen
* List item three uses a asterisk
* List item four uses a asterisk
+ List item five uses a plus sign
+ List item six uses a plus sign

## Ordered lists

To order a list, precede each line with a number instead of a hyphen, asterisk, or plus sign. 
 
```
1. List item number one.
2. List item number two.
3. List item number three.
```

1. List item number one.
2. List item number two.
3. List item number three.

## Nested lists

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Visual Studio Code, you can align your list visually. Type space characters in front of your nested list item until the list marker character (- or *) lies directly below the first character of the text in the item above it. For example: 

1. Funny Story
   - The best EmHen book.
     - I love this book so much.
     - I've read it four times.
3. Beach Read
4. People We Meet on Vacation
5. Book Lovers
6. Great Big Beautiful Life
7. Happy Place

Or you can count the number of spaces prior to the list item (the bullet point and space prior to the list item equal two spaces) and add that number of spaces prior to the bullet point of the list item you want indented. You can continue this method for as many indents as are needed, as long as all spaces and characters are accounted for. For example:

- This line has two spaces before the text begins.
  - This line has four spaces before the text begins.
    - This line has six spaces before the text begins.
  - This line has four spaces before the text begins.

**Note:** On the web editor, you can indent or dedent multiple lines of a list at the same time by selecting the text and then using `Tab` to indent or `Shift`+`Tab` to dedent.

## Task lists

To add a task tracker to your lists, preface list items with a hyphen and space, followed by brackets with a space between them. To mark the task as complete, replace the space between the brackets with an x.

```
- [ ] Task item 1.
- [ ] Task item 2.
- [x] Task item 2.
```

- [ ] Task item 1.
- [ ] Task item 2.
- [x] Task item 2.

If a task item description begins with a parenthesis, add a backslash prior to the parenthesis.

`- [ ] \(Optional) Task item.`

- [ ] \(Optional) Task item.

**Note:** I do not know why the backslash is required. When I tested this without the backslash, it appeared correct.

```
- [ ] (Optional) Task item.
- [x] (Optional) Task item.
```

- [ ] (Optional) Task item.
- [x] (Optional) Task item.




# Collapsed sections

Use the "details" tag to collapse sections.

You can use the default, where the section is collapsed ("details" tag).

<details>
<summary>EmHen Books ranked</summary>

| Rank | Title | 
|--|--|
| 1 | Funny Story | 
| 2 | Beach Read | 
| 3 | People We Meet on Vacation | 
| 4 | Book Lovers | 
| 5 | Great Big Beautiful Life | 
| 6 | Any future books | 
| 7 | Happy Place | 

</details>

Or you can make it so that the section defaults as visible, but can be collapsed ("details open" tag).

<details open>
<summary>EmHen Books ranked</summary>

| Rank | Title | 
|--|--|
| 1 | Funny Story | 
| 2 | Beach Read | 
| 3 | People We Meet on Vacation | 
| 4 | Book Lovers | 
| 5 | Great Big Beautiful Life | 
| 6 | Any future books | 
| 7 | Happy Place | 

</details>

# Quotes

Here is a quote from a book that I love:

---
> It begins with absence and desire. It begins with blood and fear. It begins with a discovery of witches.

&mdash; Deborah Harkness, _A Discovery of Witches_

## Adding a comment

Comments are hidden. You have to view the code to see the comment. Use comment tag:

`<!-- COMMENT -->`


# Code Text

To display code text without code output, surround code text with a backtick ( ` ). 

Example for a single line or word of code:

<img width="221" height="40" alt="image" src="https://github.com/user-attachments/assets/6138333b-2b6b-48d9-910b-6eea6a303a36" />

`Surround code text with marks`

Example for a long string of code:

<img width="289" height="137" alt="image" src="https://github.com/user-attachments/assets/bde81865-5239-4186-ae52-8b2079746896" />

```
To display multiple lines of code text:
Enter three marks and a hard return.
Enter the code.
Enter three closing marks.
```

# Color

In issues, pull requests, and discussions, call out colors by using backticks. A supported color model within backticks will display a visualization of the color.

| Color | Syntax | Example | 
|---|---|---|
| HEX | `#RRGGBB` | `#0969DA` |
| RGB | `rgb(R,G,B)` | `rgb(9,105,218)` |
| HSL | `hsl(H,S,L)` | `hsl(212,92%,45%)` |

The HEX background colors are `#ffffff` for light mode and `#000000` for dark mode.

# Links

Wrap the text in brackets `[ ]` and the URL in parenthesis `( )`.

Keyboard shortcut is `command`+`K`.

## External links

To create a markdown hyperlink, highlight the text and use the keyboard shortcut `command`+`v`. To replace the text with the link, use the shortcut `command`+`shift`+`V`.

## Section links

Add the brackets and parenthesis, then copy the section link and paste it into the parenthesis.

Notes for section links:
- Letters are lowercase.
- Replace spaces with hyphens.
- Remove any markdown code, leaving only the contents.

## Relative links

A relative link is a link that is relative to the current file. They help readers navigate to other files in your repository and are easier for users who clone your repository.

For example, a README file in root contains a link to the CONTRIBUTING.md file, also in root. In this case, the link is `[visible text](docs/CONTRIBUTING.md)`.

## Anchors

An anchor can be a heading or one that is manually created. To manually add an anchor, enter an HTML link `<a name="my-custom-anchor-point"></a>` at the point you want to return to, and then add a markdown link (`[Link to anchor](#mycustom-anchor-point)`) in the text.

# Paragraph breaks

To create a new paragraph, leave a blank line between lines of text.

```
This is one paragraph.

This is a new paragraph.
```

This is one paragraph.

This is a new paragraph. 



# Line breaks

As noted in the [Paragraph section](#paragraph-breaks), a blank line in the code displays a blank line in the output. But sometimes you may want a break in a line of text without creating a new paragraph. And just adding a hard return does not result in a line break. For example:

<ul>
 

```
You cannot add a line break
with a hard return
```

You cannot add a line break
with a hard return

</ul>

This is when you need to use a line break. There are a few ways to manually add a line break.
- [Two spaces](#line-break-two-spaces).
- [Backslash](#line-break-backslash).
- [Line break tag](#line-break-html-break-tag).

<a name="line-break-two-spaces"></a>Include two spaces at the end of the first line:

<ul>
 
```
Add a line break  
with two spaces
```

Add a line break  
with two spaces

</ul>

<a name="line-break-backslash"></a>Add a backslash at the end of the first line:

<ul>
 
```
Add a line break\
with a backslash
```

Add a line break\
with a backslash

</ul>

<a name="line-break-html-break-tag"></a>Use an HTML break tag:

<ul>
 
```
Add a line break<br>
with a break tag
```

Add a line break<br>
with a break tag

</ul>

# Images

Display an image by adding an exclamation point and then wrapping the alt text in brackets and the image link in parentheses.

`![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

To add an image from your repository, use relative links.

| Context | Relative Link |
|---|---|
| In a .md file on the same branch | `/file/image file/image.png` |
| In a .md file on another branch | `/../main/file/image file/image.png` |
| In issues, pull requests, and comments of the repository | `../blob/main/assets/images/image.png?raw=true` |
| In a .md file in another repository | `/../../../../github/docs/blob/main/assets/images/image.png` |
| In issues, pull requests, and comments of another repository | `../../../github/docs/blob/main/assets/images/image.png?raw=true` |

The `<picture>` element is also supported in GitHub.

<picture>
 <img alt="IMAGE OF OPEN BOOKS" src="https://github.com/efretwell/images/blob/main/open-books-background-reading-concept-bookstore-library-education-information-hardcover.jpg" width="50%">
</picture>

This one is from an image added to my image repo. The repo needs to be public in order for others to see the image. 

# Emojis

To manually add an emoji, type a colon, the emoji code, and a colon: `:EMOJICODE:` 

`This looks great! :+1:`

This looks great! :+1:

Typing a colon brings up a list of suggested emojis. The list filters as you type, so once you find the emoji you want to use, press `Tab` or `Enter` to add the highlighted emoji.

You can also access the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/github-actions-auto-update/README.md) and copy+paste the emoji directly into your text.

# Mention people and teams

When you use the mention feature, GitHub triggers a notification and brings the attention of the persons mentioned to the conversation.

To mention a person or team on GitHub, type `@` plus the user or team name. When you type the `@` symbol, a list appears that filters as you type. The list of options is restricted to repository collaborators and any other participants on the thread.

**Note:** The person or team will only be notified if they have read access to the repository and, if owned by an organization, the person is a member of the organization.

# Reference issues and pull requests

To bring up a list of suggested issues and pull requests within the repository, typ the `#` symbol and then the issue or pull request number or title to filter the list. Press tab or enter to select the highlighted result to display in the text.

# Reference external resources

If custom autolink references are configured for a repository, then references to external resources, like a JIRA issue or Zendesk ticket, convert into shortened links. To know which autolinks are available in your repository, contact someone with admin permissions to the repository. For more information, see [Configuring autolinks to reference external resources](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources).

# Upload assets

To add assets, such as images, drag and drop, select from the file browser, or paste the item.

# Footnotes

Add footnotes to your content by using the following syntax:

```
Here is a simple footnote[^1].

Here is a footnote that has multiple lines[^2].

[^1]: Reference.
[^2]: Reference. Add two spaces to add a second line. There are two spaces here.
This is the second line.
```

Here is a simple footnote[^1].

Here is a footnote that has multiple lines[^2].

[^1]: Reference.
[^2]: Reference. Add two spaces to add a second line. There are two spaces here.  
This is the second line.

**Notes:** 
- The footnotes always render at the bottom of the markdown.
- Footnotes are not supported in wikis.

# Alerts

Alerts, callouts, or admonitions, are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub they display with distinctive colors and icons to indicate the significance of the content. 

Things to note:
- Only use alerts when they are crucial for user success.
- Limit alerts to one or two per article to prevent overload.
- Avoid placing alerts consecutively.
- Alerts cannot be nested within other elements.

```
> [!NOTE]
> Note alert. Useful information that users should know, even when skimming content.

> [!TIP]
> Tip alert. Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Important alert. Key information users need to know to achieve their goal.

> [!WARNING]
> Warning alert. Urgent information that needs immediate user attention to avoid problems.

> [!CAUTION]
> Caution alert. Advises about risks or negative outcomes of certain actions.
```

> [!NOTE]
> Note alert. Useful information that users should know, even when skimming content.

> [!TIP]
> Tip alert. Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Important alert. Key information users need to know to achieve their goal.

> [!WARNING]
> Warning alert. Urgent information that needs immediate user attention to avoid problems.

> [!CAUTION]
> Caution alert. Advises about risks or negative outcomes of certain actions.

# Ignore Markdown formatting

You can tell GitHub to ignore Markdown formatting by using a backslash before the Markdown character.

`When you \*want\* to show the asterisks.`

When you \*want\* to show the asterisks.

# Disable Markdown rendering

Disabling Markdown rendering enables you to use source view features, such as line linking, which is not possible when viewing rendered Markdown files.

When viewing a Markdown file, select Code, located at the top of the file, to disable Markdown rendering and instead view the file's source material.



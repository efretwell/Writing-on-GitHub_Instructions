# Writing On GitHub - Practice

This is a demo project for me to practice the "Writing on GitHub" instructions (https://docs.github.com/en/get-started/writing-on-github).

<!-- This is a comment. It is not visible on the published page. -->

## Adding an image

<picture>
 <img alt="IMAGE OF OPEN BOOKS" src="https://github.com/efretwell/images/blob/main/open-books-background-reading-concept-bookstore-library-education-information-hardcover.jpg" width="50%">
</picture>

This one is from an image added to my image repo. The repo needs to be public in order for others to see the image. 

## Adding a table

Ranking Emily Henry books and showing table formatting. 

| Rank | default -- | L aligned :-- | R aligned --: | Center aligned :--: |
|:--:|--|:--|--:|:--:|
| 1 | Funny Story | Funny Story | Funny Story | Funny Story |
| 2 | Beach Read | Beach Read | Beach Read | Beach Read |
| 3 | People We Meet on Vacation | People We Meet on Vacation | People We Meet on Vacation | People We Meet on Vacation |
| 4 | Book Lovers | Book Lovers | Book Lovers | Book Lovers |
| 5 | Great Big Beautiful Life | Great Big Beautiful Life | Great Big Beautiful Life | Great Big Beautiful Life |
| 6 | Any future books | Any future books | Any future books | Any future books |
| 7 | Happy Place | Happy Place | Happy Place | Happy Place |

See how -- (the default) makes the cells left aligned, --: makes the cells right aligned, :-- makes the cells left aligned, and :--: makes the cell center aligned

## Adding a collapsed section

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

## Adding a quote

Here is a quote from a book that I love:

---
> It begins with absence and desire. It begins with blood and fear. It begins with a discovery of witches.

&mdash; Deborah Harkness, _A Discovery of Witches_

## Adding a comment

Comments are hidden. You have to view the code to see the comment. Use comment tag:

`<!-- COMMENT -->`

# Headings

This is what the headings look like:

# Level 1
## Level 2
### Level 3
#### Level 4
##### Level 5
###### Level 6

# Text styling

| Style | Code | Example Code | Output | 
|---|---|---|---|
| Bold | Surround text with ** or __ | `**Bold text**` | **Bold text** |
| Italic | Surround text with * or _ | `*Italic text*` | *Italic text* |
| Strikethrough | Surround text with ~ or ~~ | `~Strikethrough text~` | ~Strikethrough text~ |
| Bold and italic | Surround text with *** | `***Bold and italic text***` | ***Bold and italic text*** |
| Bold and nested italic | Surround text with ** and nested with _ | `**Bold _and italic text_**` | **Bold _and italic text_** |
| Subscript | Surround text with `<sub> </sub>` | `<sub>Subscript text</sub>` | <sub>Subscript text</sub> |
| Superscript | Surround text with `<sup> </sup>` | `<sup>Superscript text</sup>` | <sup>Superscript text</sup> |
| Underline | Surround text with `<ins> </ins>` | `<ins>Underlined text</ins>` | <ins>Underlined text</ins> |

## Code Text

To display code text without code output, surround code text with ` 

Example for a single line or word of code:

<img width="221" height="40" alt="image" src="https://github.com/user-attachments/assets/6138333b-2b6b-48d9-910b-6eea6a303a36" />

Output:

`Surround code text with marks`

Example for a long string of code:

<img width="289" height="137" alt="image" src="https://github.com/user-attachments/assets/bde81865-5239-4186-ae52-8b2079746896" />

Output: 

```
To display multiple lines of code text:
Enter three marks and a hard return.
Enter the code.
Enter three closing marks.
```



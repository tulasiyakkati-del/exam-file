# Markdown Quick Start Guide <!-- omit from toc -->

**Tech Writer's Tribe**
**Version:** 1.0



## Table of Contents <!-- omit from toc -->

1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [Concept: Markdown](#concept-markdown)
   1. [Key Features](#key-features)
   2. [Access Options](#access-options)
   3. [Applications](#applications)
   4. [Benefits](#benefits)
   5. [High-Level Architecture](#high-level-architecture)
4. [Using Markdown Styles](#using-markdown-styles)
   1. [Format Headings](#format-headings)
   2. [Format Text](#format-text)
   3. [Create Lists](#create-lists)
   4. [Add Links](#add-links)
   5. [Add Images](#add-images)
   6. [Create Tables](#create-tables)
   7. [Insert Code Blocks](#insert-code-blocks)
5. [Reference](#reference)
   1. [Text Formatting](#text-formatting)
   2. [Lists](#lists)
   3. [Links and Media](#links-and-media)
   4. [Tables and Code](#tables-and-code)
   5. [Notes](#notes)
   6. [Additional References](#additional-references)
6. [Frequently Asked Questions](#frequently-asked-questions)
7. [Troubleshooting](#troubleshooting)
8. [Best Practices](#best-practices)


## Overview

This quick start guide describes how to use Markdown to format text, create lists, add links and images, create tables, and insert code blocks.

This QSG helps you perform the following:

1. Understand what Markdown is and how it works.
2. Format text using headings, bold, and italics.
3. Create bullet and numbered lists.
4. Add links, images, and tables to your document.
5. Insert code blocks.

## Prerequisites

- Visual Studio Code is installed on your computer.
- A GitHub account is available, if you plan to publish your files.

## Concept: Markdown

Markdown is a lightweight markup language that lets you format plain text using simple, keyboard-based symbols instead of HTML tags or a mouse-driven interface. Markdown files use the `.md` extension and are stored as plain text, which keeps them easy to create, edit, and maintain across any text editor.

### Key Features

Markdown provides the following features:

- Simple, readable syntax
- Plain-text file format
- Headings
- Bold and italic text
- Ordered and unordered lists
- Links and images
- Tables
- Code blocks
- Cross-platform compatibility

### Access Options

You can write and view Markdown through the following options:

- **Editor:** Visual Studio Code
- **Version control platform:** GitHub
- **Note-taking apps:** Notion, Obsidian
- Static site generators and documentation tools

### Applications

Markdown is commonly used to create:

- README files
- User guides and Quick Start Guides
- Technical documentation
- Release notes
- Knowledge base articles
- Static websites

### Benefits

Markdown offers the following benefits:

- Remains readable even in its raw, unformatted form
- Works in any plain text editor, without requiring specific software
- Is the standard format for GitHub, technical documentation, and note-taking tools
- Separates content from formatting, making files lightweight and portable
- Supports version control, since files are stored as plain text
- Can be converted into HTML for publishing

### High-Level Architecture

```
Markdown File (.md)
    ↓
Markdown Processor
    ↓
Formatted Output
(VS Code Preview or GitHub)
```

A Markdown file is written once, then rendered by different tools — such as a VS Code preview pane, GitHub's file viewer, or a static site generator — to produce formatted output.

## Using Markdown Styles

The following tasks describe how to use common Markdown styles.

### Format Headings

Headings organize content into logical sections and improve document readability.

To create headings:

1. Open a `.md` file in VS Code.
2. Place the cursor where you want the heading.
3. Type one or more hash (`#`) symbols followed by a space.
4. Enter the heading text.

**Example:**

```
# Heading 1
## Heading 2
### Heading 3
```
The headings are created successfully.

### Format Text

Markdown supports bold, italic, bold italic, and strikethrough text.

To format text:

1. Open a `.md` file in VS Code.
2. Place the cursor where you want to format text.
3. Apply the appropriate syntax.

| Style | Syntax |
|---|---|
| Bold | `**text**` |
| Italic | `*text*` |
| Bold Italic | `***text***` |
| Strikethrough | `~~text~~` |

The text is formatted successfully.

### Create Lists

Lists organize related information and improve readability.

To create a list:

1. Open a `.md` file in VS Code.
2. Type a hyphen (`-`) followed by a space to create a bullet list item.
3. Type a number followed by a period (`.`) to create a numbered list item.
4. Repeat for each additional item.

**Example:**

```
- Apple
- Orange

1. Install Visual Studio Code.
2. Create a Markdown file.
```
The list is created successfully.

### Add Links

Links let readers navigate to webpages, documents, or other resources.

To add a link:

1. Open a `.md` file in VS Code.
2. Type the link text inside square brackets.
3. Type the URL inside parentheses immediately after.

**Example:**

```
[GitHub](https://github.com)
```
The link is added successfully.

### Add Images

Images help illustrate concepts and improve document readability.

To add an image:

1. Open a `.md` file in VS Code.
2. Type an exclamation mark, then alt text in square brackets.
3. Type the image path or URL in parentheses immediately after.

**Example:**

```
![Markdown Logo](images/markdown-logo.png)
```
The images are added successfully.

### Create Tables

Tables organize information into rows and columns.

To create a table:

1. Open a `.md` file in VS Code.
2. Enter the header row.
3. Add a separator row using hyphens.
4. Enter the table data.

**Example:**

```
| Feature | Description |
|---------|-------------|
| Heading | Creates document headings |
| Lists   | Organizes information |
```
The table is created successfully.


### Insert Code Blocks

Code blocks display commands or source code while preserving formatting.

To insert a code block:

1. Open a `.md` file in VS Code.
2. Type three backticks.
3. Optionally, specify the programming language.
4. Type the code, then close with three backticks on a new line.

**Example:**

````
```bash
git init
git add .
git commit -m "Initial commit"
```
````
The code blocks are added successfully.


## Reference

Markdown uses specific symbols to format text, lists, links, tables, and code. This reference lists the syntax for each element covered in this guide.

### Text Formatting

| Element | Syntax |
|---|---|
| Heading 1–6 | `#` to `######` |
| Bold | `**text**` |
| Italic | `*text*` |
| Bold Italic | `***text***` |
| Strikethrough | `~~text~~` |

### Lists

| Element | Syntax |
|---|---|
| Bullet list | `- item` |
| Numbered list | `1. item` |

### Links and Media

| Element | Syntax |
|---|---|
| Link | `[text](url)` |
| Image | `![alt](url)` |

### Tables and Code

| Element | Syntax |
|---|---|
| Table | Header row + `---` separator row |
| Inline code | `` `code` `` |
| Code block | Three backticks |
| Blockquote | `> text` |
| Horizontal rule | `---` |

### Notes

- Markdown syntax is case-sensitive and must be typed exactly as shown.
- A space is required after `#` for headings to render correctly.
- Symbols display as plain text if the file does not have a `.md` extension.

### Additional References

- GitHub Docs – Basic Writing and Formatting Syntax.
- Markdown Guide.
- CommonMark Specification.

## Frequently Asked Questions

**Can I use Markdown in any text editor?**
Yes. Since Markdown files are plain text, they can be opened and edited in any text editor. However, only editors or platforms with Markdown support, such as VS Code or GitHub, will render the formatting visually.

**Do I need an internet connection to write Markdown?**
No. Markdown files can be created and edited offline. An internet connection is only required to push files to GitHub or view them online.

**Can I convert a Markdown file to another format?**
Yes. Markdown files can be converted to formats such as HTML or PDF using tools like Pandoc or extensions available in VS Code.

## Troubleshooting

**Scenario:** Formatting does not render correctly.
**Solution:** Confirm the file has a `.md` extension and the syntax is correctly formatted before saving.

**Scenario:** Preview does not open in VS Code.
**Solution:** Install the "Markdown All in One" extension from the Extensions panel, then reopen the file.

**Scenario:** A table does not display in a table format.
**Solution:** Confirm each row has the same number of `|` symbols as the header row, and that the separator row uses at least three hyphens per column, such as `|---|---|`.

**Scenario:** An image does not display.
**Solution:** Verify that the image path or URL and file name are correct.

**Scenario:** A link does not open.
**Solution:** Verify that the URL is correct and begins with `https://`.

## Best Practices

- Use clear, meaningful headings to organize content.
- Use one blank line between a heading and the paragraph that follows it, to ensure correct rendering.
- Use consistent heading levels (`#`, `##`, `###`) to maintain a clear document hierarchy.
- Use descriptive link text instead of generic text such as "click here."
- Provide alternative text for images.
- Use relative paths for links and images within the same project, to keep them working if the folder is moved.
- Preview the file before publishing, to confirm that headings, lists, and tables render as expected.

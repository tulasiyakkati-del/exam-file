# Markdown Quick Start Guide
Quick Start Guide

Tech Writer's Tribe
Version: 1.0

---

## Contents

| Section | Page |
|---|---|
| Overview | 2 |
| Prerequisites | 2 |
| Concept: Markdown | 2 |
| Using Markdown | 3 |
| I. Formatting Text | 3 |
| II. Formatting Lists | 3 |
| III. Adding Links and Media | 4 |
| Reference: Markdown Syntax | 4 |
| Frequently Asked Questions | 5 |
| Troubleshooting | 5 |
| Best Practices | 5 |

---

## Overview

This quick start guide describes how to use Markdown to format text, create lists, and add links and images.

This QSG helps you perform the following:
1. Understand what Markdown is and how it works.
2. Format text using headings, bold, and italics.
3. Create bullet and numbered lists.
4. Add links and images to your document.

---

## Prerequisites

- Visual Studio Code is installed on your computer.
- A GitHub account is available, if you plan to publish your files.

---

## Concept: Markdown

### Introduction to Markdown

Markdown is a lightweight markup language that lets you format plain text using simple, keyboard-based symbols instead of HTML tags or a mouse-driven interface. It converts characters such as `#`, `*`, and `-` into formatted elements like headings, bold text, and lists when a file is rendered by an editor or platform that supports Markdown.

### Key Features

Markdown provides the following features:
- Headings
- Bold and italic text
- Bullet and numbered lists
- Links and images
- Inline code and code blocks
- Blockquotes
- Tables
- Horizontal rules

### Access Options

You can write and view Markdown through the following options:
- Editor: Visual Studio Code
- Version control platform: GitHub
- Note-taking apps: Notion, Obsidian
- Static site generators and documentation tools

### Benefits

Markdown offers the following benefits:
- Remains readable even in its raw, unformatted form.
- Works in any plain text editor, without requiring specific software.
- Is the standard format for GitHub, technical documentation, and note-taking tools.
- Separates content from formatting, making files lightweight and portable.
- Supports version control, since files are stored as plain text.


---

## Using Markdown

Markdown formatting is applied directly in your `.md` file using specific symbols. The following sections describe how to format text, create lists, and add links.

### I. Formatting Text

You can format text as headings, bold, or italic to emphasize content and structure your document.

To format text:
1. Open a `.md` file in VS Code.
2. Type `#` followed by a space, then your heading text, to create a Heading 1.
3. Type `##` followed by a space, then your heading text, to create a Heading 2.
4. Wrap text with `**` on both sides to make it bold.
5. Wrap text with `*` on both sides to make it italic.
6. Save the file.

The text is now formatted and displays correctly when previewed or rendered on GitHub.

### II. Formatting Lists

You can create bullet lists or numbered lists to organize information.

To format a list:
1. Open a `.md` file in VS Code.
2. Start a line with a hyphen and a space to create a bullet list item.
3. Start a line with a number, a period, and a space to create a numbered list item.
4. Repeat step 2 or step 3 for each additional list item.
5. Save the file.

The list is now created and displays as bullets or numbers when rendered.

### III. Adding Links and Media

You can add links and images to reference external resources or embed visuals.

To add a link or image:
1. Open a `.md` file in VS Code.
2. Type your link text in square brackets, followed immediately by the URL in parentheses, to create a link.
3. Type an exclamation mark, then alt text in square brackets, followed immediately by the image URL in parentheses, to embed an image.
4. Save the file.

The link or image is now added and renders as clickable text or a visible image.

---

## Reference: Markdown Syntax

Markdown uses specific symbols to format text, lists, and links. This reference lists the syntax for each element covered in this guide.

### Text Formatting

| Element | Syntax |
|---|---|
| Heading 1–6 | `#` to `######` |
| Bold | `**text**` |
| Italic | `*text*` |

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

### Notes

- Markdown syntax is case-sensitive and must be typed exactly as shown.
- A space is required after `#` for headings to render correctly.
- Symbols display as plain text if the file does not have a `.md` extension.

---

## Frequently Asked Questions

**Can I use Markdown in any text editor?**
Yes. Since Markdown files are plain text, they can be opened and edited in any text editor. However, only editors or platforms with Markdown support, such as VS Code or GitHub, will render the formatting visually.

**Do I need an internet connection to write Markdown?**
No. Markdown files can be created and edited offline. An internet connection is only required to push files to GitHub or view them online.

**Can I convert a Markdown file to another format?**
Yes. Markdown files can be converted to formats such as HTML or PDF using tools like Pandoc or extensions available in VS Code.

---

## Troubleshooting

**Scenario: Formatting does not render correctly.**  
Solution: Confirm the file has a `.md` extension and the syntax is correctly formatted before saving.

**Scenario: Preview does not open in VS Code.**  
Solution: Install the "Markdown All in One" extension from the Extensions panel, then reopen the file.

**Scenario: A table does not display in a table format.**  
Solution: Confirm each row has the same number of `|` symbols as the header row, and that the separator row uses at least three hyphens per column, such as `|---|---|`.

---

## Best Practices

- Use one blank line between a heading and the paragraph that follows it, to ensure correct rendering.
- Use consistent heading levels (`#`, `##`, `###`) to maintain a clear document hierarchy.
- Add a space after `#` and before the heading text, since Markdown requires it to recognize a heading.
- Preview the file before publishing, to confirm that headings, lists, and tables render as expected.
- Use relative paths for links and images within the same project, to keep them working if the folder is moved.
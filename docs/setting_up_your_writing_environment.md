# Setting up your writing environment
When you start thinking about documentation, the first question that usually pops up is:  
“**What tool should I use to write all this?**”

That’s a totally fair question. The good news is, you don’t need anything fancy or expensive to get started.  

For this setup, we’re going to use **Markdown** as the writing format and **Visual Studio Code (VS Code)** as the editor. Both are lightweight, powerful, and completely free.

## Why Markdown?
Markdown is a super simple, clean way to write formatted text using plain text. It lets you add headings, lists, links, and even code blocks without messing around with clunky menus or strange formatting.  

## Why Visual Studio Code (VS Code)
VS Code is a free, open-source code editor made by Microsoft. It works on Windows, macOS, and Linux, and has excellent support for Markdown files.

It’s fast, customizable, and has a huge collection of extensions that can improve your writing workflow.

## How to set it up
### Install Visual Studio Code  
1. Go to https://code.visualstudio.com
2. Click Download for your operating system (Windows, macOS, or Linux).
3. Run the installer and follow the setup instructions.
4. Once installed, open VS Code.

### Create your documentation folder  
1. Choose a place on your computer to store your docs (e.g., Desktop or Documents)
2. Create a new folder and name it something like my-docs
3. Inside that folder, create a new file called getting-started.md

3. Open the folder in VS Code
Open VS Code

Click File > Open Folder and select the folder you just created

Your new Markdown file (getting-started.md) should be visible in the file explorer

4. Add your first content
Open getting-started.md and paste this starter content:

markdown
Copy
Edit
---
title: Getting Started
slug: /getting-started
---

## Welcome to the Docs

This is your first documentation page. 🎉

You can:
- Make bullet lists
- Use **bold** or *italic* text
- Add [links](https://example.com)
- Write `inline code` or full code blocks
5. Install helpful extensions (optional but recommended)
In VS Code, install these extensions to make writing easier:

Markdown Preview Enhanced
Shows a live preview of your Markdown.
To install: Open the Extensions tab (Ctrl + Shift + X), search for the extension, and click Install.
Use Ctrl + Shift + V to preview your file.

Prettier – Code Formatter
Automatically formats your Markdown every time you save.
After installing, go to Settings (Ctrl + ,), search for Format On Save, and enable it.

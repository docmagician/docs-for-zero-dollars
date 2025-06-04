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
3. Open VS Code, click **File** > **Open Folder**, and select the folder you just created.  
   Your new Markdown file (getting-started.md) should be visible in the file explorer.  
4. Add your first content.
Before you add your content, start by adding the frontmatter (the part with ---, title, and slug) at the very top of each file. The frontmatter gives the static site generator important details about your content, like its title and how it should be displayed.
Here’s an example of what the frontmatter looks like:
```
---
title: "The name of your page"
slug: "The URL path for this page"
date: 2025-05-29
tags:
  - markdown
  - static-site
category: "Guides"
--- 
```
#### Install these free VS Code extensions

To make your Markdown writing smoother, install these two free extensions:  
Markdown Preview Enhanced  
This extension shows a live preview of your Markdown as you type, helping you see exactly how your content will look.  

Prettier – Code Formatter  
Prettier automatically formats your Markdown files every time you save, keeping your code clean and consistent.

**How to install and use it**:
1. Open the Extensions panel in VS Code.
2. Search for your add-ins’ name and click Install.
3. For Previewer: Once installed, press Ctrl + Shift + V to open the live preview next to your editor.
5. For Prettier: After installation, open Settings (Ctrl + ,), search for Format On Save, and turn it on.

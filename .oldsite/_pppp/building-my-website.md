---
layout: pppp_post
mathjax: true
title: "Building my website"
date: 2021-09-21
categories: update
---

<div class="postbox">
This post is now outdated, as I've greatly changed the way I build and post to my website. However, I'm keeping this here to document how I used to do it.
</div>

# Preamble

As part of documenting the process of my physics personal project, I think it would be appropriate to go over how I actually build and publish what I write onto my website for this project.

# Writing

## Notion

I use Notion to write and format all of these posts. It allows me to centralize my research and my final writings into a single platform and offers a wealth of formatting options for the final site that I create.

![Screenshot of my PPPP homepage](/school/pppp/assets/building-my-website/Screenshot1.png)

You can view the original Notion page I wrote this post on at [this link](https://simon-w.notion.site/Building-my-website-c2e1dfffa80c4437b87be5ac608862c2).

Notion and the way I export it for publishing *does* have some limitations, but it ultimately affords me the best balance of customizability, formatting options and ease of publishing myself.

# Publishing

## Loconotion

Loconotion is a really great tool for exporting Notion pages. Notion has a built-in export function to HTML, which would be acceptable for hosting on my website, but has a lot of limitations:

- URLs would be terrifyingly long and very ugly. For example, this page's slug (the link to access this page) would be a link with `c2e1dfffa80c4437b87be5ac608862c2.c2e1dfffa80c4437b87be5ac608862c2` in it with the default export. That's not great at all: Loconotion generates nicer slugs for pages automatically and also supports manually setting slugs in a configuration `toml` file, which shortens and prettifies all of the URLs on my site nicely.
- Many Notion formatting features aren't supported in the default export. Funnily enough, Loconotion actually supports many of them better than the **included export function**! This includes:
    - Cover images at the top of pages
    - Database views other than the table (such as lists, which I am using on this site, and boards)
    - Dark mode: dark background, light text and accompanying adjusted highlight and background colors

![Screenshot of the original Notion page](/school/pppp/assets/building-my-website/Screenshot2.png)

The original homepage written on Notion, pre-publication.

![Screenshot of the default Notion export of that page](/school/pppp/assets/building-my-website/Screenshot3.png)

The default export function in the official Notion app, viewed in a standard web browser. Notice the lack of support for dark mode, poor formatting of the top image, ugly table for the database view, and the incredibly long and ugly URL in the titlebar.

![Screenshot of the final Loconotion export](/school/pppp/assets/building-my-website/Screenshot4.png)

Final export in Loconotion, viewed in a standard web browser. Notice the very nicely formatted URL, very similar and much prettier formatting of the general page, and the preserved list view of the blog posts database.

<div class="postbox">
Update (01/10/2021): I decided to move back to a light theme for the blog.
</div>

## GitHub Pages

GitHub Pages is the hosting service that I use to host the project site. It's a subfolder within my personal website, and the site automatically updates to include changes to the blog once I export and push changes to the linked GitHub repository. Once that's done, my site can be accessed at [https://noisya55616.github.io/school/pppp/](https://noisya55616.github.io/school/pppp/)!
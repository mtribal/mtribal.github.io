---
title: Quartz as a SSG for Obsidian
language: english
date: 2024-09-23
draft: false
tags:
  - quartz
  - github-pages
  - "#obsidian"
---
Once I [took the decision to start my blog](index), I had to overcome any friction to publish content without complex setups. I had decided which authoring platform to work with, [Obsidian](https://obsidian.md/). It was the time to choose a good static-site generator. After reading pro's and con's, I decided on [Quartz](https://quartz.jzhao.xyz/).

This is how I made my blog's initial set up.

## Quartz
 
On the console, cloned the project by typing 
```bash
git clone https://github.com/jackyzha0/quartz.git
```

Before cd'ing the project directory, during a very lucid and inspired moment, I renamed it to the specially creative name `my-blog` :
```bash
mv quartz my-blog
cd my-blog
```

I followed the installation instructions, setting previously the desired node version (Quartz needs v20 at least)
```bash
nvm use 20
npm i
npx quartz create
```

The last command asks the user 2 questions for configuring the project. In my case, I chose the following options:
>- *Choose how to initialize the content in `./my-blog/content`*: **Empty Quartz**

>- *Choose how Quartz should resolve links in your content*: **Treat links as shortest path**

## Obsidian

In this case, I simply started a new vault called `my-blog` and set the vault directory `my-blog/content`. Time will tell if setting the `content` directory was a good or bad decision. My purpose was to avoid any distraction and show only the files I am interested in, for publishing, and nothing else.



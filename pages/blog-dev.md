---
layout: page
title: Blog Developments
date: 2019-04-20
permalink: /dev-notes/
---
Last Modified: {{ page.date | date: "%b %d, %Y" }}

The stark white is nice for reading documents, but perhaps we can get some visual stuff going on too?
![](https://images.unsplash.com/photo-1516780508808-137eba9e614e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1029&q=80)

Setting up features for this blog.

- [x] `_drafts`  
Set up a drafts folder for works in progress. This post used to live there until I set these things up!
- [x] `pages`  
Set up a directory to collect pages in. This just keeps the project root cleaner. Permalinks can still be configured from front matter.
- [x] `config.yml`  
Add a bit of customization&#8253;
- [x] `_sass`  
Customize some styles and tidy up this blog
- [ ] `_layouts`  
I haven't added any overrides here yet. To figure out what to replace I can look in the theme's [[source](https://github.com/jekyll/minima/)] 
- [ ] `images`  
As above, I need to work the images into the layout of the site. maybe use front matter variables?
- [ ] [`disqus`](https://disqus.com/admin/install/platforms/jekyll/)  
I'm strongly considering adding disqus comments. Comments are one silk thread that weaves this social web.

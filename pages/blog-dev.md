---
layout: page
title: Blog Developments
date: 2019-04-24
permalink: /dev-notes/
---

![from https://unsplash.com/@korpa](https://images.unsplash.com/photo-1516780508808-137eba9e614e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1029&q=80)

Setting up features for this blog.
- [x] `_drafts`  
Set up a drafts folder for works in progress. This post used to live there until I set these things up!
- [x] `_pages`  
Set up a directory to collect pages in. This just keeps the project root cleaner. Permalinks can still be configured from front matter.
- [x] `config.yml`  
Add a (very tiny) bit of customization&#8253;
- [x] `_sass`  
Customize some styles and tidy up this blog
- [x] `collections: _quotes/`  
Created a collection to keep [quotes](/quotes/).
- [x] `_layouts`  
We started to override some defaults, but not much has been built out yet.  
To figure out what to replace I can look in the theme's [source](https://github.com/jekyll/minima/)
- [ ] `assets/img/`  
As above, I need to work the images into the layout of the site better. maybe use front matter variables?
- [ ] `_menu`  
Set up a collection for menu items, override \_includes/header.html
- [ ] [`disqus`](https://disqus.com/admin/install/platforms/jekyll/)  
I'm strongly considering adding disqus comments. Comments are one silk thread that weaves this social web.
- [ ] `_changelogs`  
start a changelog and standardize messaging formats.
```
workflow:
tasklist -> changelog -> release notes
```



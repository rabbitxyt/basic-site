---
layout: post
title:  添加照片
date:   2017-10-10 22:03:08 -0400
categories: 
---


今天找到了不错的image gallery的代码，效果参见本网站右上角 Image Gallery

下载链接：[github code](https://github.com/opieters/jekyll-image-gallery-example/tree/gh-pages){:target="_blank"} 

博客文章链接：[blog post](https://olivierpieters.be/blog/2016/02/26/creating-a-jekyll-image-gallery){:target="_blank"}

提纲：
<br>

### Creating the Gallery Data

In `_data` directory:

- Create a set of e.g. 24MP, 12MP, 6MP, 3MP and 1MP pictures

- Feed to a Python script and generate the YAML data

- You can add title and caption to a specific picture
  
### Creating the HTML Page


- Define `gallery.html` in `_layouts` 

- Define `gallery-layout.html` in `_includes`

### Updating the HTML Head


### Creating a Gallery Overview Page

- Create `index.html`

- Create `overview.yml` in the `data` folder
  
### Adding Some Styling with SCSS

- Create `gallery.scss`
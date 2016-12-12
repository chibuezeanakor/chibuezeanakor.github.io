---
title: Portfolio Website
layout: post
categories: [blog, projects]
tags: [Jekyll, Material Design Lite, GitHub Pages]
banner: portfolio_website_banner.png
image: portfolio_website_image.png
github_repo: chibuezeanakor.github.io
---

I was inspired by Google's Material Design Lite template for websites and I really needed a portfolio website, so I wanted to see if I could build one for myself. Luckily, Google had many templates for me to choose from.

First, you'll have to figure out what your purpose is for building your site. Then, you have to choose the [template][1] that best suits your needs. Mine was to build a portfolio, so it made sense for me to choose the [Portfolio Theme][2]. Next, you have 2 opitons: go to [GitHub][3] and clone the repository of the template that you want to use, or download the template from the templates page in the first link.

Once you have the files on your computer, you can install [Jekyll][4]. After you have Jekyll installed, you can run the command, `jekyll new site-name-here`, replacing `site-name-here` with whatever you want to name your site.Then, open up your favorite text editor and you will see folders, such as `_layouts`, `_includes`, and `_posts`.

Once you navigate to the folder where your Jekyll website resides, you'll see that there is a file named `_config.yml`. Go to that file and edit the values of the variables that are already present for your own purposes.

You can store pieces of code that are the same on every page, such as the head, header, and footer tags (and everything in them), in the `_includes` folder. From there, you can create your layouts. Mine are `default` and `post`, which are in the `_layouts` folder of this repository, which is located at the bottom of this page. 

This page and Shuttle Reminder use the `post` layout, whereas the Portfolio and Contact pages use the `default` layout. This is because each of these pages has a codebase similar to its corresponding layout. If you go to this website's GitHub repository, you'll notice that my index page looks similar to the index page of the template, with a few minor changes.

You can specify the layout, title, tags, categories, and more at the top of the page, which is known as YAML Front Matter. You can even add your own custom variables to reduce your workload.

For this website, I tried to make it look as close to the orignal as possible, while using as little code as possible. I also paid attention to the sizes of the images on the original template and modified my images to correspond to them. If you want to customize your theme colors, I recommend using the [Custom CSS Theme Builder][5] to pick your primary and accent colors, then change the `head.html` file in the `_includes` folder, where you see a similarly named tag with different colors, and replace it with the `<link>` tag that you see at the bottom of the Theme Builder page. As you can tell, my primary color is red and my accent color is blue.

This website just launched, so there is not much content on it yet, but as I build more software applications, it'll start to become more wholesome.



[1]: https://getmdl.io/templates/index.html
[2]: https://getmdl.io/templates/portfolio/index.html
[3]: https://github.com/google/material-design-lite/tree/mdl-1.x/templates
[4]: http://jekyllrb.com
[5]: https://getmdl.io/customize/index.html

---
layout: post
title:  "Hello, World"
date:   2014-12-15 21:50
author: "asmalldev"
read_time: "5 minutes"
article_overview: "Hello, World! For my first post, I thought it would be appropriate to talk about the creation process of this site. To build this site, I've written original HTML and CSS from the ground up (with just a bit of javascript for flare). I wanted to keep the back end as simple as possbile and easy to..."
---

##HTML, CSS, and Jekyll, Oh My
To build this site, I've written original HTML and CSS from the ground up (with just a bit of javascript for flare). I wanted to keep the back end as simple as possbile and easy to maintain. With that in mind, I have to say: the ammount of functionality and design you can get out of CSS and HTML alone is impressive to say the least.

In keeping with my goal of simplicity, rather than use a complicated content management system for extra functionality (think wordpress, droopal, and the like) I used a static site generator. The static site generator I've chosen is Jekyll (which is popular and has relatively good documentation). Jekyll is fairly simple to set up and use. This is *especially* true if you are familiar with the concept of static site generation and/or with template languages like Liquid (which is what Jekyll uses). I'll say more on Liquid in a bit.

The concept of static site generation is simple: raw files of CSS, HTML, javascript, and markdown go in to Jekyll and a pre-built site comes out and is served. Bon App&eacutetit. This approach is favored for its simplicity, ease, and security. The most commonly stated reason that this is more secure is that there's no code being executed in the browser, it's all done when Jekyll builds the site. If something is executing code, it can be vulnerable- and static sites do not.

Jekyll/ Liquid (it's template engine of choice) also includes some very handy features like includes and layouts. By specifying a layout in the .yaml or .yml front matter ()

Combined with Github pages I am able to host this site in a git repository for free! Which makes me want to ~~laugh maniacally and pet a kitten at the same time~~ throw a bitcoin towards github as thanks. 


###this is a smaller heading
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

###this is an even smaller heading...
Jekyll also offers powerful support for code snippets:

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help

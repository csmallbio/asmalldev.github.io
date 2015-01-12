---
layout: post
title:  "Hello, World:<br>HTML, CSS, and Jekyll (Oh Myyy)"
date:   2015-1-10 14:02
author: "asmalldev"
read_time: "5 minutes"
article_overview: "Hello, World! For my first post, I thought it would be appropriate to talk about the creation process of this site. To build this site, I've written original HTML and CSS from the ground up (with just a bit of javascript). I've kept in mind that HTMLL and CSS alone provide an impressive amount of functionality and..."

---

##HTML, CSS, and Keeping Things Lightweight
Hello, World! For my first post, I thought it would be appropriate to talk about the creation process of this site. To build this site, I've written original HTML and CSS from the ground up (with just a bit of javascript). I've kept in mind that HTMLL and CSS alone provide an impressive amount of functionality and design and that not using any bulky dynamic content is freeing. I also did this because I want to keep the back end as simple as possible and easy to maintain.

###Jekyll: Simple Static Site Generation With Functionality
In keeping with my goal of simplicity, rather than using a complicated content management system (CMS) for extra functionality (think wordpress, droopal, and the like) I use a static site generator. The static site generator I've chosen is called Jekyll (which is popular and has relatively good documentation). Jekyll is fairly simple to set up and use. This is *especially* true if you are familiar with the concept of static site generation and/or with template languages like Liquid (which is what Jekyll uses). Jekyll allows me to turn my markup, text, and styling into a static site that includes extra functionality like a blog section, layouts, and includes, to name just a few.

The concept of static site generation is relatively simple: raw files of CSS, HTML, javascript, and markdown go in and a pre-built site comes out, ready to be served. Bon Appetit. This approach is great for it's ease, and security. I can personally advocate for the simplicity of static site generation after building this site. I like that I can keep all the parts of my site local and editable with the program of my choice. Jekyll simply takes these building blocks organized in a specific directory structure (posts in one directory, layouts in another, and so on) and puts them together to make a static site. Simple. I do admit the nitty gritty of where to put what and how to make use of templates can take some fiddling at times, but still this is undeniably more lightweight than using a CMS like wordpress. Static site generation like that of Jekyll is also hailed for it's security benefits. A common rule for security is if something is executing code it can be vulnerable to attack. Often this is stated as a reason that static site generation is more secure: there's no code being executed like there is with complicated CMS's, it's all done beforehand when Jekyll builds the site. The bottom line is that static sites don't execute code in the browser, and that makes them more secure. (Disclaimer: I'm **not** a security expert.)

Jekyll and Liquid (its template engine of choice) include numerous ways to make building and maintaining sites more simple and add functionality. For example, in my site I make use of includes and layouts to simplify creation and editing. Includes allow me to isolate parts of HMTL or CSS and add them into the site in specific places rather than duplicating markup or styling to have in each file. Layouts are similar: using layouts I can write HTML files that provide basic structure for different page types (one for a blog post, another for the about page, etc). In the case of my site, I use a master layout that contains the menu and footer that appear on all pages of the site. This allows me to edit one HTML file rather than a different one for each page (what a relief). This also ensures I don't end up with inconsistent menus or footers across different pages. These simple yet powerful features of Jekyll make creating and managing my site more functional and in some ways easier than plain HTML and CSS while retaining the simplicity of having the files locally editable- just the way I like them.

### Jekyll and Github Pages: Hosting That's Easy As Eating Free Pie...
<div class="center_imgs">
<img class="post_img" src="/img/octojekyll.png" alt="Jekyll and Github">
<img class="post_img" src="/img/post0/equals.png" alt="equals">
<img class="post_img" src="/img/post0/pie.png" alt="pie">
</div>
Combined with Github pages I am able to host this site in a git repository for *free*. This is the cherry on top. The simplicity that Jekyll brings to building and maintaining a site and the ease of hosting on Github pages makes the whole process a joy and basically makes me want to <s>laugh maniacally while petting a kitten</s> donate a bitcoin or two to Github and Jekyll. 

### Long Story Short:
Jekyll and Github were instrumental in the making of this site and provide a simple, functional, and secure solution for static site generation and deployment. I highly encourage you to check out both [Jekyll](http://www.jekyllrb.com) and [Github Pages](http://www.pages.github.com). Head over to the credits tab up above to see the other useful tools I've used for this site!
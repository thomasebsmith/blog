# Thomas Smith's Blog
This repository contains the code for Thomas Smith's blog. The blog is written
in Jekyll and hosted on GitHub pages. The blog primarily contains
programming-related articles.


### Project Structure
```
_includes/           Contains partial files that can be pasted into HTML layouts
_layouts/            Contains the layouts for various sections of the blog
    default.html     The HTML for the main page's layout
    post.html        The HTML for each post page's layout
_posts/              Contains Markdown files with content for each blog post
_scss/               Contains SCSS stylesheets to be included in style.css
README.md            A description and basic information for this project
_config.yml          Jekyll configuration for the blog
index.html           The content of the main page
style.scss           The SCSS stylesheet to be transformed into style.css
```

### Deployment
This site should be deployed using Jekyll. It is optimized for GitHub pages but
should work in a standard Jekyll environment. Note that it is intended to be
hosted as a part of a larger website (e.g. at a path like /blog). This larger
website should provide:

 - /main.css
 - /favicon.png
 - /index.html
 - /projects.html
 - /contact.html

If hosted on a path other than /blog, the \_includes/header.html file should be
changed to correspond.

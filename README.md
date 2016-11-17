# Mustard theme for Jekyll

Hello!

I was designing from scratch a Jekyll theme for my personal site and I thought it could be useful to others, so here I am publishing the basic files you need if you like it or if you want to contribute and make it better.

## How to use the Mustard theme

The current template has 3 main pages: a home page, an "about me" page, and a blog.

Set up your site at `_config.yml` and start by adding your content at `about.md` and `index.md`.

```
.
├── _config.yml           # Configuration data
├── _includes             # Partials of the site which are used in most pages
|   ├── footer.html           # Footer line
|   ├── head.html             # Head HTML tag contents
|   ├── menu.html             # Link menu
|   └── header.html           # Hello! message container
├── _layouts              # Site templates
|   ├── default.html          # Default template
|   ├── blog.html             # Blog template: shows titles and excerpts for posts
|   ├── home.html             # Home page. Includes index.md and lists posts
|   └── post.html             # Template for posts in the blog
├── _posts                # Blog posts
|   ├── 2016-10-10-articles-you-must-read.markdown
|   └── 2016-10-10-hello-world.markdown
├── css                   # Styles
|   └── main.css
├── about.md              # Content for the "About me" section
├── index.md              # Content for the homepage
├── notes.md              # Notes section
└── feed.xml              # ATOM feed

```

## Preview
![](theme_preview.png)

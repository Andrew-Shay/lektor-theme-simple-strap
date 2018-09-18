# Simple Strap - Lektor Theme

Simple Strap is a theme for [Lektor](https://www.getlektor.com/).

It's a clean, simple, black and white theme.  
It's built using [Bootstrap 4](https://getbootstrap.com/).  
The base theme is a modified version of [Lux](https://bootswatch.com/lux/) by [Bootswatch](https://bootswatch.com/).  
Lux was modified with [bootstrap.build](https://bootstrap.build/).  
See `css_src/` for the CSS source.

## Templates

* `templates/blog.html` - Blog listing.
* `templates/blog-post.html` - A single page that contains one blog post.
* `templates/layout.html` - The base template for every page. Includes header and footer.
* `templates/page.html` - The template for the homepage. A two column page. The right column will be the same for every page with this template.
* `templates/page_one_column.html` - A single column page.
* `templates/page_two_column.html` - A two column page.
* `templates/macros/blog.html` - Renders a single blog post. 
* `templates/macros/pagination.html` - Renders the Previous and Next buttons for blog listing.

## Models

* `models/page.ini` - Body content formatted in markdown.  Used for templates `page.html` and `page_one_column.html`.
* `models/page_html.ini` - Body content formatted in HTML.  Used for template `page_one_column.html`.
* `models/page_two_column.html.ini` - Body content and Right content formatted in HTML. Used for template `page_two_column.html`.
* `models/page_two_column_markdown.ini` - Body content and Right content formatted in markdown. Used for template `page_two_column.html`.

# Screenshot

[Demo Site](https://andrew-shay.github.io/lektor-theme-simple-strap/)  

![example-site image](https://github.com/Andrew-Shay/lektor-theme-simple-strap/blob/master/screenshot.png)

# License

MIT
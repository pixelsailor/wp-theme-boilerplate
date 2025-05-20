# Boilerplate theme for Wordpress
Outline of theme structure:

```
my-custom-theme/
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       └── logo.png
│
├── inc/
│   ├── setup.php            # Theme setup (menus, supports)
│   ├── scripts.php          # Enqueue scripts and styles
│   ├── custom-post-types.php # CPTs if needed
│   └── widgets.php          # Widget areas
│
├── template-parts/
│   ├── header/
│   │   └── site-header.php
│   ├── footer/
│   │   └── site-footer.php
│   ├── content/
│   │   ├── content-page.php
│   │   └── content-single.php
│   └── loops/
│       └── loop-posts.php
│
├── languages/               # .pot/.po/.mo translation files
│
├── screenshot.png           # Theme screenshot for WP dashboard
├── functions.php            # Loads files from /inc
├── style.css                # Theme meta info + main styles
├── index.php                # Fallback template
├── header.php               # General header
├── footer.php               # General footer
├── sidebar.php              # Optional sidebar
├── page.php                 # Default page template
├── single.php               # Default single post template
├── archive.php              # Archive pages
├── 404.php                  # Not found page
├── search.php               # Search results
└── comments.php             # Comments template
```

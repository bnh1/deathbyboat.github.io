# Nord Minimal Pelican Theme

A minimal Scandinavian-inspired Pelican theme with:
- elegant typography
- centered content column
- responsive design
- dark mode support
- lightweight/no JavaScript

## Installation

Copy the theme into your Pelican themes directory:

```bash
themes/nord-minimal
```

Then set in `pelicanconf.py`:

```python
THEME = "themes/nord-minimal"

SITENAME = "Your Site Name"

MENUITEMS = (
    ("About", "/pages/about.html"),
)
```

## Recommended Plugins

```python
PLUGIN_PATHS = ["pelican-plugins"]
PLUGINS = ["sitemap"]
```

## Example Content Structure

```
content/
├── pages/
│   └── about.md
└── posts/
    └── first-post.md
```

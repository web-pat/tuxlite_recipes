# Tuxlite_Recipes
A [Pelican](https://getpelican.com) theme based on [tuxlite_lbs](https://github.com/getpelican/pelican-themes/tree/master/tuxlite_lbs), modified to create simple and responsive recipes websites.

## Why this theme?
If you have ever looked up a cooking recipe on the net and felt annoyed by heaps of circumstantial information burying the essentials, tons of javascript and pictures bogging down page load speeds, then this theme is right up your alley.

This theme harnesses Pelican to create your personal recipes website on lightning fast rendering html, cutting right through the bullshit!

## Screenshot
![Screenshot](screenshot.webp)

## Example `pelicanconf.py`

```python
from datetime import date

AUTHOR = "Your Name"
SITENAME = "My Recipes"
SITEURL = ""  # Set to your site's URL when publishing
DEFAULT_LANG = "en"
THEME = "path/to/tuxlite_recipes"

CURRENT_YEAR = date.today().year
DISPLAY_PAGES_ON_MENU = True
MENUITEMS = (("Home", SITEURL or "/"),)
LINKS = (("Pelican", "https://getpelican.com"),)
SOCIAL = (("GitHub", "https://github.com/yourname"),)
```

Change the theme path and example values to suit your site. Add pages and
recipe articles to your Pelican `content` directory. For a fuller configuration,
see [this site's `pelicanconf.py`](https://codeberg.org/web_pat/rezepte_patrickweber_info/src/branch/master/pelicanconf.py).

## Setup
Clone or download this repository, then set `THEME = 'path/to/tuxlite_recipes'` in your `pelicanconf.py`. Make sure Pelican and its dependencies are installed (`pip install pelican`), and run `pelican content` to generate your site. For a full walkthrough, check out this [howto article](https://www.patrickweber.info/en/setting-up-a-static-recipe-website-with-pelican-and-tuxlite_recipes/).

## License
This project is licensed under the [MIT license](./LICENSE).

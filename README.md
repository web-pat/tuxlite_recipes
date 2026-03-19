# Tuxlite_Recipes
A [Pelican](https://getpelican.com) theme based on [tuxlite_lbs](https://github.com/getpelican/pelican-themes/tree/master/tuxlite_tbs), modified to create simple and responsive recipes websites.

## Why this theme?
If you have ever looked up a cooking recipe on the net and felt annoyed by heaps of circumstantial information burying the essentials, tons of javascript and pictures bogging down page load speeds, then this theme is right up your alley.

This theme harnesses Pelican to create your personal recipes website on lightning fast rendering html, cutting right through the bullshit!

## Screenshot
![Screenshot](screenshot.webp)

## Pelican configuration parameters
### Copyright date
In order for your webpage to always display the actual year in your copyright notice, add this parameter at the beginning of your config file:

```
import datetime
CURRENT_YEAR = datetime.date.today().year
```

### Template
For an example on how to setup your pelicanconf.py you may checkout the config of [this](https://codeberg.org/web_pat/rezepte_patrickweber_info/src/branch/master/pelicanconf.py) existing website.

## Setup
Need help setting up your own recipe website? Check out this [howto article](https://www.patrickweber.info/en/setting-up-a-static-recipe-website-with-pelican-and-tuxlite_recipes/)

## License
This project is licensed under the [MIT license](./LICENSE).

# Qutebrowser Dark Theme

This is a forked version of the following project:
github.com/davidinspace/qutebrowser_dark_solarized

## Screenshots

## Style

There is one stylesheet :
- *dark_theme.css* This is my attempt to change the dark_solarized .css file that the GitHub user, davidinspace, has provided, but to modify it to be a dark theme instead, since I prefer dark themes over solarized themes when it comes to web browsers. Also, this doesn't currently exist for qutebrowser as well, so I felt like this would benefit a lot more people than myself.

## Usage

### In settings

Tape `:set` and put their names in `content.user_stylesheets` with your path.

Example :

```
["dark_theme"]

```

### In config

In `config.py` :

```
c.content.user_stylesheets = [
    'dark_theme.css'
]
```

## Revisions

Please feel free to correct this project by submitting a pull request to include changes for other sites. This project aims to be a good template for a dark theme, but would definitely benefit by being modified to accommodate popular sites.

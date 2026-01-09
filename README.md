# User style for trade 2

Adds different highlighting to mods on the trade 2 site

![sample](./img/sample.png)

- [User style for trade 2](#user-style-for-trade-2)
  - [Install](#install)
  - [Styles](#styles)
    - [Raw Tag Based](#raw-tag-based)
    - [Raw Tag Based, compact only](#raw-tag-based-compact-only)
    - [Kvan7 CSS (Personalized Tag Based)](#kvan7-css-personalized-tag-based)

## Install

Given you have [stylus](https://github.com/openstyles/stylus) or some other userstyle manager (or if you do it manually),

1. Find which style you want to install
2. Click to go to that file
3. Click "Raw" in the top right
  a. This should open in with your userstyle manager, just hit save there

or use the install links below

## Styles

### Raw Tag Based

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://github.com/Kvan7/gist-trade-highlight/raw/refs/heads/main/tagOnly.user.css)

Very rudimentary, just strictly takes the tags on the mods and adds different colors to different tags. The only changes
to strictly the in game tags are adding different colors to str, dex, and int, and making
+levels without the "gem" tag display as +levels with the "gem" tag.
![sample](./img/sample.png)

### Raw Tag Based, compact only

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://github.com/Kvan7/gist-trade-highlight/raw/refs/heads/main/tagOnlyCompact.user.css)

Same as above, but doesn't change the "default" view, only the compact one(which had a small amount of highlighting before)

![sample](./img/compactSample.png)

### Kvan7 CSS (Personalized Tag Based)

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://github.com/Kvan7/gist-trade-highlight/raw/refs/heads/main/kvanRules.user.css)

This is the one I use. So it has some decent opinionation on what it highlights, but has additional bells and whistles.
Also will be most actively updated since I use it.

NOTE: ***Hides "Bonded: *" rune modifiers***

(I should really make it hide minion mods too. . . . )

# Xenapto theme for Ghost

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) derived from the [Crisp](https://github.com/kathyqian/crisp-ghost-theme) theme by [Kathy Qian](http://kathyqian.com).

![Index](https://raw.github.com/kathyqian/crisp-ghost-theme/master/index.png)

### Installation

1. Download the files
2. Change the link color on *line 78* in **xenapto/assets/styles/xenapto.css**
3. Manually add/remove all links to static pages by copying (or deleting) *line 26* in **xenapto/default.hbs**
4. Replace the `example` disqus_shortname with your shortname on *line 11* of **xenapto/post.hbs**, or delete the #comments div to remove comments altogether
5. Add the "xenapto" folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

### Additional Suggestions

* Add code for Google Analytics in **xenapto/default.hbs** after `{{ghost_foot}}`
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)

### License

[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/)

### More Screenshots

![Post](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post.png)

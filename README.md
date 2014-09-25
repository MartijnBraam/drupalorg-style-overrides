Drupal.org style overrides
==========================

These less stylesheets compile to a single css file that can be injected (by the browser plugin of your choise) into https://www.drupal.org

Modifications:

* Made the whole site slightly wider
* Made the header slightly less high (except on the frontpage)
* Added boxes around all internal blocks (makes page structure more visible)
* Made code boxes and tables wider
* Dimmed less important information in comments and nodes (post date and author) to make finding information quicker
* Moved all non-body content in comments to the right (makes scanning comments way easier)
* Changed font on site to your os's default sans-serif font and increased line spacing
* Styled and aligned form elements on various pages
* Made dredditor styles more consistant with rest of the page
* More small changes to clean up the layout

Building
--------

The `style.css` in the repository should be the most recent build from my IDE. To compile it yourself:

```bash
$ git clone git@github.com:MartijnBraam/drupalorg-style-overrides.git
$ cd drupalorg-style-overrides
$ lessc style.less > style.css
```

Screenshots
-----------
[![](https://raw.githubusercontent.com/MartijnBraam/drupalorg-style-overrides/master/screenshots/comparison.png)](https://raw.githubusercontent.com/MartijnBraam/drupalorg-style-overrides/master/screenshots/comparison.png)

[![](https://raw.githubusercontent.com/MartijnBraam/drupalorg-style-overrides/master/screenshots/issue-page.png)](https://raw.githubusercontent.com/MartijnBraam/drupalorg-style-overrides/master/screenshots/issue-page.png)

# Ben Cipollini's website.

This website was built from the `&ast;folio` Jekyll theme (<a href="http://liabogoev.com/-folio">live &ast;folio demo</a>). Jekyll is a Ruby-on-rails gem that Github supports; if you create a repository called `[your-username].github.io` and commit a Jekyll project to the `master` branch, Github will build the website for you and host it--cool!


## Setup & Development

### Install Jekyll and RubyGems

Here are [complete instructions](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll).

Refer to the [Jekyll documentation](http://jekyllrb.com) for further help.


### Running Locally

* `git clone https://github.com/bcipolli/bcipolli.github.io`
* `cd bcipolli.github.io`
* `jekyll serve`


## Adding / Editing / Deleting Content

There are a few different types of content:

* Base pages (home, non-profit, academia, for-profit, etc)
* "News (Homepage content)
* Etc.


### Base pages

These pages show in the top navigation bar, and represent the most basic divisions of content. Content lives in the repository directory.

#### Adding content

1. Duplicate an existing page; save with any unique (.md) filename in the repository directory.
2. Edit the header content, specifically: `nav-title` (appearance on website header) and `permalink` (URL)
3. Customize the content!


#### Updating content

* To **update the sort order** of items, change the `weight` property within the MD file header.


### "News"

These items highlight large items going on with me, in any domain. Content lives in the `_news` directory.

#### Adding content

1. Duplicate an existing page; save by `%Y-%m-%d-keyword.m` syntax (e.g. `2017-11-05-website-update.md`)
2. Add core header information (e.g. `title`, `date`, `description`)
3. Either add: `redirect` (offsite content on click), or content below `--` (to view the item on site)

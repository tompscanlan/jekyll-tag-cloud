jekyll-tag-cloud
================

based on a [gist][https://gist.github.com/710577] by [Ikka][https://github.com/ilkka]

A [jekyll plugin][http://jekyllrb.com/docs/plugins/] to make a tag cloud that can be inserted into any generated page, with associated page for each tag referencing a link to the original post.

## how to use it?

Drop these files into the `jekyll/_plugins` dir for your site

On any page, you can add the tag: `{$ tag_cloud %}` which will be replaced with a cloud consisting of links to "tag" pages.
Each of those "tag" pages has references back to the originating pages.

The tag pages are created as `_site/tag/index.html`.

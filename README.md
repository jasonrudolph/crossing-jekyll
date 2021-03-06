# Crossing

A [Jekyll](https://jekyllrb.com/) theme.

![Screenshot](screenshot.png?raw=true)

[Demo](https://jasonrudolph.github.io/crossing-jekyll/) × [Download](https://github.com/jasonrudolph/crossing-jekyll/archive/gh-pages.zip)

Demo images are from [Unsplash](https://unsplash.com/).


## Cover images

Site cover image:

```yml
# _config.yml
image: /crossing-jekyll/images/site-image.jpg
```

Post cover image:

    ---
    image: /crossing-jekyll/images/post-image.jpg
    ---


## Author information

To have author bylines and bio at bottom of posts, add configuration like the following in `_config.yml`:

```yml
author:
  name: John Doe
  bio: An awesome bio # Author info at bottom of post only shows if bio exists
  avatar: /crossing-jekyll/images/avatar.jpg
```

## Social meta tags

Crossing generates [Open Graph](https://developers.facebook.com/docs/sharing/webmasters) and [Twitter Cards](https://dev.twitter.com/cards/overview) meta tags automatically for better social media sharing. There are two extra settings:

```yml
# _config.yml
og_image: /images/og-image.jpg # Fallback og:image when no page.image or site.image. at least 200 x 200px.
twitter_site: # twitter:site. Your Twitter username without "@"
```

### Meta description

`page.excerpt` is used for meta description of posts and pages. It is the first paragraph by default for posts. For pages you have to set it in the Front Matter:

    ---
    excerpt: An excerpt
    ---

Twitter Cards requires meta description. Facebook could infer it from the page if it's empty.


## License

[CC0](LICENSE)

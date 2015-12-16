# Lobbying Transparency

Files for http://lobbyingtransparency.net/, which is a static site, compiled with [Middleman](https://middlemanapp.com/)

## To edit this site

1. Install [Middleman](https://middlemanapp.com/)
2. Clone this repository (master branch)
3. `cd` into your local version
4. `bundle exec middleman server` to run the server and watch for changes (with LiveReload)

### Files

Most of the files required for editing content, are found in the `data` directory, while files used for layout and styling are in the `source` directory.

Content is witten in Markdown, including [Kramdown footnotes](http://kramdown.gettalong.org/syntax.html#footnotes).

### Deploy to Github Pages

When you have made changes that you wish to put live, you can do so by running:

```
  $ middleman deploy
```

This will build the site and deploy it to the gh-pages branch of this repository.

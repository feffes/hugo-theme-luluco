# luluco

**_Dark theme based off the colors of luluco._**


## Screenshots

![Home](/.github/images/home.png?raw=true)
![Article](/.github/images/article.png?raw=true)
![Phone](/.github/images/phone.png?raw=true)
## Features

* Smart table of contents (will highlight and expand current section in TOC)
* Google Analytics
* [KaTeX](https://github.com/Khan/KaTeX)
* Syntax highlighting using [highlight.js](https://github.com/isagalaev/highlight.js)

## Installation

To install this theme, add it as a submodule in the `themes/` directory:

```
$ cd themes/
$ git submodule add https://github.com/feffes/hugo-theme-luluco
```

Second, specify `hugo-theme-luluco` as your default theme in the config.toml file. Just add the line

```
theme = "hugo-theme-luluco"
```

## Options

### Pagination
```
paginate = 10
```

### Smart TOC
```
[params]
    smartToc = true
```

### Disqus
```
disqusShortname = "xxxxxx"
```

### Google Analytics
```
[params]
    googleAnalytics = "UA-123-45"
```

### KaTeX
```
[params]
    katex = true
```

This option enables the KaTeX auto-render extension. To render block math, use `$$ ... $$`. For inline math, use `\\( ... \\)`. For more details, please refer to https://github.com/KaTeX/KaTeX/blob/v0.7.1/contrib/auto-render/auto-render.js#L73 .

### Others

For other configuration variables, visit [Hugo documentation](https://gohugo.io/overview/configuration/#configuration-variables).

## Post Params

### Featured Image displayed in index.html
```
+++
featuredImage = "img/foobar.jpg"
+++
```

### Hide the post from index.html
This can be used when creating an "About me"-page.
```
+++
hidden = true
+++
```

### Enable KaTeX for this post
Enable KaTeX for a specific post without enabling the global switch.
```
+++
katex = true
+++
```


## License

Licensed under the MIT License. See the [LICENSE](https://github.com/feffes/hugo-theme-luluco/blob/master/LICENSE.md) file for more details.

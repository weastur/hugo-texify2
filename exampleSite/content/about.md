+++
title = "About"
description = "A minimal, latex-style hugo theme for personal blogging"
date = "2023-06-20"
aliases = ["about-us", "about-texify2", "contact"]
author = "weastur"
+++
A minimal, latex-style hugo theme for personal blogging.
The successor of the original [TeXify](https://github.com/queensferryme/hugo-theme-texify)

<iframe src="https://ghbtns.com/github-btn.html?user=weastur&repo=hugo-texify2&type=star&count=false&size=large" frameborder="0" scrolling="0" width="170" height="30" title="GitHub"></iframe>

## Features

- **Social sharing buttons**
- **Any comment engine (giscus, remark42, hyvor, etc.)**
- **Word Counter and Reading Time**
- **[Mermaid](https://mermaid.js.org) support**
- **DuckDuckGo search**
- **Configurable root font size**
- **Buymeacoffee widget**
- **Auto numbered subtitles**
- **Simplified config**
- **Hugo modules support**
- **Tested on Chrome, Safari, Edge, Firefox**
- [Disqus](https://disqus.com/) & Google Analytics included
- Responsive design for mobile devices
- Customize the site with your stylesheets
- Math equations powered by [KaTeX](https://katex.org/)
([MathJax](https://www.mathjax.org/) has been deleted)
- Minimal CSS, No JavaScript, Blazing Fast!

\* Diff with the original texify is **bold**

## Usage

### Install as git submodule

Install:

```bash
git submodule add https://github.com/weastur/hugo-texify2.git themes/hugo-texify2
echo "theme = 'hugo-texify2'" >> hugo.toml
```

Upgrade:

```bash
git submodule foreach git pull origin master
```

### Install as hugo module

Initialize hugo modules, if not done yet:

```bash
hugo mod init github.com/<username>/<projectName>
```

add `[module]` section to your `hugo.toml`:

```bash
[module]
[[module.imports]]
  path = 'github.com/weastur/hugo-texify2'
```

load/update theme module

```bash
hugo mod get -u github.com/weastur/hugo-texify2
```

See [`hugo.toml`](https://github.com/weastur/hugo-texify2/blob/master/hugo.toml)
for an example configuration.

## Development

Install `pre-commit`

```bash
pre-commit install
make dev
```

## Acknowledgement

The following software inspires the design of this theme:

- <https://github.com/vincentdoerig/latex-css>
- <https://github.com/7ma7X/HugoTeX>
- <https://theme.typora.io/theme/Academic/>
- <https://github.com/queensferryme/hugo-theme-texify>
- <https://sharingbuttons.io>

# TeXify2

[![Hugo](https://img.shields.io/badge/hugo-0.113-blue.svg)](https://gohugo.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Build with Hugo](https://github.com/weastur/hugo-texify2/workflows/Build%20with%20Hugo/badge.svg)
![gitlint](https://github.com/weastur/hugo-texify2/workflows/gitlint/badge.svg)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/weastur/hugo-texify2/master.svg)](https://results.pre-commit.ci/latest/github/weastur/hugo-texify2/master)

A minimal, latex-style hugo theme for personal blogging.
The successor of the original [TeXify](https://github.com/queensferryme/hugo-theme-texify)

![screenshot](https://raw.githubusercontent.com/weastur/hugo-texify2/master/images/screenshot.png)

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

Visit the [demo site](https://texify2.io).

**Note:** All the features are enabled on the demo site,
but you can turn them off on your own project.
Check both `hugo.toml` of the theme and of the exampleSite.

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

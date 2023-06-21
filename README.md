# TeXify2

[![Hugo](https://img.shields.io/badge/hugo-0.113-blue.svg)](https://gohugo.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Build with Hugo](https://github.com/weastur/hugo-texify2/workflows/Build%20with%20Hugo/badge.svg)
![gitlint](https://github.com/weastur/hugo-texify2/workflows/gitlint/badge.svg)

A minimal, latex-style hugo theme for personal blogging.
The successor of the original [TeXify](https://github.com/queensferryme/hugo-theme-texify)

![screenshot](https://raw.githubusercontent.com/weastur/hugo-texify2/master/images/screenshot.png)

## Features

- **Social sharing buttons**
- **Any comment engine (giscus, remark42, hyvor, etc.)**
- **Word Counter and Reading Time**
- **[Meramid](https://mermaid.js.org) support**
- **DuckDuckGo search**
- **Configurable root font size**
- **Buymeacoffee widget**
- **Simplified config**
- **Hugo modules support**
- [Disqus](https://disqus.com/) & Google Analytics included
- Responsive design for mobile devices
- Customize the site with your stylesheets
- Math equations powered by [KaTeX](https://katex.org/)
([MathJax](https://www.mathjax.org/) has been deleted)
- Minimal CSS, No JavaScript, Blazing Fast!

\* Diff with the origianl texify is **bold**

## Usage

## Install as git submodule

Install:

```bash
git submodule add https://github.com/weastur/hugo-texify2.git themes/hugo-texify2
echo "theme = 'hugo-texify2'" >> hugo.toml
```

Upgrade:

```bash
git submodule foreach git pull origin master
```

## Install as hugo module

Initialize hugo modules, if not done yet:

```bash
hugo mod init github.com/<username>/<projectName>
```

add `[module]` section to your `config.toml`:

```bash
[module]
[[module.imports]]
  path = 'github.com/weastur/hugo-texify2'
```

load/update theme module

```bash
hugo mod get -u github.com/weastur/hugo-texify2
```

See [`config.toml`](https://github.com/weastur/hugo-texify2/blob/master/config.toml)
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

## Support

If you want to support the development or say thanks, become a GitHub Sponsor or

<a href="https://www.buymeacoffee.com/weastur" target="_blank">
<img src="https://cdn.buymeacoffee.com/buttons/default-orange.png"
    alt="Buy Me A Coffee"
    height="41"
    width="174">
</a>

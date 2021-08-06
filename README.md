# Administration Guide for [**Jekyll Theme Chirpy**][chirpy]
[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)](https://rubygems.org/gems/jekyll-theme-chirpy)
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]
[![GitHub action](https://github.com/OnkelDom/onkeldom.github.io/workflows/test/badge.svg)](https://github.com/OnkelDom/onkeldom.github.io)

## New Sites

To add a new site, take it in the `_tabs` folder and add it to `_data/locales/en.yml` in `tabs:` section.

## New Post

To add a new post, take it in the `_posts` folder and and name it in syntax `YYYY-MM-DD-article-name.md`.

## Usage

Please see the [theme's docs](https://github.com/cotes2020/jekyll-theme-chirpy#usage).

## Upgrading

First, please modify the target version number of `jekyll-theme-chirpy` in the `Gemfile` (e.g., `gem "jekyll-theme-chirpy", "~> 4.0", ">= 4.0.1"`).

After that, execute the following command:

```console
$ bundle update jekyll-theme-chirpy
```

As the version upgrades, the critical files and configuration options will change. Please refer to the [Upgrade Guide](https://github.com/cotes2020/jekyll-theme-chirpy/wiki/Upgrade-Guide) to keep your website files in sync with the latest version of the theme.

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE

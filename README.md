# Jekyll Creative Commons

Easily publish a Jekyll site with a Creative Commons license

## Usage

Include a Liquid tag with the URL of the Creative Commons license you wish to use, and Jekyll will generate HTML with the appropriate metadata.

```liquid
{% license http://creativecommons.org/licenses/by/4.0/ %}
```

## Installation

1. Add `gem 'jekyll-creativecommons'` to your site's Gemfile and run `bundle`
2. Add the following to your site's `_config.yml`:

```yml
gems:
  - jekyll-creativecommons
```

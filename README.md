# Jekyll::Latex::Converter

Use LaTeX with Jekyll.

Supports all LaTeX syntax supported by [PolyTeXnic](https://github.com/softcover/polytexnic). For Jekyll 3.0 and up.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jekyll-latex-converter'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-latex-converter

Lastly, add it to your `_config.yml` file:

    gems:
    - jekyll-latex-converter

## Usage

Create files with the `.tex` extension in the `_posts` directory, as in

`_posts/2017-07-12-test-post.tex`:

```
---
layout: post
title:  "Welcome to Jekyll 3"
categories: jekyll update
published: true
---


This is a \emph{LaTeX} file.
```
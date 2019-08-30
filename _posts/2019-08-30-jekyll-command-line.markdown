---
layout: post
title:  "Jekyll Command Line"
date:   2019-08-30 12:23:28 +0200
categories: jekyll update
---
# Command Line Usage

The Jekyll gem makes a <mark>jekyll</mark> executable available to you in your terminal. 
You can use this command in a number of ways: 
* <mark>jekyll new</mark> - Creates a new Jekyll site with default gem-based theme 
* <mark>jekyll new --blank</mark> - Creates a new blank Jekyll site scaffold 
* <mark>jekyll build</mark> or <mark>jekyll b</mark> - Performs a one off build your site to <mark>./_site</mark> (by default) 
* <mark>jekyll serve</mark> or <mark>jekyll s</mark> - Builds your site any time a source file changes and serves it locally * <mark>jekyll doctor</mark> - Outputs any deprecation or configuration issues 
* <mark>jekyll clean</mark> - Removes all generated files: destination folder, metadata file, Sass and Jekyll caches. 
* <mark>jekyll help</mark> - Shows help, optionally for a given subcommand, e.g. <mark>jekyll help build</mark> 
* <mark>jekyll new-theme</mark> - Creates a new Jekyll theme scaffold 

Typically you’ll use <mark>jekyll serve</mark> while developing locally and <mark>jekyll build</mark> when you need to generate the site for production. To change Jekyll’s default build behavior have a look through the [configuration options](/docs/configuration/).

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

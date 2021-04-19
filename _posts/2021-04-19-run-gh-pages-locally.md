---
layout: post
title: Run gh-pages branch locally in WSL
---

Running `gh-pages` locally is easy.

The documentation explains it very well:

- [https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

Alternative installation guide to install Ruby with `rbenv`.

- [https://linuxize.com/post/how-to-install-ruby-on-ubuntu-18-04/](https://linuxize.com/post/how-to-install-ruby-on-ubuntu-18-04/)

This post is a reminder to myself to easily find this documentation again.

---
I am using WSL and `ruby 2.7` to test it locally.

```
rbenv install 2.7.0
rbenv global 2.7.0
gem install jekyll jekyll-gist jekyll-sitemap jekyll-seo-tag jekyll-paginate
```

Then launch with from checkout directory with `jekyll serve`.

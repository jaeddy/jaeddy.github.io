---
layout: post
published: false
title: Blogging with Beautiful Jekyll & R Markdown
---
Several months ago I migrated my personal website from the default GitHub Boostrap setup to the more aesthetically attractive, flexible, and easy-to-use [**Beautiful Jekyll**](https://github.com/daattali/beautiful-jekyll) framework, developed by Dean Attali. More recently, I decided it would be fun if I could write and publish a small analysis &mdash; annotated in a literate programming framework like R Markdown &mdash; directly as a new blog post. 

This undertaking was made substantially easier by the excellent work of others, but it required some additional tweaking and troubleshooting. In the hope of saving others some time and pain, I thought I'd share the steps I followed and lessons I learned.

## Beautiful Jekyll

For starters, you'll need to get your site set up with Beautiful Jekyll. To do so, you can follow the instructions provided in the repo (the process is quick and easy).

(working locally vs. prose.io)

## `knitr-jekyll` and `servr`

https://www.r-bloggers.com/blogging-with-rmarkdown-knitr-and-jekyll/
https://github.com/yihui/knitr-jekyll

## Back to Beautiful Jekyll

1. Clone or download your site repo.
2. Install Ruby
3. Install `bundle`
(bundle)
(Gemfile biz: rouge)
(bundle exec)

```
servr::jekyll(command = "bundle exec jekyll build")
```

## Adventures with `htmlwidgets`: `brocks` and a `knitr-jekyll` fork

https://github.com/yihui/knitr-jekyll/issues/8
https://github.com/brendan-r/knitr-jekyll
https://brendanrocks.com/htmlwidgets-knitr-jekyll/#including-the-extra-html
http://ryankuhn.net/blog/How-To-Use-Plotly-With-Jekyll

## some additional tweaking

https://github.com/yihui/knitr/issues/1228
(build.R)
(deps renaming)
(modified snippet)
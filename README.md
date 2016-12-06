# Hugo blog theme
-----------

This is a [hugo](https://gohugo.io/) static blog engine theme, if you like this theme,please give me star  ~_~

------------
[See Dome](https://feiio.com)
# Installation
Inside the folder of your Hugo site run:
```
cd themes
git clone https://github.com/leonhe/hugo_eiio

```
# Config
Modify your configuration:
```
baseurl = "https://feiio.com/"
title = "阿拉伯的鞋匠"
languageCode = "zh-CN"
themesdir = "themes"
theme = "hugo_eiio"
Paginate=15
PaginatePath="page"
pygmentsuseclasses = true
#disqusShortname = "iyuanfei"
googleAnalytics='UA-66653712-1'
[taxonomies]
  category = "categories"
  tag = "tags"

[params]
  description = "阅读、思考、生活"
  author = "Leon He"
  github ="leonhe"
[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

```

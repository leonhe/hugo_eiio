# Hugo blog theme

This is a [hugo](https://gohugo.io/) static blog engine theme, if you like this theme,please give me star  ~_~

![screenshot](https://raw.githubusercontent.com/leonhe/hugo_eiio/master/images/screenshot.png)

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
baseurl = "site url"
title = "Site Name"
languageCode = "zh-CN"
copyright = "Copyright right infomation."
themesdir = "themes"
theme = "hugo_eiio"
Paginate=15 
PaginatePath="page"
pygmentsuseclasses = true
disqusShortname = "user id"
googleAnalytics='google analytics code'
[taxonomies]
  category = "categories"
  tag = "tags"

[params]
  description = "site description"
  author = "your name"
  github ="github username"
  securityPolicy = false #disable https content security policy
  footerRight="Your tips content" #footer right content
  addthisID="addthis.com sharder plugin id"
[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

```

# License
This theme is released under the [MIT License](https://github.com/leonhe/hugo_eiio/blob/master/LICENSE).

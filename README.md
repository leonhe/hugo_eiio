# Hugo blog theme 

This is a [hugo](https://gohugo.io/) static blog engine theme, if you like 😍 💗 this theme,please give me star🌟🌟  ~_~

## Features
- ✏️ Blog ️
- 🎩 Modern、Responsive
- 🅾️ Syntax highlight
- Emoji 😄 ,Disqus 🌐
- 🏙 🎇 🌆 Post thumbnail images

[See Demo](https://heyuanfei.com)

<!-- # Screenshot
 !-- ![screenshot](https://raw.githubusercontent.com/leonhe/hugo_eiio/master/images/screenshot.png) -->

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
languageCode = "site language code"
copyright = "Copyright right infomation."
themesdir = "themes"
theme = "hugo_eiio"
Paginate=15 
MetaDataFormat = "toml"
PaginatePath="page"
pygmentsuseclasses = true
disqusShortname = "user id"
googleAnalytics='google analytics code'

hasCJKLanguage = true
preserveTaxonomyNames = false
disablePathToLower =false 
enableEmoji = true
enableInlineShortcodes = true
enableRobotsTXT = true

[taxonomies]
  category = "categories"
  tag = "tags"
  summaryLength = 250 # default 70
[params]
  hljsStyle="github" #code highlightjs css style . See [Style List](https://github.com/highlightjs/highlight.js/tree/master/src/styles "CSS Style list")

  showNextAndPrePost = false #Is Show Next and Previous Post Button
  description = "site description"
  keywords = "site keywords use seo"
  googleSiteVerification = "google site verification key"
  author = "your name"
  github ="github username"
  email="your email"
  twitter="your twitter name" 
  securityPolicy = false #disable https content security policy
  footerRight="Your tips content" #footer right content
  mainSections = ['page']
[sitemap]
  changefreq = "monthly"
  priority = 0.5
  filename = "sitemap.xml"

```
# Use post's thumbnail 


## Home thumbnail of post:

if you need in home page list display thumbnail of post,write head of post keywords,see below code👇:

```

+++
title = "Post Title"
categories = ["Categories"]
tags = ["tags"]
date = "write datetime"
draft = false
header_images="post home list thumbnail"
+++
..............
```

## Content thumbnail of post:

if you need in post content to display different thumbnail,see below code 👇

```
{{< figure  class="floatright|floatleft" src="your image path" alt="" >}}
```

# License
This theme is released under the [MIT License](https://github.com/leonhe/hugo_eiio/blob/master/LICENSE).

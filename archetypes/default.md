---
date: '{{ .Date }}'
draft: false
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
showToc: true
TocOpen: false
hideSummary: false
searchHidden: true
UseHugoToc: true
tags: ["tech"]
#cover:
#    image: "<image path/url>"
#    alt: "<alt text>"
#    caption: "<text>"
#    relative: false # when using page bundles set this to true
#    hidden: true # only hide on current single page
---
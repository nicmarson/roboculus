---
date        : {{ .Date }}
title       : "{{ replace .TranslationBaseName "-" " " | title }}"
description : "Our components are a collection of interface elements that can be reused across the Shopify system."
tags        : [ "React", "HTML", "CSS" ]
topics      : [ "Development", "React" ]
slug        : "react"
---

**Insert Lead paragraph here.**

<!--more-->

## New Cool Posts

{{ range first 10 ( where .Site.RegularPages "Type" "cool" ) }}
* {{ .Title }}
{{ end }}
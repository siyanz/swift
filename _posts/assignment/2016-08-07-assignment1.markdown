---
layout: post
title:  "Assignment 1"
date:   2016-08-07
dueDate: 2016-09-07 23:59:00 
categories: assignment
author: siyanz
---

This is a sample post to denote the features of Swift theme . The theme consists of various share plugins , feedburner support , sitemap generation etc. You can configure the blog in similar way you use a word press blog

<!-- more -->

**Basic**

Neque porro *quisquam* est, qui **dolorem** ipsum, quia ***dolor*** sit, amet, [consectetur](http://cjdns.info/), adipisci velit.

 * lorem
 * ipsum

1. dolor
2. sit


**Blockquote**

> They who can give up essential liberty to obtain a little temporary safety, deserve neither liberty nor safety.
> 
> _Benjamin Franklin_

**Code**

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

**Image**

![ThisIsADemoPhoto](http://media.vector4free.com/normal/flat-banner-vectors.jpg)

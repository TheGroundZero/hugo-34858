---
title: "Example - bundle"
author: Seq
type: posts
date: 2021-00-26
publishdate: 2021-00-26
lastmod: 2021-00-26
summary: Example for issue 34858 - bundle
comments: false
images:
- example-bundle.png
categories: ["Examples"]
tags: ["example","bundle"]
toc: true
toclevels: 4
draft: false
---

## Example of page bundle (NL)

This blog post is constructed as a page bundle.
The head tag (e.g. twitter tags) should refer to `/blog/1/01/example-bundle/example-bundle.png` but refers to `/example-bundle.png`.

```html
<meta name="twitter:image" content="http://localhost:1313/example-bundle.png">
```

{{< figure src="example-bundle.png" alt="Example of Page Bundle" position="center" caption="Example of page bundle" captionPosition="center" >}}

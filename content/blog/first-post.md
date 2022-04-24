---
title: My first blog post
description : Welcome to my first blog post using the content module
slug: first-post
img: blog-1.jpg
---


# My First Blog post

Why?

Because of the way nuxt works the $content property on the context has to be merged into the nuxt Context interface via declaration merging. Adding @nuxt/content to your types will import the types from the package and make typescript aware of the additions to the Context interface.
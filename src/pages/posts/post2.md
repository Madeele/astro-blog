---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: My second blog post!
publishDate: 07 Feb 2022
name: Magdalena Polakowska
description: Lalala this is my second blog post!
---

<Cool name={frontmatter.name} href="https://www.instagram.com/madeele_design/" client:load />

This is the text for my first blog post!
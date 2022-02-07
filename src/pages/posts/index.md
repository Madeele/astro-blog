---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: My first blog post!
publishDate: 07 Feb 2022
name: Magdalena Polakowska
description: Trying to make my first blog post!
---

<Cool name={frontmatter.name} href="https://www.instagram.com/madeele_design/" client:load />

This is the text for my first blog post!
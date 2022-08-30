---
title: My First Eleventy Site
layout: base.njk
---

## Lorem Ipsum

Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ducimus
nulla nihil, sequi deleniti exercitationem, officia, veritatis
recusandae doloribus debitis dolore laboriosam error expedita illum

{% for page in collections.pages %}

- [{{ page.data.title }}]({{ page.url }})
  {%-endfor %}

## Lorem Ipsum

Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed labore
similique molestiae saepe. Dignissimos ullam magnam vitae ad,
doloribus voluptas!

![cat of the day]({{ catpic }})

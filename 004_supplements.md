---
layout: default
title: Supplements
number: 4
---

# Supplements

## Maps

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Map of the German Confederation'" %}
{% include media.html pages=media %}



## Images

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Kaiserproklamation'" %}
{% include media.html pages=media %}

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1xQuV5EhFV3Frzm7SuxZJSq9i0Aa6XIlyKKJE1y-2MPQ&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

# Supplementary Videos/Audio Recordings

## Videos

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Video - von Habsburg Every Year'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Video - Brandenburg Every Year'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Video - TenMinutes'" %}
{% include media.html pages=media %}



## Audio

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Audio - FranzJosef'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Audio - Wilhelm II'" %}
{% include media.html pages=media %}

# Supplementary Websites

Wikipedia: [List of States in the HRE](https://en.wikipedia.org/wiki/List_of_states_in_the_Holy_Roman_Empire)

House of Habsburg: [The full timeline and family tree of the von Habsburg line](https://habsburg.org/family-history/extended-family-tree/?lang=en)

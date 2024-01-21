---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Arcana Mind
      image:
        filename: tarot-featured.jpg
      cta:
        label: '**Minting Now**'
        url: https://opensea.io/collection/tarotnfts-art/drop/
      cta_alt:
        label: Learn More
        url: /post/arcana-mind/
      text: |-
        Discover the groundbreaking Arcana Mind NFT collection, fusing Tarot with the power of AI.

        With 17,594 unique images, each NFT captures the essence of the Tarot like never before.

        Soon, you can be part of history and mint your own one-of-a-kind Arcana Mind NFT.

        <!--Custom spacing-->
        <div class="mb-3"></div>
    design:
      background:
        gradient_end: '#6a1b9a'
        gradient_start: '#282828'
        text_color_light: true
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

---

---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: iStock-1453719521.jpg
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "30+"
          description: |
            Publications
        - statistic: "450+"
          description: |
            Citations
        - statistic: "11"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
       I research in AI4Science and LLM -v-. 
    design:
      columns: '1'
  - block: markdown
    content:
      title: Recent News
      subtitle: ''
      text: |-
        <div style="font-size: 0.85em; line-height: 1.4;">
        2025 Jan: My paper on peptide sequencing with Non-autoregressive Transformer got accepted to Nature Communications
        </div>
    design:
      columns: '1'
---

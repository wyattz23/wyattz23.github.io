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
            Manuscripts
        - statistic: "460+"
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
        <div style="font-size: 0.85em; line-height: 1.6; color: #333;">
          <div style="margin-bottom: 12px;">
            <span style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 Sept:</span>
            <span style="color: #555;">2 papers were accepted to <strong style="font-weight: 700; color: #2c3e50; font-size: 1.05em;">NeurIPS</strong></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 July:</span>
            <span style="color: #555;">One paper got accepted in <em style="font-weight: 700; color: #2c3e50; font-style: italic; font-size: 1.05em;">Journal of Scheduling</em>, after 3 years of reviewing process</span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 April:</span>
            <span style="color: #555;">2 papers were accepted to <strong style="font-weight: 700; color: #2c3e50; font-size: 1.05em;">ICML</strong></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 March:</span>
            <span style="color: #555;">1 paper got accepted to <strong style="font-weight: 700; color: #2c3e50; font-size: 1.05em;">ACL</strong> main conference</span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div>
            <span style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 Jan:</span>
            <span style="color: #555;">My paper on peptide sequencing with Non-autoregressive Transformer got accepted to <em style="font-weight: 700; color: #2c3e50; font-style: italic; font-size: 1.05em;">Nature Communications</em></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
        </div>
    design:
      columns: '1'
---

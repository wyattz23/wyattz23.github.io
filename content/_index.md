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
        - statistic: "470+"
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
        <div class="news-container" style="font-size: 0.85em; line-height: 1.6;">
          <div style="margin-bottom: 12px;">
            <span class="news-date" style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 Sept:</span>
            <span class="news-content">2 papers were accepted to <strong class="news-highlight">NeurIPS</strong></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span class="news-date" style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 July:</span>
            <span class="news-content">One paper got accepted in <em class="news-journal">Journal of Scheduling</em>, after 3 years of reviewing process</span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span class="news-date" style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 April:</span>
            <span class="news-content">2 papers were accepted to <strong class="news-highlight">ICML</strong></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div style="margin-bottom: 12px;">
            <span class="news-date" style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 March:</span>
            <span class="news-content">1 paper got accepted to <strong class="news-highlight">ACL</strong> main conference</span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
          <div>
            <span class="news-date" style="font-weight: 600; color: #3498db; font-size: 0.95em; margin-right: 8px;">2025 Jan:</span>
            <span class="news-content">My paper on peptide sequencing with Non-autoregressive Transformer got accepted to <em class="news-journal">Nature Communications</em></span>
            <span style="margin-left: 6px;">🎉</span>
          </div>
        </div>
        <style>
          /* Light mode - black text (default) */
          .news-container {
            color: #000000;
          }
          .news-content {
            color: #000000;
          }
          .news-highlight {
            font-weight: 700;
            color: #e74c3c;
            font-size: 1.05em;
          }
          .news-journal {
            font-weight: 700;
            color: #27ae60;
            font-style: italic;
            font-size: 1.05em;
          }
          /* Explicit light mode support */
          @media (prefers-color-scheme: light) {
            .news-container {
              color: #000000 !important;
            }
            .news-content {
              color: #000000 !important;
            }
            .news-highlight {
              color: #e74c3c !important;
            }
            .news-journal {
              color: #27ae60 !important;
            }
          }
          /* Ensure light mode when not in dark mode */
          html:not(.dark) .news-container,
          html:not([data-theme="dark"]) .news-container,
          body:not(.dark) .news-container {
            color: #000000 !important;
          }
          html:not(.dark) .news-content,
          html:not([data-theme="dark"]) .news-content,
          body:not(.dark) .news-content {
            color: #000000 !important;
          }
          html:not(.dark) .news-highlight,
          html:not([data-theme="dark"]) .news-highlight,
          body:not(.dark) .news-highlight {
            color: #e74c3c !important;
          }
          html:not(.dark) .news-journal,
          html:not([data-theme="dark"]) .news-journal,
          body:not(.dark) .news-journal {
            color: #27ae60 !important;
          }
          /* Dark mode support - white text (MUST come last to override) */
          @media (prefers-color-scheme: dark) {
            .news-container {
              color: #ffffff !important;
            }
            .news-content {
              color: #ffffff !important;
            }
            .news-highlight {
              color: #ff6b6b !important;
            }
            .news-journal {
              color: #51cf66 !important;
            }
          }
          /* Hugo Blox dark mode class support - white text (MUST come last) */
          html.dark .news-container,
          html[data-theme="dark"] .news-container,
          .dark .news-container,
          [data-theme="dark"] .news-container,
          body.dark .news-container {
            color: #ffffff !important;
          }
          html.dark .news-content,
          html[data-theme="dark"] .news-content,
          .dark .news-content,
          [data-theme="dark"] .news-content,
          body.dark .news-content {
            color: #ffffff !important;
          }
          html.dark .news-highlight,
          html[data-theme="dark"] .news-highlight,
          .dark .news-highlight,
          [data-theme="dark"] .news-highlight,
          body.dark .news-highlight {
            color: #ff6b6b !important;
          }
          html.dark .news-journal,
          html[data-theme="dark"] .news-journal,
          .dark .news-journal,
          [data-theme="dark"] .news-journal,
          body.dark .news-journal {
            color: #51cf66 !important;
          }
        </style>
    design:
      columns: '1'
---

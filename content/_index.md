---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        #url: resume.pdf
      headings:
        about: ''
        #education: 'Work Experience'
        education: 'Experience'
        interests: ''
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: 'background.jpg'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I received my Ph.D. degree in ... Feel free to reach out via email if you'd like to collaborate or discuss research ideas. I am on job market 😃
        
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
        tag: "Publications"
      sort_by: weight
      sort_ascending: true
    design:
      view: citation
  - block: markdown
    id: awards
    content:
      title: Awards
      subtitle: ''
      text: |-
        - **PQG Travel Award** (2026)
        - **NSF Travel Award for the ICSA Applied Statistics Symposium** (2025)
        - **"Zhong Jiaqing" Award in Probability and Statistics** (2023)
        - **Outstanding Doctoral Dissertation** (2024)
        - **Outstanding Graduate of Beijing** (2024)
        - **Outstanding Graduate of Tsinghua University** (2024)
        - **President Scholarship** (Only awarded to 20 students) (2021)
        - **The 1st Prize "RONG" Scholarship** (2021)
        - **"BeiGene" Paper Award for Youth Scholars, Outstanding paper** (2020 & 2021)
    design:
      columns: '1'
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: software
    content:
      title: Software
      subtitle: ''
      text: |-
        <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(320px,1fr));gap:12px;">
          <div style="border:1px solid #d9d9df;border-radius:10px;padding:14px 18px;background:#fbfbfd;">
            <h4 style="margin:0 0 8px 0;font-size:1.05rem;color:#3b67df;">🖥️ WGS / WES</h4>
            <p style="margin:0 0 8px 0;color:#334155;">Rare-variant association tools for sequencing studies.</p>
            <div style="line-height:1.8;">
              <a href="https://github.com/shuangsong0110/GATE-STAAR" target="_blank" rel="noopener">GATE-STAAR</a> ·
              <a href="https://github.com/shuangsong0110/GATE-STAAR-RAP" target="_blank" rel="noopener">GATE-STAAR-RAP</a>
            </div>
          </div>

          <div style="border:1px solid #d9d9df;border-radius:10px;padding:14px 18px;background:#fbfbfd;">
            <h4 style="margin:0 0 8px 0;font-size:1.05rem;color:#3b67df;">🖥️ Heritability / Genetic Correlation</h4>
            <p style="margin:0 0 8px 0;color:#334155;">Methods for SNP heritability and participation-bias correction.</p>
            <div style="line-height:1.8;">
              <a href="https://github.com/shuangsong0110/LDER" target="_blank" rel="noopener">LDER</a> ·
              <a href="https://github.com/shuangsong0110/ParticipationBias" target="_blank" rel="noopener">ParticipationBias</a>
            </div>
          </div>

          <div style="border:1px solid #d9d9df;border-radius:10px;padding:14px 18px;background:#fbfbfd;">
            <h4 style="margin:0 0 8px 0;font-size:1.05rem;color:#3b67df;">🖥️ Polygenic Risk Prediction</h4>
            <p style="margin:0 0 8px 0;color:#334155;">Polygenic risk score modeling and Bayesian prediction tools.</p>
            <div style="line-height:1.8;">
              <a href="https://github.com/shuangsong0110/NeuPred" target="_blank" rel="noopener">NeuPred</a> ·
              <a href="https://github.com/shuangsong0110/EBPRS" target="_blank" rel="noopener">EBPRS</a>
            </div>
          </div>

          <div style="border:1px solid #d9d9df;border-radius:10px;padding:14px 18px;background:#fbfbfd;">
            <h4 style="margin:0 0 8px 0;font-size:1.05rem;color:#3b67df;">🖥️ Multiomics</h4>
            <p style="margin:0 0 8px 0;color:#334155;">Integrative analysis across transcriptome and omics modalities.</p>
            <div style="line-height:1.8;">
              <a href="https://github.com/shuangsong0110/MTWAS" target="_blank" rel="noopener">MTWAS</a> ·
              <a href="https://github.com/shuangsong0110/OWAS" target="_blank" rel="noopener">OWAS</a> ·
              <a href="https://github.com/shuangsong0110/OWASjoint" target="_blank" rel="noopener">OWASjoint</a>
            </div>
          </div>

          <div style="border:1px solid #d9d9df;border-radius:10px;padding:14px 18px;background:#fbfbfd;">
            <h4 style="margin:0 0 8px 0;font-size:1.05rem;color:#3b67df;">🖥️ Mendelian Randomization</h4>
            <p style="margin:0 0 8px 0;color:#334155;">Robust multivariable Mendelian randomization inference.</p>
            <div style="line-height:1.8;">
              <a href="https://github.com/shuangsong0110/MVMR-PRESS" target="_blank" rel="noopener">MVMR-PRESS</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: service
    content:
      title: Service
      subtitle: ''
      text: |-
        **Reviewer:**
        - *Nature Communications*
        - *The American Journal of Human Genetics*
        - *npj Digital Medicine*
        - *IEEE/ACM Transactions on Computational Biology and Bioinformatics*
        - *BMC Bioinformatics*
        - *BMC Medicine*
        - *Scientific Reports*

        **Teaching:**
        - Teaching Assistant for Probability Theory (2021)
        - Teaching Assistant for the Science and Art of Data Analysis (2021)
        - Teaching Assistant for Mathematics History (2020 & 2021)
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

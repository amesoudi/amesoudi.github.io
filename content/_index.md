---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-22
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
        url: uploads/alex_mesoudi_cv.pdf
    # design:
      # css_class: dark
      # background:
      #  color: black
      #  image:
          # Add your image background to `assets/media/`.
      #    filename: ''
      #    filters:
      #      brightness: 1.0
      #    size: cover
       #   position: center
       #   parallax: false
#  - block: markdown
#    content:
#      title: '📚 My Research'
#      subtitle: ''
#      text: |-
#        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind.  #  I blog about machine learning, deep learning, and moonshots.
#    design:
#      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        <h4>1. Cultural Evolution</h4>
        <p><img src="/uploads/book_cover.png" alt="Cultural Evolution book cover" style="width:200px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:right;">The human species has an extraordinary reliance on culture, i.e. the vast body of beliefs, knowledge and skills that we acquire from other individuals via social learning. While other species adapt to their environments primarily via genetic evolution, we adapt via cultural evolution. I am interested in how this process of cultural evolution works, its similarities and differences to genetic evolution, and how traditional social science findings and topics can be studied within an evolutionary framework.</p>
        <h5>Representative publications:</h5>
        [Mesoudi (2017) Pursuing Darwin's curious parallel: Prospects for a science of cultural evolution. _Proceedings of the National Academy of Sciences_ 114, 7853–7860.]({{< ref "/publication/mesoudi-pursuing-2017/index.md" >}})
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 6
    design:
      view: citation
  - block: markdown
    id: tutorials
    content:
      title: 'Simulation models of cultural evolution in R'
      subtitle: ''
      text: |-
        <img src="/uploads/sim.png" alt="Screenshots of cultural evolution simulations"> <a href="https://github.com/amesoudi/cultural_evolution_ABM_tutorial">This tutorial</a> shows how to create very simple simulation or agent-based models of cultural evolution in R. It uses the RStudio notebook or RMarkdown (.Rmd) format, allowing you to execute code as you read the explanatory text. Each model is contained in a separate RMarkdown file which you can open in RStudio. Currently these are:

        * Model 1: Unbiased transmission
        * Model 2: Unbiased and biased mutation
        * Model 3: Biased transmission (direct/content bias)
        * Model 4: Biased transmission (indirect bias)
        * Model 5: Biased transmission (conformist bias)
        * Model 6: Vertical and horizontal transmission
        * Model 7: Migration
        * Model 8: Blending inheritance
        * Model 9: Demography and cultural gain/loss
        * Model 10: Polarization
        * Model 11: Cultural group selection
        * Model 12: Historical dynamics
        * Model 13: Social contagion
        * Model 14: Social networks
        * Model 15: Opinion formation
        * Model 16: Bayesian iterated learning
        * Model 17: Reinforcement learning
        * Model 18: Evolution of social learning
        * Model 19: Evolution of social learning strategies
        
        The tutorial is freely available <a href="https://github.com/amesoudi/cultural_evolution_ABM_tutorial">in this github repository</a>. An online version which contains the compiled models with outputs can be found <a href="https://bookdown.org/amesoudi/ABMtutorial_bookdown/">on this bookdown site</a>.
    design:
      columns: '1'
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
#  - block: cta-card
#    demo: true # Only display this section in the Hugo Blox Builder demo site
#    content:
#      title: 👉 Build your own academic website like this
#      text: |-
#        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
#
#        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>
#
#        Easily build anything with blocks - no-code required!
#        
#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---

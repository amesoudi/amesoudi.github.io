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
      #      ightness: 1.0
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
  - block: markdown
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        <h4>1. Cultural Evolution</h4>
        <p style="font-size:17px"><img src="/uploads/book_cover.png" alt="Cultural Evolution book cover" style="width:200px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:right;">The human species has an extraordinary reliance on culture, i.e. the vast body of beliefs, knowledge and skills that we acquire from other individuals via social learning. While other species adapt to their environments primarily via genetic evolution, we adapt via cultural evolution. I am interested in how this process of cultural evolution works, its similarities and differences to genetic evolution, and how traditional social science findings and topics can be studied within an evolutionary framework.</p>
        <h4>Representative publications:</h4>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-pursuing-2017/" style="font-size: 15px">Mesoudi (2017) Pursuing Darwin's curious parallel: Prospects for a science of cultural evolution. Proceedings of the National Academy of Sciences 114, 7853–7860.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-cultural-2011/" style="font-size: 15px">Mesoudi (2011) Cultural evolution: How Darwinian theory can explain human culture and synthesize the social sciences. University of Chicago Press.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-towards-2006/" style="font-size: 15px">Mesoudi, Whiten and Laland (2006) Towards a unified science of cultural evolution. Behavioral and Brain Sciences 29, 329–383.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-is-2004/" style="font-size: 15px">Mesoudi, Whiten and Laland (2004) Is human cultural evolution Darwinian? Evidence reviewed from the perspective of The Origin of Species. Evolution 58, 1–11.</a></p><br>
        <h4>2. Social Learning Experiments</h4>
        <p style="font-size:17px"><img src="/uploads/arrowhead_bilateral.jpg" alt="Arrowhead task screenshot" style="width:350px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:right;">Learning from others, aka 'social learning', lies at the heart of human culture. I have run lab experiments examining how people learn from one another, who they learn from, when they learn from others rather than alone, and what they learn. Some studies use the 'transmission chain method', where stories or task solutions are passed along linear chains of participants like the game 'Telephone'. These have found, for example, that information about social relationships and interactions is transmitted better than non-social information, and that causal understanding is not necessary for improvements in technologies over time. Other studies look at how people within small groups learn from one another over time. Often these experiments look at technological change, getting participants to design arrowheads, handaxes or other objects reflecting real-life human technology. These studies have found that people prefer to learn from successful others, but often copy others less than they should do; and that people copy prestigious people only when direct success information is unavailable.</p>
        <h4>Representative publications:</h4>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/brand-emergence-2020/" style="font-size: 15px">Brand, Heap, Morgan & Mesoudi (2020). The emergence and adaptive use of prestige in an online social learning task. Scientific Reports 10, 12095.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/derex-causal-2019/" style="font-size: 15px">Derex, Bonnefon, Boyd and Mesoudi (2019) Causal understanding is not necessary for the improvement of culturally evolving technology. Nature Human Behaviour 3, 446–452.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-experimental-2011/" style="font-size: 15px">Mesoudi (2011) An experimental comparison of human social learning strategies: payoff-biased social learning is adaptive but underused. Evolution and Human Behavior 32, 334–342.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-bias-2006/" style="font-size: 15px">Mesoudi, Whiten and Dunbar (2006) A bias for social information in human cultural transmission. British Journal of Psychology 97, 405–423.</a></p><br>
        <h4>3. Models of Cultural Evolution</h4>
        <p style="font-size:17px"><img src="/uploads/kempe_model.png" alt="Kempe et al. model" style="width:350px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:right;">I have used theoretical models, primarily agent-based simulations, to explore how different learning dynamics - who copies what, from whom and when - might generate large-scale patterns of cultural evolution. Previous models have looked at beliefs in partible paternity (where children have more than one biological 'father'), copycat suicide, and how the costs of acquiring ever-accumulating knowledge slows down innovation in cumulative cultural evolution.</p>
        <h4>Representative publications:</h4>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/kempe-cultural-2014/" style="font-size: 15px">Kempe, Lycett and Mesoudi (2014) From cultural traditions to cumulative culture: Parameterizing the differences between human and nonhuman culture. Journal of Theoretical Biology 359, 29–36.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-variable-2011/" style="font-size: 15px">Mesoudi (2011) Variable cultural acquisition costs constrain cumulative cultural evolution. PLOS ONE 6, e18239.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-cultural-2009/" style="font-size: 15px">Mesoudi (2009) The cultural dynamics of copycat suicide. PLOS ONE 4, e7252.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-culturally-2007/" style="font-size: 15px">Mesoudi and Laland (2007) Culturally transmitted paternity beliefs and the evolution of human mating behaviour. Proceedings of the Royal Society B 274, 1273–1278.</a></p><br>
        <h4>4. Migration, Acculturation and Cross-Cultural Variation</h4>
        <p style="font-size:17px"><img src="/uploads/acculturation.png" alt="Acculturation of attribution style" style="width:350px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:right;">Ever since our species first evolved in Africa, migration has been a constant fixture of <i>Homo sapiens</i>. 'Acculturation' describes the psychological and behavioural changes that occur as a result of migration. I have studied how acculturation affects the psychological characteristics of first and second generation British Bangladeshi migrants in London, and constructed theoretical models showing how acculturation and migration interact to shape cultural diversity over time. Lab experiments have mapped cross-cultural variation in social learning, showing higher rates of social learning in mainland China than in the West.</p>
        <h4>Representative publications:</h4>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/kunst-decoding-2024/" style="font-size: 15px">Kunst & Mesoudi (2024). Decoding the dynamics of cultural change: A cultural evolution approach to the psychology of acculturation. Personality and Social Psychology Review</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-migration-2018/" style="font-size: 15px">Mesoudi (2018) Migration, acculturation, and the maintenance of between-group cultural variation. PLOS ONE 13, e0205573.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-how-2016/" style="font-size: 15px">Mesoudi, Magid and Hussain (2016) How do people become W.E.I.R.D.? Migration reveals the cultural transmission mechanisms underlying variation in psychological processes. PLOS ONE 11, e0147162.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-higher-2015/" style="font-size: 15px">Mesoudi, Chang, Murray and Lu (2015) Higher frequency of social learning in China than in the West shows cultural variation in the dynamics of cultural evolution. Proceedings of the Royal Society B 282, 20142209.</a></p><br>
        <h4>5. Big Cultural Data</h4>
        <p style="font-size:17px"><img src="/uploads/formations.png" alt="Football formations" style="width:350px;margin-left:20px;margin-right:20px;margin-left:20px;margin-bottom:10px;float:right;">The digital age has yielded big cultural datasets that can be used to quantitatively analyse patterns of real-life cultural evolution. Recent projects have analysed and explained large-scale, long-term change in pop music lyrics, football tactics and tweets related to the Netflix documentary Our Planet.</p>
        <h4>Representative publications:</h4>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/acerbi-sentiment-2023/" style="font-size: 15px">Acerbi, Burns, Cabuk, Kryczka, Trapp, Valletta and Mesoudi (2023) Sentiment analysis of the Twitter response to Netflix's Our Planet documentary. Conservation Biology 37(4), e14060.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/mesoudi-cultural-2020/" style="font-size: 15px">Mesoudi (2020) Cultural evolution of football tactics: strategic social learning in managers' choice of formation. Evolutionary Human Sciences 2, e25.</a></p>
        <p style="line-height:20px;"><a href="https://www.alexmesoudi.com/publication/brand-cultural-2019/" style="font-size: 15px">Brand, Acerbi and Mesoudi (2019) Cultural evolution of emotional expression in 50 years of song lyrics. Evolutionary Human Sciences 1, e11.</a></p>
    design:
      columns: '1'
  - block: collection
    id: books
    content:
      title: Selected Books
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
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
    id: lab
    content:
      title: 'Lab members'
      subtitle: ''
      text: |-
        <p style="font-size:18px"><b>Current lab members</b></p>
        <ul style="font-size:17px">
          <li><a href="http://andonisergiou.com/">Andoni Sergiou</a>, PhD student, 2020-present</li>
          <li><a href="https://uk.linkedin.com/in/ishaan-sinha-02785b193">Ishaan Sinha</a>, PhD student, 2023-present</li>
        </ul>
        <p style="font-size:18px"><b>Former postdocs</b></p>
        <ul style="font-size:17px">
          <li><a href="https://angelvjimenez.com/">Dr Angel V. Jimenez</a>, CES/Templeton funded postdoc, 2023-2024</li>
          <li><a href="https://lottybrand.wordpress.com/">Dr Charlotte Brand</a>, Leverhulme Trust funded Postdoctoral Research Associate, 2017-2020</li>
          <li><a href="https://maximederex.weebly.com/">Dr Maxime Derex</a>, Marie Curie Fellow, 2017-2019 (now holds CNRS position at IAST in Toulouse)</li>
          <li><a href="https://www.anthro.ox.ac.uk/people/dr-kesson-magid">Dr Kesson Magid</a>, ESRC funded postdoc, 2013-2016 (now at Department of Anthropology, Oxford)</li>
          <li><a href="http://www.sps.ed.ac.uk/staff/social_anthropology/delwar_hussain">Dr Delwar Hussain</a>, ESRC funded postdoc, 2013-2014 (now at Department of Anthropology, University of Edinburgh)</li>
          <li>Dr Keelin Murray, ESRC funded postdoc, 2013-2014</li>
        </ul>
        <p style="font-size:18px"><b>Former PhD students</b></p>
        <ul style="font-size:17px">
          <li><a href="https://biosciences.exeter.ac.uk/staff/profile/index.php?web_id=Dugald_Foster">Dr Dugald Foster</a>, University of Exeter, 2019-2023; passed with no corrections</li>
          <li><a href="https://angelvjimenez.com/">Dr Angel V. Jimenez</a>, University of Exeter, 2017-2020; passed with minor corrections</li>
          <li><a href="https://alicejeanwilliams.wordpress.com/">Dr Alice Williams</a>, University of Exeter, 2018-2019 (took over as main supervisor); passed with minor corrections</li>
          <li><a href="https://www.sjc.edu/academic-programs/faculty/annapolis">Dr Marius Kempe</a>, Queen Mary / Durham University, 2010-2013; passed with minor corrections</li>
          <li>Dr Vera Sarkol, Queen Mary, 2010-2014; passed with minor corrections</li>
        </ul>
        <p style="font-size:18px"><b>Former visiting PhD/MSc students and postdocs</b></p>
        <ul style="font-size:17px">
          <li><a href="https://sites.google.com/site/watarutoyokawa/home">Dr Wataru Toyokawa</a>, British Academy Visiting Fellow, October-December 2023</li>
          <li>Jérémy Perez, visiting Masters student from Télécom Paris, France, June-August 2021</li>
          <li>André Luiz Borba do Nascimento, visiting PhD student from Federal Rural University of Pernambuco, Brazil, March-August 2017</li>
        </ul>
    design:
      columns: '1'
  - block: markdown
    id: tutorials
    content:
      title: 'Simulation models of cultural evolution in R'
      subtitle: ''
      text: |-
        <p style="font-size:17px"><img src="/uploads/sim.png" alt="Screenshots of cultural evolution simulations"> <a href="https://github.com/amesoudi/cultural_evolution_ABM_tutorial">This tutorial</a> shows how to create very simple simulation or agent-based models of cultural evolution in R. It uses the RStudio notebook or RMarkdown (.Rmd) format, allowing you to execute code as you read the explanatory text. Each model is contained in a separate RMarkdown file which you can open in RStudio. Currently these are:</p>
        
        <ul style="font-size:17px">
          <li>Model 1: Unbiased transmission</li>
          <li>Model 2: Unbiased and biased mutation</li>
          <li>Model 3: Biased transmission (direct/content bias)</li>
          <li>Model 4: Biased transmission (indirect bias)</li>
          <li>Model 5: Biased transmission (conformist bias)</li>
          <li>Model 6: Vertical and horizontal transmission</li>
          <li>Model 7: Migration</li>
          <li>Model 8: Blending inheritance</li>
          <li>Model 9: Demography and cultural gain/loss</li>
          <li>Model 10: Polarization</li>
          <li>Model 11: Cultural group selection</li>
          <li>Model 12: Historical dynamics</li>
          <li>Model 13: Social contagion</li>
          <li>Model 14: Social networks</li>
          <li>Model 15: Opinion formation</li>
          <li>Model 16: Bayesian iterated learning</li>
          <li>Model 17: Reinforcement learning</li>
          <li>Model 18: Evolution of social learning</li>
          <li>Model 19: Evolution of social learning strategies</li>
        </ul>
        
        <p style="font-size:17px">The tutorial is freely available <a href="https://github.com/amesoudi/cultural_evolution_ABM_tutorial">in this github repository</a>. An online version which contains the compiled models with outputs can be found <a href="https://bookdown.org/amesoudi/ABMtutorial_bookdown/">on this bookdown site</a>.</p>
    design:
      columns: '1'
  - block: markdown
    id: talks
    content:
      title: 'Talks'
      subtitle: ''
      text: |-
        <p style="font-size:17px"><b>Archaeology Within a Unified Science of Cultural Evolution</b>. Part of the Garrod Research seminar series of the McDonald Institute for Archaeological Research, University of Cambridge, 11 January 2024.</p>
        <p align="center"><iframe width="390" height="221" src="https://www.youtube.com/embed/pyves6t84zk?si=R6yUnf2sdrC8ZIzW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p><br>
        <p style="font-size:17px"><b>A Brief History of Cultural Evolution</b>. Keynote presentation at the Culture Conference 2021: Evolutionary Approaches to Culture, 7th June 2021.</p>
        <p align="center"><iframe width="390" height="221" src="https://www.youtube.com/embed/LPCJw7pT8-g?si=8ErdQJn7aW7UfwCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p><br>
        <p style="font-size:17px"><b>Darwin's Curious Parallel: Towards a Unified Science of Cultural Evolution</b>. Presentation at the National Academy of Sciences Arthur M. Sackler Colloquium on the Extension of Biology Through Culture held at the Beckman Center in Irvine, CA on November 15-16, 2016, organized by Marcus Feldman, Francisco J. Ayala, Andrew Whiten and Kevin Laland.</p>
        <p align="center"><iframe width="390" height="221" src="https://www.youtube.com/embed/8odzOGK-8hE?si=d2BuloQG0Tg6kp8K" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p><br>
        <p style="font-size:17px"><b>Towards A Science Of Culture Within A Darwinian Evolutionary Framework</b>. Moderator: Prof. Itamar Even-Zohar. Tel-Aviv, Israel. 2nd June 2015</p>
        <p align="center"><iframe width="390" height="221" src="https://www.youtube.com/embed/yT32gKqQEFU?si=S4eJMtJDxY6m7in5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
    design:
      columns: '1'
  - block: markdown
    id: media
    content:
      title: 'Media / podcasts'
      subtitle: ''
      text: |-
        <a href="http://bigpicturescience.org/episodes/post-social-media"><img src="/uploads/bigpicturescience-website-logo.png" alt="Big Picture Science Podcast" style="width:150px;height:150px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="http://bigpicturescience.org/episodes/post-social-media"><p style="font-size:18px"><b>The Big Picture Science Podcast</b></p></a>
        <p style="font-size:17px">Contributor to the episode Post Social Media. 3 June 2024.</p>
        <br><br><br>
        <a href="https://www.youtube.com/watch?v=UwYzy-F0LP0"><img src="/uploads/unsupervisedlearning.png" alt="Unsupervised Learning Podcast" style="width:150px;height:150px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="https://www.youtube.com/watch?v=UwYzy-F0LP0"><p style="font-size:18px"><b>Unsupervised Learning podcast</b></p></a>
        <p style="font-size:17px">In conversation with Razib Khan. 23 Oct 2022.</p>
        <br><br><br>
        <a href="https://thisviewoflife.libsyn.com/cultural-evolution-with-alex-mesoudi"><img src="/uploads/thisviewoflife.png" alt="This View of Life" style="width:150px;height:150px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="https://thisviewoflife.libsyn.com/cultural-evolution-with-alex-mesoudi"><p style="font-size:18px"><b>This View of Life podcast</b></p></a>
        <p style="font-size:17px">Episode entitled "Cultural Evolution with Alex Mesoudi", hosted by David Sloan Wilson. 11 Sep 2020.</p>
        <br><br><br>
        <a href="https://www.thedissenter.net/podcast/228-alex-mesoudi-studying-cultural-evolution-migration-and-transmission/"><img src="/uploads/thedissenter.jpg" alt="The Dissenter" style="width:150px;height:150px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="https://www.thedissenter.net/podcast/228-alex-mesoudi-studying-cultural-evolution-migration-and-transmission/"><p style="font-size:18px"><b>The Dissenter podcast</b></p></a>
        <p style="font-size:17px">Episode #228 Alex Mesoudi: Studying Cultural Evolution, Migration, And Transmission. 12 Sep 2019.</p>
        <br><br><br>
        <a href="https://www.bbc.co.uk/programmes/b07jysds"><img src="/uploads/radio4.jpg" alt="BBC Radio 4" style="width:150px;height:100px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="https://www.bbc.co.uk/programmes/b07jysds"><p style="font-size:18px"><b>The Human Zoo</b></p></a>
        <p style="font-size:17px">Contributor, Series 8 Episode 4: Democracy and the Wisdom of the Crowds. 12 July 2016.</p>
        <br><br><br>
        <a href="https://blogs.lse.ac.uk/theforum/darwinismsocialsciences/"><img src="/uploads/theforum.jpg" alt="The Forum" style="width:150px;height:150px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="https://blogs.lse.ac.uk/theforum/darwinismsocialsciences/"><p style="font-size:18px"><b>The Forum Debate: Darwinism and the Social Sciences</b></p></a>
        <p style="font-size:17px">Panellist. Organised by the Forum for European Philosophy, London School of Economics. 29 Feb 2016.</p>
        <br><br><br>
        <a href="http://america.aljazeera.com/articles/2016/2/24/do-different-generations-of-immigrants-think-differently.html"><img src="/uploads/Al_Jazeera_America_Logo.png" alt="Al Jazeera America" style="width:150px;height:167px;margin-left:20px;margin-right:20px;margin-bottom:10px;float:left;"></a>
        <a href="http://america.aljazeera.com/articles/2016/2/24/do-different-generations-of-immigrants-think-differently.html"><p style="font-size:18px"><b>Al Jazeera America: Do different generations of immigrants think differently?</b></p></a>
        <p style="font-size:17px">Feature/interview on my cross-cultural thinking styles project by novelist Ned Beauman. 24 Feb 2016.</p>
    design:
      columns: '1'
#  - block: collection
#    id: talks
#    content:
#      title: Talks
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
#        From landing pages, second ains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---

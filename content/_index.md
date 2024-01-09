---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Network Analysis for Organic Chemistry
        content: Analyzing large chemical reaction networks and optimizing the selection of reaction pathways are the most resource efficient to synthesize a library of molecules
        align: left
        fontsize: 10
        background:
          image:
            filename: slider1.jpeg
            filters:
              brightness: 0.7
          position: right
          color: '#661'
      - title: Polymer Reaction Engineering and Process Optimization
        content: Combine optimization algorithms and simulation models to designing reaction recipe for desired polymer properties
        align: left
        background:
          image:
            filename: slider2.jpeg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      # - title: World-Class Semiconductor Lab
      #   url: 'https://sled.eecs.umich.edu/'
      #   content: 'Just opened last month!'
      #   align: right
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
          
        # link:
          # icon: graduation-cap
          # icon_pack: fas
          # text: Join Us
          # url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      slide_weight: '800px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000

  - block: hero
    content:
      title: |
        <h1 style="font-size: 24px;">Welcome to the Research Group of Hanyu Gao</h1>
      image:
        filename: welcome.jpg
      text: |
        <p style="font-size:16px;"> Modeling techniques have played an important role in chemical reaction and process engineering in multiple aspects. For example, microkinetic modeling provides ways of exploring complex reaction systems for which experimental measurements are challenging; optimization algorithms can be used to guide efficient design of experiments and improvement of processes. More recently, advances in data science and machine learning have also demonstrated their strength in elucidating complicated patterns from molecular structures and reaction systems. Although they have already been powerful individually, the synergies between these modeling techniques would provide even more benefits. </p>

        <p style="font-size:16px;"> Our group focuses on developing and applying both theoretical and data-driven models to solve problems in chemistry and chemical engineering, in order to facilitate chemical discovery and process development. </p>
        <p style="font-size:16px;"></p>
        <p style="font-size:16px;"></p>
        <p style="font-size:20px;"><a href="./research/" style="text-decoration: none;">Read more →</a></p>
      # cta:
      #   label: Read more →
      #   url: ./people/
      #   icon: sparkles
      #   icon_pak: fas
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: list
  #     columns: '1'
  
  - block: markdown
    content:
      title: Latest News
      text: |
        - <p style="font-size:20px;"><strong>[Dec. 2023]</strong> Congratulations to Haifan on the acceptance of <a href="https://doi.org/10.1021/acsengineeringau.3c00056">Using Active Learning for the Computational Design of Polymer Molecular Weight Distributions</a> by ACS Engineering, and to Puqing for <a href="https://doi.org/10.1016/j.giant.2023.100226">Systematic Discovery and Feature Analysis of Intertwined Symmetric Protein Motifs for Topology Engineering</a> being accepted by Giant.</p>
        - <p style="font-size:20px;"><strong>[Oct. 2023]</strong> The paper, Machine learning and molecular fingerprint screening of high-performance 2D/3D MOF membranes for Kr/Xe separation, is accepted by  Chemical Engineering Science.</p>
        - <p style="font-size:20px;"><strong>[Sep. 2023]</strong> Thrilled to welcome Haifan Zhou, Yufan Chen, and Yuxuan Zhang as the newest PhD students in our lab, with special congratulations to Haifan for receiving the Hong Kong PhD Fellowship Scheme! </p>
        - <p style="font-size:20px;"><strong>[Jul. 2023]</strong> Congratulations to Yue Fang on the acceptance of their paper, <a href="https://doi.org/10.1016/j.apsusc.2023.157942">Effect of SiO2 Nano-Interphase on the Water Absorption Mechanism of Natural Fiber Reinforced Composites: A Multi-Scale Study</a>, by Applied Surface Science!</p>
        - <p style="font-size:20px;"><strong>[Jun. 2023]</strong> The paper, <a href="https://doi.org/10.1016/j.ces.2023.119031"> Machine learning and molecular fingerprint screening of high-performance 2D/3D MOF membranes for Kr/Xe separation</a>, is accepted by  Chemical Engineering Science.</p>
        - <p style="font-size:20px;"><strong>[Jan. 2023]</strong> Delighted to welcome Fenghao Hong as a new MPhil student in our lab!</p>
        - <p style="font-size:20px;"><strong>[Dec. 2022]</strong> Delighted to announce Min Hu joining our lab as a Postdoc!</p>
        - <p style="font-size:20px;"><strong>[Sep. 2022]</strong> Excited to welcome Puqing Deng as our latest PhD student and congratulate him on receiving the HKUST Redbird PhD Scholarship!</p>
        - <p style="font-size:20px;"><strong>[Jun. 2022]</strong> The paper, <a href="https://pubs.rsc.org/en/content/articlelanding/2022/ta/d2ta02039d">Machine learning for design principles for single atom catalysts towards electrochemical reactions</a>, is accepted by  Journal of Materials Chemistry.</p>
        - <p style="font-size:20px;"><strong>[Sep. 2021]</strong> Welcome Yue Fang as the newest member of our research group!</p>
        - <p style="font-size:20px;"><strong>[Jan. 2021]</strong> The paper, <a href="https://pubs.acs.org/doi/10.1021/acs.jcim.0c01032">Direct Optimization across Computer-Generated Reaction Networks Balances Materials Use and Feasibility of Synthesis Plans for Molecule Libraries</a>, is accepted by Journal of Chemical Information and Modeling.</p>

        {{% cta cta_link="post" cta_text="View all posts →" %}}
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text: Innovations in chemistry have been a strong propellent to solving important challenges in energy, environment and health. The lifecycle of chemical innovation includes molecular discovery, reaction engineering, and process design and optimization. Computational modeling has played an important role in this process, but challenges still exist in different aspects. First, the scope and complexity of the molecules and chemistry are rapidly increasing. Efficient and rational exploration of the chemical space is desired in order to maximize the likelihood of success. 
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
banner:
  caption: ''
  image: ''
---
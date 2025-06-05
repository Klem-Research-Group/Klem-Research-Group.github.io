---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Klem Research Group
      image:
        filename: icon.png
      text: |
        <br>
        The Klem Research Group at LSU develops integrative computational models to understand and exploit enzyme function. We combine quantum mechanics, molecular dynamics, and machine learning to address challenges in medicine and sustainability.

  - block: slider
    content:
      slides:
        - title: '<span style="color: #000000;">Computational Tools for Enzyme Modeling</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/qmzyme.png" alt="QMzyme and tools" style="width: 30%; margin: 1em auto;">
            </div>
            <br>
            We build community-focused infrastructure such as <a href="https://qmzyme.readthedocs.io/en/latest/" target="_blank"><strong>QMzyme</strong></a> to automate quantum mechanical enzyme modeling. Our work integrates high-fidelity QM/MM and MD workflows to uncover catalytic mechanisms, electrostatic features, and structural determinants of activity in systems like β-lactamases.
          align: center
          background:
            color: "#e0e0e0"

        - title: '<span style="color: #000000;">Automation & Machine Learning for Biocatalyst Design</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/research/streamlined_biocatalyst_design.png" alt="Biocatalyst ML" style="width: 30%; margin: 1em auto;">
            </div>
            <br>
            We streamline enzyme engineering using hybrid workflows that combine QM/MM simulations with machine learning-guided predictions. Our models help identify reactive conformations, prioritize mutations, and accelerate optimization campaigns for novel biocatalysts.
          align: center
          background:
            color: "#e0e0e0"

        - title: '<span style="color: #000000;">Multienzyme Systems for Plastic Degradation</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/research/PET_proposal_horizontal.png" alt="Multienzyme PETase" style="width: 100%; margin: 1em auto;">
            </div>
            <br>
            We design and model multienzyme systems for PET plastic degradation, uncovering catalytic mechanisms and structural dynamics to guide the engineering of efficient depolymerization pathways. Our work contributes to sustainable biocatalysis and plastic recycling innovation.
          align: center
          background:
            color: "#e0e0e0"
    design:
      slide_height: ''
      is_fullscreen: true
      loop: true
      interval: 8000

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: true
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: list
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---


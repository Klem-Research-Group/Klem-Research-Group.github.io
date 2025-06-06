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
        The Klem Research Group at LSU develops integrative computational models to understand and exploit enzyme function. We combine quantum mechanics, molecular dynamics, and machine learning to investigate catalytic mechanisms, engineer biocatalysts, and design novel enzyme systems. Our work bridges fundamental theory and real-world application, addressing pressing challenges in medicine, biotechnology, and sustainable chemistry.

  - block: slider
    content:
      slides:
        - title: '<span class="slider-title">Computational Tools for Enzyme Modeling</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/qmzyme.png" alt="QMzyme and tools" style="width: 30%; margin: 1em auto;">
            </div>
            <br>
            We build community-focused infrastructure such as <a href="https://qmzyme.readthedocs.io/en/latest/" target="_blank"><strong>QMzyme</strong></a> to automate quantum mechanical enzyme modeling. Our work integrates high-fidelity QM/MM and MD workflows to uncover catalytic mechanisms, electrostatic features, and structural determinants of activity in systems like β-lactamases.
          align: center
          background:
            color: "#E0DBF0"

        - title: '<span class="slider-title">Automation & Machine Learning for Biocatalyst Design</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/research/streamlined_biocatalyst_design.png" alt="Biocatalyst ML" style="width: 30%; margin: 1em auto;">
            </div>
            <br>
            We streamline enzyme engineering using hybrid workflows that combine QM/MM simulations with machine learning-guided predictions. Our models help identify reactive conformations, prioritize mutations, and accelerate optimization campaigns for novel biocatalysts.
          align: center
          background:
            color: "#E0DBF0"
        - title: '<span class="slider-title">Multienzyme Systems for Plastic Degradation</span>'
          content: >
            <div style="text-align: center;">
              <img src="/uploads/research/PET_proposal_horizontal.png" alt="Multienzyme PETase" style="width: 100%; margin: 1em auto;">
            </div>
            <br>
            We design and model multienzyme systems for PET plastic degradation, uncovering catalytic mechanisms and structural dynamics to guide the engineering of efficient depolymerization pathways. Our work contributes to sustainable biocatalysis and plastic recycling innovation.
          align: center
          background:
            color: "#E0DBF0"
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
      title: Get to Know Us
      subtitle: Learn about the people behind the science
      text: |
        We're a collaborative, curious, and growing research group dedicated to pushing the boundaries of computational enzymology. From postdocs to undergrads, each member contributes unique perspectives and strengths to our work.

        {{% cta cta_link="/people/" cta_text="Meet the team →" color="#E0DBF0" %}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      background:
        color: "#E0DBF0"

---


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
        url: ivanchou/uploads/resumeeng.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Research Interests'
      subtitle: ''
      text: |-
        The research primarily focuses on the field of natural resource management and environmental economics, particularly the sustainable utilization of forest resources and the mechanisms of ecological protection policies. It emphasizes the implementation of China's forest tenure reform and its impact on forest ecosystem quality, forest carbon sequestration, and regional economic development. By applying advanced big data analysis and machine learning models, the research aims to reveal the long-term ecological and economic effects of policy reforms from multiple perspectives, providing innovative theoretical frameworks and empirical evidence for global environmental governance.
        
        Additionally, the research addresses the heterogeneous effects of policies across different regions and levels of economic development. Through studies on the clarification of natural resource property rights and the improvement of management efficiency, it proposes practical pathways for promoting sustainable forest management and addressing climate change. The goal is to provide theoretical support and practical references for the efficient management of global natural resources and environmental governance, advancing frontier research for academia and policymakers in addressing environmental challenges.
        
        The research includes:
        - Utilizing remote sensing technology and Geographic Information Systems (GIS) to assess the health status and carbon sequestration capacity of forest ecosystems.
        - Developing and applying machine learning algorithms to predict the long-term impacts of forest resource management policies.
        - Integrating socio-economic data and environmental data to construct comprehensive evaluation models, analyzing the multifaceted effects of policy implementation.
        - Exploring adaptive and resilient strategies for forest resource management policies in the context of climate change.
        
        Through these studies, the research aims to provide scientific basis and policy recommendations for global environmental governance and sustainable development, promoting academic progress and practical innovation in the field of natural resource management.
        
        Please reach out to collaborate 😃

    design:
      columns: '1'
  
---

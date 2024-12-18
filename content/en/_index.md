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
        My research focuses on resource economics and environmental management, particularly the sustainable use of forest resources and the mechanisms of ecological protection policies. I explore the implementation of China's forest tenure reform and its impact on forest ecosystem quality, forest carbon sequestration, and regional economic development, with a focus on how property rights reforms optimize resource allocation and enhance ecological benefits. By combining big data analysis and spatial econometric models, I reveal the long-term ecological and economic effects of policy reforms from multiple perspectives.

        Additionally, my research examines the heterogeneous effects of policies across different regions and levels of economic development. Through studies on the clarification of natural resource property rights and the improvement of management efficiency, I propose practical pathways for promoting sustainable forest management and addressing climate change. The goal is to provide theoretical support and practical references for the efficient management of global natural resources and environmental governance.

        Please reach out to collaborate 😃

    design:
      columns: '1'
  
---

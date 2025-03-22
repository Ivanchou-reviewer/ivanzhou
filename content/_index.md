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
        text: 个人简历（Download CV）
        url: uploads/resume.pdf
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
      title: '📚 研究兴趣与目标'
      subtitle: ''
      text: |-
        研究聚焦于自然资源管理与环境经济学，尤其是森林资源的可持续利用与生态保护政策的作用机制。探讨中国林权改革的实施及其对森林生态系统质量、森林碳汇效应和区域经济发展的影响，重点分析产权制度变革如何优化资源配置，提升生态效益。结合大数据分析与空间计量模型，从多维视角揭示政策改革的长期生态与经济效应。

        此外，研究还关注不同地区和经济发展水平下的政策异质性效应，通过对自然资源产权明晰化和管理效率提升的研究，提出推动可持续森林管理和应对气候变化的实践路径。目标是为全球自然资源的高效管理和环境治理提供理论支撑和实践参考。
        
    design:
      columns: '1'
  
---

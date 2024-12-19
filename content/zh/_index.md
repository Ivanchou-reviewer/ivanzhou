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
        text: 个人简历
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
        研究主要集中在自然资源管理与环境经济学领域，特别是森林资源的可持续利用和生态保护政策的作用机制。重点探讨中国林权改革的实施及其对森林生态系统质量、森林碳汇效应和区域经济发展的影响。研究通过应用先进的大数据分析和机器学习模型，从多维视角揭示政策改革的长期生态与经济效应，旨在为全球环境治理提供创新性的理论框架和实证依据。
        
        此外，研究还关注不同地区和经济发展水平下的政策异质性效应。通过对自然资源产权明晰化和管理效率提升的研究，提出了推动可持续森林管理和应对气候变化的实践路径。目标是为全球自然资源的高效管理和环境治理提供理论支撑和实践参考，推动学术界和政策制定者在应对环境挑战方面的前沿研究。
        
        研究内容包括：
        - 利用遥感技术和地理信息系统（GIS）评估森林生态系统的健康状况和碳汇能力。
        - 开发和应用机器学习算法预测森林资源管理政策的长期影响。
        - 结合社会经济数据和环境数据，构建综合评估模型，分析政策实施的多重效应。
        - 探讨气候变化背景下，森林资源管理政策的适应性和弹性策略。
        
        通过这些研究，旨在为全球环境治理和可持续发展提供科学依据和政策建议，推动自然资源管理领域的学术进步和实践创新。
        
    design:
      columns: '1'
 
---

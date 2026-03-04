---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: 下载简历
        url: uploads/cv.pdf
      headings:
        about: ''
        education: 教育背景
        interests: 研究方向
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🧠 研究简介'
      subtitle: ''
      text: |-
        我的研究聚焦于**计算精神病学**、**认知神经科学**与**智能计算分析人类自然行为**的交叉领域。通过结合神经影像学（MRI/fMRI）、计算建模与机器学习，我们致力于理解大脑如何支持认知功能，以及其异常如何导致精神疾病。

        **主要研究方向：**
        - 精神疾病的神经影像学标志物（MRI 皮层厚度、功能连接）
        - 决策与认知控制的计算模型
        - 基于可穿戴设备与视频的自然行为分析
        - 机器学习在临床神经科学中的应用

        **欢迎有意加入实验室的同学联系我！** 详见[研究方向](/zh/research/)页面。
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: 代表性论文
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 近期发表
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: contact
    content:
      title: 联系方式
      text: |-
        **邮箱：** your-email@institution.edu

        **办公室：** XXX 楼 XXX 室，您的机构

        欢迎就科研合作、学生事宜或任何问题与我联系。
    design:
      columns: '1'
---

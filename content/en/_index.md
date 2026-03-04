---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '5rem'

sections:
  # ── Biography ────────────────────────────────────────────────────────────────
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: ''
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  # ── Research Highlights ───────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '🧠 Research'
      subtitle: ''
      text: |-
        My work sits at the intersection of **computational psychiatry**, **cognitive neuroscience**, and **AI-driven behavioral analysis**. I develop computational models and apply neuroimaging methods (MRI/fMRI) to understand how the brain gives rise to cognition, and how its disruption leads to psychiatric disorders.

        **Current research themes:**
        - Neural correlates of psychiatric disorders (MRI cortical thickness, functional connectivity)
        - Computational modeling of decision-making and cognitive control
        - Naturalistic behavior analysis using wearable sensors and video
        - Machine learning applications in clinical neuroscience

        **Interested in joining the lab?** I welcome students with backgrounds in neuroscience, psychology, computer science, or biomedical engineering. See the [Research](/research/) page for open topics.
    design:
      columns: '1'

  # ── Featured Publications ─────────────────────────────────────────────────────
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  # ── Recent Publications ───────────────────────────────────────────────────────
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  # ── Contact ───────────────────────────────────────────────────────────────────
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        **Email:** your-email@institution.edu

        **Office:** Room XXX, Building XXX, Your Institution, City, Country

        I am happy to discuss research collaborations, student inquiries, or any questions about my work.
    design:
      columns: '1'
---

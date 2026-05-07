---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: markdown
    content:
      title: Current Engineering Focus
      text: |
        - Cloudflare governance and remediation platform using Python, Terraform, GitHub Actions, and the Cloudflare API
        - Infrastructure-as-Code workflows with automated validation, scheduled audits, and secure secret handling
        - Repository governance and DevSecOps practices with Dependabot, CodeQL, secret scanning, and branch protection
        - Data engineering workflows using APIs, ETL pipelines, medallion-style architecture, Supabase, PostgreSQL, and dashboard integrations
        - Public engineering documentation at 100daydash.blog covering platform engineering, cloud infrastructure, automation, analytics, and software development
    design:
      css_class: "wide-block"

  - block: collection
    content:
      title: Selected Projects
      text: Recent portfolio projects and in-progress case studies demonstrating cloud automation, infrastructure governance, API-driven data engineering, analytics platforms, and public engineering documentation.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---

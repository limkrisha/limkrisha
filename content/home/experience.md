---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience


# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

experience:
  - title: Term 2 courses
    company: FRE515, FRE521D, FRE530
    company_logo: org-gc
    date_start: 'Jan'
    date_end: 'April'
    description: |2-
        Analysis include:
        
        * Python to analyze emissions data
        * SQL to access Google Big Query
        * R to analyze time series commodity data
        * R to analyze survey datasets
        
  - title: Term 1 courses
    company: FRE501, FRE502, FRE515, FRE528
    company_logo: org-x
    date_start: 'Sept'
    date_end: 'Dec'
    description: |2-
      Analysis include:
        
        * R to connect to the UN Comtrade’s API to access data, plotting data and analyzing data to demonstrate law of one price
        * R to estimate a gravity model for bilateral trade in Transport Services (TSP) 
        * R to analyze housing prices in Vancouver
        * PowerBI to create financial statements and dashboards
      
  - title: Programming Bootcamp
    company_logo: org-gc
    date_start: Summer before MFRE start
    description: Incoming MFRE students take a 3-day intensive coding bootcamp to bring them up to quality required to succeed in the program

design:
  columns: '2'
---

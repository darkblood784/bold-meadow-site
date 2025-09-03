---
title: "Home"
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Call-to-action button under your bio
      button:
        text: "Download Résumé"
        url: "uploads/resume.pdf"
    design:
      banner:
        # Cover image lives in assets/media/
        filename: "kalen-emsley-Bkci_8qcdvQ-unsplash.jpg"
      biography:
        # Style your biography text
        style: "text-align: justify; font-size: 0.8em;"
      # Avatar customization
      avatar:
        size: large        # small | medium (default) | large | xl | xxl
        shape: rounded     # circle (default) | square | rounded

  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: "January 2006"
      # Education or Experience section first?
      is_education_first: false

  - block: skills
  content:
    title: "Skills & Hobbies"
    username: admin
  class: center-skills

  - block: languages
    content:
      title: "Languages"
      username: admin
---

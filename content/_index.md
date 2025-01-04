---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Paper about SER, accepted by ICASSP 2024
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2312.11974
        - text: Paper about ASR, accepted by InterSpeech 2024
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2407.03026
        - text: Paper about Deepfake Detection, accepted by ICASSP 2025
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2412.20799
---

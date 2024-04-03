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
  - block: biography
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
        - text: Check out all of my publications
          icon: custom/tum
          url: https://www.cda.cit.tum.de/team/burgholzer/
        - text: Check out the Munich Quantum Toolkit (MQT)
          icon: custom/mqt
          url: https://mqt.rtfd.io
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/lukas-burgholzer-7a1741a7/
---

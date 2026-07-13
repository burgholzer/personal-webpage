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
  - block: markdown
    content:
      title: New book
      text: |-
        [![Cover of *Design Automation Tools and Software for Quantum Computing*](/uploads/books/9783032067708_cover_image.jpg)](https://www.awin1.com/cread.php?awinmid=26429&awinaffid=2926239&campaign=author&ued=https%3A%2F%2Flink.springer.com%2Fbook%2F10.1007%2F978-3-032-06770-8)

        **[*Design Automation Tools and Software for Quantum Computing*](https://www.awin1.com/cread.php?awinmid=26429&awinaffid=2926239&campaign=author&ued=https%3A%2F%2Flink.springer.com%2Fbook%2F10.1007%2F978-3-032-06770-8)**

        *Inside the Munich Quantum Toolkit*

        [Purchase from Springer →](https://www.awin1.com/cread.php?awinmid=26429&awinaffid=2926239&campaign=author&ued=https%3A%2F%2Flink.springer.com%2Fbook%2F10.1007%2F978-3-032-06770-8)

        *Affiliate link — I may earn a commission from qualifying purchases.*
    design:
      css_class: book-promo
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: List of Publications
          icon: custom/tum
          url: https://www.cda.cit.tum.de/team/burgholzer/
        - text: Munich Quantum Toolkit (MQT)
          icon: custom/mqt
          url: https://mqt.rtfd.io
        - text: Connect on LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/lukas-burgholzer-7a1741a7/
---

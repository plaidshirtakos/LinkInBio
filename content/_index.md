---
title: 'Home'
date: 2024-01-01
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
        - text: Blog
          icon: hero/pencil
          url: https://anaploka.blogspot.com/
        - text: Hobbi - drón
          icon: hero/video-camera
          url: https://aka91hu.github.io/dronephoto/Fly-as-usual.html
        - text: VeloViewer
          icon: hero/forward
          url: https://veloviewer.com/athlete/98012356/
---

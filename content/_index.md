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
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/manfredbjorlin/
        - text: Bluesky
          url: https://bsky.app/profile/manfredbjorlin.bsky.social
        - text: Mastodon
          icon: brands/mastodon
          url: https://oslo.town/@manfredbjorlin
        - text: Sessionize
          icon: hero/megaphone
          url: https://sessionize.com/manfredbjorlin
        - text: GitHub
          icon: brands/github
          url: https://github.com/manfredbjorlin
  - block: markdown
    id: section1
    content:
      text: |-
       {{< sessionize >}}
---

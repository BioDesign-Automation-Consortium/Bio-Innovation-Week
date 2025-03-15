---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: biw
    # block: about.biography
    id: bioinnovationweek
    content:
      username: bio-innovation-week

  - block: portfolio
    id: events
    content:
      title: Events
      #subtitle: A subtitle
      #text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - events25
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
      

  - block: contact
    id: contact
    content:
      title: Contact Us
      text: |-
        Interested in participating, organizing, or sponsoring Bio Innovation Week? Reach out to us for more information on how you can get involved in IWBDA, IWBMA, the Nona Works Hackathon, or SBOL Workshops. We look forward to hearing from you!
      email: bio.design.automation.inc@gmail.com


  - block: people
    content:
      title: Organising Committee
      user_groups:
        - Organising Committee

---

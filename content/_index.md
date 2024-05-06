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
          - events24
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

  - block: contact
    id: logistics
    content:
      title: Conference Logistics
      text: |-
        ## Location Details
        
        Bio-Innovation Week will be held at the <b>Rajen Kilachand Center for Integrated Life Sciences and Engineering</b> in <b>Boston University</b>. </br>

        <b>Address:</b></br>
        610 Commonwealth Ave,</br>
        Boston, MA 02215,</br>
        United States

        ## Hotels
        Hotels close to Boston University and Asimov during Bio-Design Week may be more expensive than usual due to a Red Sox-Yankees series happening during the same week. We recommend looking at hotels along the MBTA’s Green Line (B) or within a reasonable walking distance to Boston University. There are options over in the Longwood Medical area (~25 minute walk or ~15 min by public transportation). Hotels in Cambridge may also be less expensive, but would require a longer commute.
        
      coordinates:
        latitude: '42.349228822225356'
        longitude: '-71.10150585063934'

  - block: people
    content:
      title: Organising Committee
      user_groups:
        - Organising Committee

---

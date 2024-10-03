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
  
  - block: markdown
    id: registration
    content:
      title: Registration
      text: |- 
        <link rel="stylesheet" type="text/css" href="https://www.brownpapertickets.com/widget_v671.css" /> <DIV ID="bpt_eventbody"><CENTER><BR><BR>Brown Paper Tickets Ticket Widget Loading...<BR><BR><A HREF="https://www.brownpapertickets.com/event/6463652">Click Here</A> to visit the Brown Paper Tickets event page.</CENTER><BR><BR></DIV> <script src="https://www.brownpapertickets.com/eventwidget.js?event=6463652&nodescription=1" type="text/javascript" language="javascript"></script> <script src="https://www.brownpapertickets.com/widget_v671.js?event=6463652" type="text/javascript" language="javascript"></script>
    design:
      columns: '2'
  
  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |- 
          # Bio-Innovation Week - November 16-19, 2024

          ## Saturday, November 16 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:10** Welcome and kick-off of Bio-Design Week
          - **09:10-10:10** Keynote
          - **10:10-10:40** Coffee break
          - **10:40-12:00** 
            - SBOL Visual Workshop
            - NonaWorks Logistics, Examples, Demos (TBD)
          - **12:00-13:00** Lunch
          - **13:00-15:00** 
            - IWBDA Talks
            - NonaWorks + Office Hours
          - **15:00-15:30** Coffee break
          - **15:30-17:00** Nona Works: Present Proposals
          - **17:00-18:00** Networking Reception

          ## Sunday, November 17 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:20** IWBDA Talks
          - **10:20-10:45** Coffee break
          - **10:45-12:00** SBOL Data Model Workshop
          - **12:00-13:00** Lunch
          - **13:00-14:20** IWBDA Talks
          - **14:20-14:40** Coffee break
          - **14:40-17:00** IWBDA Talks
          - **08:30-17:00** NonaWorks Office Hours

          ## Monday, November 18 - 8 St. Mary's Street, Photonics 906

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:20** IWBDA Talks
          - **10:20-10:45** Coffee break
          - **10:45-11:45** Keynote: DARPA BTO Head Michael Koeris
          - **11:45-13:20** Lunch
          - **13:20-14:40** IWBMA Talks: Amplifying Science Through Automation
          - **14:40-15:10** Coffee break
          - **15:10-16:50** IWBDA Talks
          - **08:30-16:50** NonaWorks Office Hours
          - **17:00-20:30** Dinner

          ## Tuesday, November 19 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:45** NonaWorks Presentations and Voting
          - **09:45-10:15** Coffee break
          - **10:30-11:30** Brainstorming
          - **11:30-12:00** Brainstorming and Summary
          - **12:00-13:00** Lunch
          - **13:00-14:00** IWBMA Industry Talks
          - **14:00-15:00** IWBDA Talks
          - **13:00-15:00** NonaWorks Office Hours
          - **15:00-15:20** Awards and Closing Remarks
          - **15:20-17:30** Vendor Booths & Cocktail Hour & DAMP Lab Tours in 106B and 106D


  - block: people
    content:
      title: Organising Committee
      user_groups:
        - Organising Committee

---

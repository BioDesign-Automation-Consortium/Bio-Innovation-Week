---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: biw24
    # block: about.biography
    id: bioinnovationweek
    content:
      username: bio-innovation-week24

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
          - **09:00-09:10** Welcome and kick-off of Bio Innovation Week
          - **09:10-10:10** Keynote - Dr Roseanna N. Zia: Colloidal Physics Instantiates Life in Biological Cells
          - **10:10-10:40** Coffee break
          - **10:40-12:00** 
            - SBOL Data Model Workshop
            - NonaWorks Logistics, Examples, Demos (TBD)
          - **12:00-13:00** Lunch
          - **13:00-14:20** 
            - SBOL Visual Workshop
            - NonaWorks + Office Hours
          - **14:20-15:00** Coffee break
          - **15:00-16:00** Nona Works: Present Proposals

          ## Sunday, November 17 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:20** Managing lab info
          - **10:20-10:45** Coffee break
          - **10:45-12:00** Managing lab info
          - **12:00-13:00** Lunch
          - **13:00-14:20** IWBDA Talks
              - **13:00-13:20** A Novel Approach to Tuning Effective Translation Rate: Tree-Based RBS Structural Analysis
              - **13:20-13:40** Deep Bayesian Optimization for NAND Aptamer Design
              - **13:40-14:00** PUMA: Promoter Unraveling Through Machine-learning Algorithms
              - **14:00-14:20** A Reinforcement Learning Framework for Automated Estimation of Rare-event Probabilities in Biochemical Systems
          - **14:20-14:40** Coffee break
          - **14:40-16:00** IWBDA Talks
              - **14:40-15:00** A Decade of SBOL Visual: The Adoption of a Diagram Standard
              - **15:00-15:20** Rule-based generation of synthetic genetic circuits
              - **15:20-15:40** SynBioSuite 2: Improving Encoding of Genetic Designs and Extending DBTL Coverage
              - **15:40-16:00** Making two turns of the DBTL Cycle to improve a biosensor
          - **08:30-17:00** NonaWorks Office Hours

          ## Monday, November 18 - 8 St. Mary's Street, Photonics 906

          - **08:30-09:00** Registration and light breakfast
          - **09:00-10:00** Keynote - Dr. Michael Koeris
          - **10:00-10:25** Coffee break
          - **10:25-11:45** Synbiohub Workshop
          - **11:45-13:20** Lunch
          - **13:20-14:40** IWBMA Talks: Amplifying Science Through Automation
          - **14:40-15:10** Coffee break
          - **15:10-16:30** IWBDA Talks
              - **15:10-15:30** Uncovering the genetic basis of transformation efficiency in Kluyveromyces marxianus with comparative omics
              - **15:30-15:50** The NIST Living Measurement Systems Foundry: Protocols and Standards for Large-Scale, Quantitative Sequence-Function Measurements
              - **15:50-16:10** Additive Manufacturing Enabled Monolayer Chambers for Immune Cells’ Communication Studies
              - **16:10-16:30** Certification and validation of engineered DNA molecules
          - **08:30-16:50** NonaWorks Office Hours
          - **17:30-20:30** Dinner

          ## Tuesday, November 19 - 610 Commonwealth Avenue, CILSE 101

          - **08:30-09:00** Registration and light breakfast
          - **09:00-09:45** NonaWorks Presentations and Voting
          - **09:45-10:15** Coffee break
          - **10:30-11:30** Brainstorming
          - **11:30-12:00** Brainstorming and Summary
          - **12:00-13:00** Lunch
          - **13:00-14:00** IWBMA Industry Talks
          - **14:00-15:00** IWBDA Talks
              - **14:00-14:15** Open-Set Biomedical Context Extraction via Multi-Task and Semi-Supervised Learning
              - **14:15-14:30** Knowledge retrieval and information reuse: a receptor design study
              - **14:30-14:45** The role of NLP and LLMs in automating expert-driven model refinement: a GBM case study
              - **14:45-15:00** Ligify: Automated Genome Mining for Ligand-Inducible Transcription Factors
          - **13:00-15:00** NonaWorks Office Hours
          - **15:00-15:20** Awards and Closing Remarks
          - **15:20-17:30** Vendor Booths & Cocktail Hour & DAMP Lab Tours in 106B and 106D


  - block: people
    content:
      title: Organising Committee
      user_groups:
        - Organising Committee 2024

---

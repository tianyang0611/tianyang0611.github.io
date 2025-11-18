---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Page sections
sections:
  # 1. 个人简介（用 authors/admin 的内容）
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # small / medium / large / xl / xxl
        shape: rounded # circle / square / rounded

  # 2. News 区块
  - block: markdown
    content:
      title: "News"
      text: |-
        - **Nov 2024 – Graduate Climate Conference (GCC), Boston**  
          Attended the 2024 Graduate Climate Conference and presented research on weather whiplash.  
          → [More about GCC](https://graduateclimateconference.github.io/)

        - **May 2025 – Sustainability Research Development Grant**  
          Received Indiana University’s **Sustainability Research Development Grant** to support research on hydroclimate extremes (~$7,000).

        - **Mar 2025 – AAG Climate Specialty Group – 1st Place Student Award**  
          Won the **1st Place Student Award** in the AAG Climate Specialty Group student paper competition at the 2025 AAG Annual Meeting.  
          → [Award information](https://sites.google.com/view/aag-climate/awards/student-paper-competition)
    design:
      columns: 1

  # 3. Selected Publications 区块
  - block: markdown
    content:
      title: "Selected Publications"
      text: |-
        1. **Yang, T.**, Yang, X., Jia, C.* (2023). Detecting the main driving force of runoff change in the Beiluo River Basin, China. *Environmental Science and Pollution Research*.

        2. **Yang, T.***, Yang, H., Yang, F., Yang, X. (2023). Assessment of groundwater salinization impact in coastal aquifers based on the shared socioeconomic pathways: An integrated modeling approach. *Environmental Research*.
    design:
      columns: 1
---

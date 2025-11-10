---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_ZhongjingJiang_20251108.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research focuses on addressing the complex challenges posed by climate change, with an emphasis on Earth System Modeling, chemistry-climate interactions, and Uncertainty Quantification (UQ). Drawing on my academic background in applied mathematics and atmospheric science, I am dedicated to advancing our understanding of the intricate relationships within the Earth’s climate system as well as finding sustainable solutions to the world.
        
        Prior to joining UIUC, I did my postdoc at Brookhaven National Laboratory, where my work spanned the Environmental and Climate Sciences Department and the Computer Science Initiative. This experience provided me with a unique perspective at the intersection of climate science and computational methodologies.

        I envision my research to contribute to both scientific understanding and practical solutions for pressing climate and environmental challenges. My focus lies particularly in terrestrial ecosystems, air quality, climate variability, and improving climate model predictability. By leveraging my interdisciplinary expertise, I aim to unravel the complexities of Earth system and climate modeling, offering insights that enhance scientific knowledge and inform nature-based solutions for mitigating global climate challenges, particularly in the agricultural domain.

  - block: markdown
    id: papers
    content:
      title: Publications
      text: |
        [Link to my Google Scholar page](https://scholar.google.com/citations?user=73N_824AAAAJ&hl=en)       
        
        **Preprint:**

        - **Jiang, Z.**, Isenberg, N., Subba, T., Urban, N., Serbin, S., Kuang, C., Woo, H.: A framework for parametric and predictive uncertainty quantification in the E3SM Land Model: Assessing the impact of site and observable heterogeneity. ESS Open Archive . March 08, 2025.

        - Zhu, F., Torbunov, D., Ren, Y., **Jiang, Z.**, Zhao, T., Yogarathnam, A., and Yue, M.: Mitigating Parameter Degeneracy using Joint Conditional Diffusion Model for WECC Composite Load Model in Power Systems, 2024.

        **Peer-reviewed publications:**

        - **Jiang, Z.**, Li, J., Liu, G., and Zhang, C.: Impact of the Indian Ocean Dipole Mode on Planetary Boundary Layer Ozone in China, Geophys Res Lett, 51, https://doi.org/10.1029/2024GL110108, 2024.
        - Ye, X., Zhang, L., Wang, X., Lu, X., **Jiang, Z.**, Lu, N., Li, D., and Xu, J.: Spatial and temporal variations of surface background ozone in China analyzed with the grid-stretching capability of GEOS-Chem High Performance, Science of the Total Environment, 914, https://doi.org/10.1016/j.scitotenv.2024.169909, 2024.
        - Ying, T., Li, J., **Jiang, Z.**, Liu, G., Zhang, Z., Zhang, L., Dong, Y., and Zhao, C.: Increased aerosol scattering contributes to the recent monsoon rainfall decrease over the Gangetic Plain, Sci. Bull., https://doi.org/10.1016/j.scib.2023.08.052, 2023.
        - Dong, Y., Li, J., Yan, X., Li, C., **Jiang, Z.**, Xiong, C., Chang, L., Zhang, L., Ying, T., and Zhang, Z.: Retrieval of aerosol single scattering albedo using joint satellite and surface visibility measurements, Remote Sens. Environ., 294, https://doi.org/10.1016/j.rse.2023.113654, 2023.
        - Zhang, C., **Jiang, Z.**, Liu, M., Dong, Y., and Li, J.: Relationship between summer time near-surface ozone concentration and planetary boundary layer height in Beijing, Atmos. Res., 293, 106892, https://doi.org/10.1016/j.atmosres.2023.106892, 2023.
        - Liu, G., Li, J., **Jiang, Z.**, and Li, X.: Impact of Sea Surface Temperature Variability at Different Ocean Basins on Dust Activities in the Gobi Desert and North China, Geophys. Res. Lett., 49,  https://doi.org/10.1029/2022GL099821, 2022.
        - Zhang, L., Li, J., **Jiang, Z.**, Dong, Y., Ying, T. and Zhang, Z.: Clear-Sky Direct Aerosol Radiative Forcing Uncertainty Associated with Aerosol Optical Properties Based on CMIP6 models, J. Clim., 35(10), 3007–3019, https://doi.org/10.1175/jcli-d-21-0479.1, 2022a.
        - Zhang, L., Li, J., **Jiang, Z.**, Dong, Y., Ying, T. and Zhang, Z.: Clear-Sky Direct Aerosol Radiative Forcing Uncertainty Associated with Aerosol Vertical Distribution Based on CMIP6 models, J. Clim., 35(10), 3021–3035, https://doi.org/10.1175/jcli-d-21-0480.1, 2022b.
        - **Jiang, Z.** and Li, J.: Impact of eastern and central Pacific El Niño on lower tropospheric ozone in China, Atmos. Chem. Phys., 22, 7273–7285, https://doi.org/10.5194/acp-22-7273-2022, 2022.
        - **Jiang, Z.**, Li, J., Lu, X., Gong, C., Zhang, L., and Liao, H.: Impact of western Pacific subtropical high on ozone pollution over eastern China, Atmos. Chem. Phys., 21, 2601–2613, https://doi.org/10.5194/acp-21-2601-2021, 2021. 
        - **Jiang, Z.**, Jolleys, M. D., Fu, T.-M., Palmer, P. I., Ma, Y., Tian, H., Li, J., and Yang, X.: Spatiotemporal and probability variations of surface PM2.5 over China between 2013 and 2019 and the associated changes in health risks: An integrative observation and model analysis, Sci. Total Environ., 723, 137896, https://doi.org/10.1016/j.scitotenv.2020.137896, 2020.
        - Dong, Y., Li, J., Guo, J., **Jiang, Z.**, Chu, Y., Chang, L., Yang, Y., and Liao, H.: The impact of synoptic patterns on summertime ozone pollution in the North China Plain, Sci. Total Environ., 735, 139559, https://doi.org/10.1016/j.scitotenv.2020.139559, 2020.
        - Xu, X., **Jiang, Z.**, Li, J., Chu, Y., Tan, W., and Li, C.: Impacts of meteorology and emission control on the abnormally low particulate matter concentration observed during the winter of 2017, Atmos. Environ., 225, 117377, https://doi.org/10.1016/j.atmosenv.2020.117377, 2020.


  - block: collection
    id: talks
    content:
      title: Presentations
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

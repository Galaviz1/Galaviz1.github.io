---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      username: admin
      text:

  - block: features
    content:
      title: Skills
      items:
        - name: MATLAB / Python
          description: Signal processing, PA modeling, DPD algorithms
          icon: code
          icon_pack: fas
        - name: FPGA Design
          description: VHDL, Verilog, SystemVerilog, UVM
          icon: microchip
          icon_pack: fas
        - name: RF Instrumentation
          description: NVNA, spectrum analyzers, automated testbeds
          icon: satellite-dish
          icon_pack: fas
        - name: EDA Tools
          description: Quartus, Xilinx ISE, Keysight ADS, Modelsim
          icon: laptop-code
          icon_pack: fas
        - name: Digital Predistortion
          description: DPD linearization, NARMA, spline modeling
          icon: wave-square
          icon_pack: fas
        - name: HDL
          description: HDL code generation, fixed-point design, hardware verification
          icon: memory
          icon_pack: fas
        - name: Research & Publication
          description: 15+ journal/conference papers, IEEE reviewer
          icon: book-open
          icon_pack: fas

  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: RF Research & Development Engineer
          company: "T\xE9l\xE9com Paris"
          company_url: 'https://www.telecom-paris.fr/'
          company_logo:
          location: Palaiseau, Paris, France
          date_start: '2024-10-01'
          date_end: '2025-12-31'
          description: |2-
              * RF R&D Engineer in the **Docte6G** national project in collaboration with NXP Semiconductors
              * Developed digital predistortion (DPD) linearization for millimeter-wave (mmW) 6G systems
              * Advanced subband DPD theoretical framework with hardware measurement validation
        - title: Adjunct Researcher (Postdoctoral)
          company: "Tecnol\xF3gico de Monterrey"
          company_url: 'https://tec.mx/en'
          company_logo:
          location: Monterrey, Mexico
          date_start: '2020-01-01'
          date_end: '2026-01-31'
          description: |2-
              * Led reconfigurable intelligent surfaces (RIS) platform with AI-driven algorithms for 5G/6G
              * Designed FPGA-based AWGN module and LDPC encoder/decoder with UVM verification (SAGE Microelectronics)
              * Developed spectral modeling and DPD algorithms for 5G massive MIMO systems
              * Advised 3 M.Sc. students and served on Ph.D. thesis committees
        - title: CONACyT Postdoctoral Fellow
          company: "Tecnol\xF3gico de Monterrey"
          company_url: 'https://tec.mx/en'
          company_logo:
          location: Monterrey, Mexico
          date_start: '2018-01-01'
          date_end: '2020-12-31'
          description: |2-
              * Optimized spectral efficiency in massive MIMO systems for 5G (CONACYT Grant)
              * Designed and implemented DPD algorithms from concept through FPGA prototyping
        - title: Visiting Scholar
          company: The Ohio State University
          company_url: 'https://www.osu.edu/'
          company_logo:
          location: Columbus, OH, USA
          date_start: '2014-01-01'
          date_end: '2016-12-31'
          description: |2-
              * RF Nonlinear Research Laboratory, Dept. of Electrical and Computer Engineering
              * Measurement and behavioral modeling of Chireix PA dynamic efficiencies
              * NSF Scholar (2015--2016)
    design:
      columns: '2'

  - block: accomplishments
    id: awards
    content:
      title: Awards & Distinctions
      subtitle:
      date_format: Jan 2006
      items:
        - title: Researcher Level I (SNII-I)
          certificate_url:
          date_end: ''
          date_start: '2022-01-01'
          description: Distinction by the National Researchers System of Mexico.
          organization: CONACYT / SNII
          organization_url:
          url: ''
        - title: Researcher Candidate (SNII)
          certificate_url:
          date_end: '2021-12-31'
          date_start: '2019-01-01'
          description: Distinction by the National Researchers System of Mexico.
          organization: CONACYT / SNII
          organization_url:
          url: ''
        - title: IEEE Senior Member
          certificate_url:
          date_end: ''
          date_start: '2020-01-01'
          description: Recognition as IEEE Senior Member.
          organization: IEEE
          organization_url: https://www.ieee.org
          url: ''
        - title: IETE JC Bose Memorial Award 2020
          certificate_url:
          date_end: ''
          date_start: '2020-06-01'
          description: Best Engineering Oriented Paper award.
          organization: IETE
          organization_url:
          url: ''
        - title: CONACyT Postdoctoral Research Fellowship
          certificate_url:
          date_end: '2020-12-31'
          date_start: '2018-01-01'
          description: Two-year postdoctoral research fellowship.
          organization: CONACyT
          organization_url:
          url: ''
        - title: NSF Scholar
          certificate_url:
          date_end: '2016-12-31'
          date_start: '2015-01-01'
          description: National Science Foundation Scholar at The Ohio State University.
          organization: NSF
          organization_url: https://www.nsf.gov
          url: ''
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
        exclude_featured: false
      count: 5
    design:
      columns: '2'
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: Feel free to reach out for research collaborations, consulting, or academic inquiries.
      email: jagalaviz@ieee.org
      address:
        street:
        city:
        region:
        postcode:
        country:
        country_code:
      autolink: true
    design:
      columns: '2'
---

---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Transform Your Business with AI Solutions by Mak J AI Limited
      text: 🌟 INNOVATIVE. SCALABLE. TRANSFORMATIVE. 🌟
      # primary_action:
      #   text: Get Started
      #   url: https://makj.ai/services/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://makj.ai/docs
      announcement:
        text: "Announcing the launch of our new AI-driven solutions."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "500+"
          description: |
            Businesses empowered  
            with AI Solutions
        - statistic: "15+"
          description: |
            AI Products  
            developed
        - statistic: "5k+"
          description: |
            Hours of consulting  
            delivered
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Our Expertise
      text: Revolutionize your operations with AI
      items:
        - name: Customized AI Solutions
          icon: light-bulb
          description: Tailored AI strategies to solve your business challenges and maximize ROI.
        - name: Advanced Analytics
          icon: chart-bar
          description: Deep insights with our advanced data analytics services.
        - name: AI Integration
          icon: server
          description: Seamless AI integration with your existing systems.
        - name: Scalable Infrastructure
          icon: cloud
          description: Robust and scalable AI infrastructure to support your growing needs.
        - name: Expert Advisory
          icon: user-tie
          description: Guidance from industry-leading AI experts.
        - name: Continuous Innovation
          icon: refresh
          description: Staying ahead with the latest advancements in AI and machine learning.
  - block: cta-image-paragraph
    id: services
    content:
      items:
        - title: AI Solutions Tailored to Your Needs
          text: From conceptualization to deployment, we’ve got you covered.
          feature_icon: check
          features:
            - "Custom AI model development"
            - "AI-driven business transformation"
            - "Proactive AI strategy consulting"
          # Upload image to `assets/media/` and reference the filename here
          image: ai-solutions.png
          button:
            text: Get Started
            url: https://makj.ai/services/
        - title: Join Our Community
          text: Connect with professionals and experts in our AI community.
          feature_icon: bolt
          features:
            - "Expert support channel"
            - "Dedicated AI discussions"
            - "Share insights and innovations"
          # Upload image to `assets/media/` and reference the filename here
          image: community.jpg
          button:
            text: Join Community
            url: https://community.makj.ai
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Jane Doe"
          role: "CTO at InnovateTech"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Mak J AI Limited transformed our analytics capabilities and drove significant business insights with their expertise!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Transform Your Business with AI
      text: Unlock new potentials and elevate your operations.
      # button:
      #   text: Get Started
      #   url: https://makj.ai/services/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
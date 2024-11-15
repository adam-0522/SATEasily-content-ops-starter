---
title: Plans
slug: plans
sections:
  - title:
      text: Flexible Plans
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: Lesson On Demand
        price: $100
        details: per hour
        description: >
          Recommended if you want to try some lessons with us first without a
          commitment, or if you have specific need in an area.
        features:
          - 'Flexible, one-on-one tutoring when you need it'
          - Target specific SAT sections or concepts based on your requests
          - Immediate feedback and strategies to boost your score
          - Feature four
        image:
          url: /images/Plan 1.jpg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: Book Sessions
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: 30-Minute Consultation
        price: Free
        details: Required before booking for tutoring sessions
        description: |
          Touch base on student's current performance and goals.
        features:
          - Personalized discussion on your SAT prep needs and goals
          - Get a clear study plan tailored to your strengths and weaknesses
          - No obligation – just explore if our sessions are right for you
          - ''
        image:
          url: /images/Plan 2.jpg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Book Free Consultation
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: 8-Hour Study Plan
        price: $700
        details: save $100 from original total
        description: |
          Save on hourly rates with a comprehensive 8-hour package
        features:
          - >-
            Structured lessons covering all major SAT components: Reading,
            Writing, and Math
          - 'Ideal for focused, consistent progress over a set period'
          - Feature four
          - Feature five
        image:
          url: /images/Plan 3.jpg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

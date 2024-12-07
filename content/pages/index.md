---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: HR.
      color: text-dark
      type: TitleBlock
    subtitle: hello
    text: >
      Please note that this page is under development. There may be errors in
      functionality, so kindly take it into consideration.
    actions: []
    media:
      url: /images/IMG_0693.jpeg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: 핵심 기능
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 3가지 중요 내용
    items:
      - type: FeaturedItem
        title: 500k
        subtitle: 츄르 뜯긴 횟수
        text: |
          츄르를 뜯을 때마다 느껴지는 간절한 눈빛 50만 번의 "줘!"라는 무언의 외침
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/IMG_0269.jpeg
          styles:
            self:
              borderRadius: x-large
      - title: 20x
        subtitle: 방해한 기록
        text: |
          바쁠 때를 귀신같이 알아차립니다
          20배 더 집중해야 하는 운명
          키보드 위, 책 위, 그리고 가슴 위까지!
          하지만 방해도 귀여우면 괜찮죠!
        image:
          url: /images/IMG_0790.jpeg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: 200%
        subtitle: 골골송의 위력
        text: |
          볼륨은 200%, 집사의 의지력은 0%
          이 작은 몸에서 나오는 우렁친 총소리! 집주인 무장 해제
        image:
          url: /images/IMG_0390.jpeg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: This is a badge
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: 쓸데없이 귀여운 행동 횟수
        tagline: Feature 1
        subtitle: 999+
        text: |
          왜 이런 행동을 할까?
        image:
          type: ImageBlock
          url: /images/IMG_0826.jpeg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Business Consulting
        tagline: Feature 2
        subtitle: Be in good company
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Business consulting
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

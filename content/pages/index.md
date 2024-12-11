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
      This product is in development. Please note that there is no sales
      schedule.
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
        text: >
          츄르 봉지가 열리는 찰나, 번뜩이는 눈빛과 함께 들려오는 무언의 외침: *"줘!"* 이미 50만 번의 전투를 치르며 학습된
          당신의 손은 자동으로 츄르를 제공합니다. 이건 식량 분배가 아니라, 생존 본능입니다.
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
        text: >
          책 위? 키보드 위? 아니, 가슴 위까지! 당신이 바쁘다고요? 그럼 *바로 지금* 주인님께 주목하라는 강력한 방해 시그널이
          날아옵니다. 하지만 이 방해를 거부할 수 있냐고요? 그런 당신의 의지를 테스트해 본 적 있나요?
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
          골골송은 단순한 소리가 아닙니다.
          볼륨은 200%, 당신의 의지력은 0%!
          이 작은 몸에서 나오는 우렁찬 총소리(?)는
          당신을 무장 해제시킵니다.
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
        title: 빼앗긴 침대
        tagline: Feature 1
        subtitle: '9,999+'
        text: |
          침대는 집주인의 것이라고 생각했지만,
          언제부턴가 자는 모습을 보고
          "이건 원래 네 거였나 봐..." 하고 체념.
          결국 남은 구석에서 웅크리고 자는 건 당신!!
        image:
          type: ImageBlock
          url: /images/IMG_0003.jpeg
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
      - type: FeaturedItem
        title: 쓸데없이 귀여운 행동 횟수
        tagline: Feature 2
        subtitle: 999+
        text: |+
          <div style="text-align: left">왜 이런 행동을 할까요?</div>

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

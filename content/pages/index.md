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
        subtitle: 50만 번의 전투
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
        subtitle: 20배 강력한 방해력
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
        subtitle: 골골송의 초월적 파괴력
        text: >
          골골송은 소리가 아닙니다. 그것은 강제 힐링입니다. 볼륨은 200%, 집중력은 -200%! 이 작은 고양이 스피커에서 울려
          퍼지는 \*“골골골”\*은 당신의 모든 계획을 물거품으로 만들어 버립니다.
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
  - type: PricingSection
    title:
      type: TitleBlock
      text: 완벽한 가격!
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: 3가지 유연한 요금제
    plans:
      - type: PricingPlan
        title: ''
        price: Free
        details: No credit card required
        description: |
          0원! 당신의 고양이보다 더 부담 없는 가격
        features:
          - '가벼운 시작: 고양이와의 첫 만남을 위한 기본 플랜. 당신은 부담 제로, 고양이는 만족 만점!'
          - '제한된 혜택: 츄르 제공 횟수는 제한적. 방해도 약간 덜 치열. 하지만 사랑만큼은 무제한!'
          - '광고 시청: 가끔 고양이의 "츄르 광고" 시청이 필요합니다. 애처로운 눈빛과 함께.'
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: ''
        price: $99
        details: per month
        description: |+
          현실적 선택, 더 많은 츄르와 평화로운 삶

        features:
          - '츄르 무제한: 이제 츄르 봉지를 수시로 뜯어도 됩니다. 고양이와 평화 협정 체결 완료!'
          - '방해 감소 모드: 약간의 간식 보조로 "20배 방해력"이 10배로 줄어듭니다. 생산성 2배 증가!'
          - '골골송 프리미엄: 골골송 무손실 음질로(flac 코덱 지원) 업그레이드. 힐링 효과도 두 배!'
          - Feature four
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: ''
        price: 영구 요금제
        details: per month
        description: |
          이건 투자입니다, 고양이와의 평생 행복을 위해
        features:
          - '츄르 평생 제공: 이제 고양이와의 계약이 영구적입니다. 1년 뒤엔 무료인 셈!'
          - '방해 제로: 고양이가 스스로 알아서 방해를 덜어주는 "자동 방해 해제 모드" 활성화 (개발 예정).'
          - '골골송 AI 탑재: 골골송이 당신의 기분을 자동으로 분석해 맞춤형 힐링 제공. 신세계 오픈!'
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
        actions:
          - type: Button
            label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: ImageGallerySection
    subtitle: 우리의 고객님
    images:
      - type: ImageBlock
        url: /images/empathy-logo.svg
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        url: /images/wellster-logo.svg
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/vise-logo.svg
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/telus-logo.svg
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/contenful-logo.svg
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/sanity-logo.svg
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        url: /images/rangle-logo.svg
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: 실제 고객님들 후기
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
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

---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: 'Vendor Interior yang Mudah, Cepat, dan Terjangkau'
      color: text-dark
    subtitle: ''
    text: |+

      Solusi Desain yang Tepat dan Fungsional untuk Setiap Ruang di Rumah Anda

    actions:
      - label: Mulai
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    media:
      url: /images/main-hero.svg
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
      text: Mengapa Memilih Kami?
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'Solusi Desain Interior Cepat, Terjangkau, dan Berkualitas'
    items:
      - title: Proses Cepat
        subtitle: ''
        text: >+

          Kami menyelesaikan proyek desain interior dengan efisien, memastikan
          hasil yang cepat tanpa mengorbankan kualitas.

        image:
          url: /images/icon2.svg
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
      - type: FeaturedItem
        title: Desain Praktis dan Fungsional
        subtitle: ''
        text: >+

          Desain kami mengutamakan fungsionalitas dan kenyamanan, memaksimalkan
          penggunaan ruang dengan tampilan yang menarik.

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
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - type: FeaturedItem
        title: Pengalaman dan Keahlian
        subtitle: ''
        text: >
          Dengan pengalaman lebih dari 8 tahun, kami menghadirkan solusi desain
          yang tepat sesuai kebutuhan dan anggaran Anda.
        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
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
            justifyContent: center
            textAlign: left
    actions:
      - label: Kontak Kami
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: Sebelum memulai interior
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
  - subtitle: Beberapa contoh project kami
    images:
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
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
  - title:
      text: Beritahu kami kebutuhan interior anda
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: WA
          label: WA
          hideLabel: true
          placeholder: Kontak WA
          isRequired: false
          width: full
          type: EmailFormControl
        - name: Jelaskan kebutuhan anda
          label: Jelaskan kebutuhan anda
          hideLabel: true
          placeholder: Jelaskan kebutuhan anda
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

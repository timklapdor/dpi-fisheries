---

layout: amp-story
title: NSW Trout monitoring  # The title of the story
subtitle: Annual stream monitoring overview
slug: trout-monitoring
publish_date: June 2019
publisher: NSW Department of Primary Industries # The name of the story's publisher
publisher_logo_src: 00-26fifty.png #logo in 1x1 aspect ratio - .png
poster_portrait_src: # Story Poster in 3x4 aspect ratio min 696px x 928px
poster_square_src: # Story Poster in 1x1 aspect ratio min 928px x 928px
poster_landscape_src: # Story Poster in 4x3 aspect ratio min 928px x 696px
brand_logo: 00-dpi-rev.svg
background_colour:
background_audio:
permalink: :slug/index.html
cover:
  title: Fisheries Test
  logo_placement: right
  secondary_logo:
  background_image: trout.jpg
  filter: "brightness(.8)"
  gradient_overlay: "to bottom, rgba(0,0,0,0.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%"
slides:
  - id:  challenge # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: creek.jpg #file url
    background_brightness: .5 #brightness control 0-1
    background_blur: 4 #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "center-text" #styling classes
    text_type: "list" #choose from list, block, blockquote, question
    text_div_class:
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_list_ordered: false #true for order lists, false for unordered
    text_list_bullet: # for unordered lists - disc, square,
    text_list_pre: |- #type as Markdown
      NSW trout fisheries are being challenged by:
    text_list_items:
    - "climate change,"
    - "pest species,"
    - "access restrictions,"
    - "habitat degradation and more."
    text_content: |- #type as Markdown
  - id:  action # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: creek.jpg #file url
    background_brightness: .5 #brightness control 0-1
    background_blur: 4 #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "center-text " #styling classes
    text_type: "blockquote" #choose from list, block, blockquote, question
    text_div_class: border-dpi-yelllow
    text_animation: fly-in-right
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      As a result NSW DPI Fisheries have developed a **state-wide trout strategy** to determine how to best address these challenges facing the fishery.
  - id:  action # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: creek.jpg #file url
    background_brightness: .5 #brightness control 0-1
    background_blur: #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "center-text" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class:
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      A key component of the trout strategy is **improved monitoring of trout fisheries**.

      This monitoring will answer questions like...
  - id: Q1  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: field.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur:  #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-middle" #styling classes
    text_type: "question" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-yellow "
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      ## What is the distribution, abundance and size of fish?
  - id: Q2 # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: handfull.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur:  #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-middle" #styling classes
    text_type: "question" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-orange-d"
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      ## Is there a decline in trout populations?
  - id: Q3 # need a unique id for each slide, don't use numbering
    background_url: trayfull.jpg #file url
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-middle" #styling classes
    text_type: "question" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-accent"
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      ## Is stocking successful & is there natural recruitment?
  - id: workshops # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: meeting.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur:  #blur setting - px settings
    text_template: "third" #location of text
    text_layer_class: "bottom block" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "bg-20-dpi-blue block-content"
    text_animation: "fly-in-bottom"
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown
      During the trout strategy workshops stakeholders were asked to indicate key streams for spawning, monitoring and habitat rehabilitation.
  - id: map # need a unique id for each slide, don't use numbering
    auto_advance:
    background_url: regions-map.png #file url
    background_brightness:  #brightness control 0-1
    background_blur:  #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-top" #styling classes
    text_type: "question" #choose from list, block, blockquote, question
    text_div_class: "question bg-20-dpi-orange-d "
    text_animation: "fly-in-top"
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown
      45 stream monitoring sites were identified across the state.
  - id: split # need a unique id for each slide, don't use numbering
    background_url: regions-map.png #file url
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-middle" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "question bg-20-dpi-orange-d "
    text_animation: "fly-in-right"
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown
      This includes 15 rivers split evenly between the **North**, **Central** and **Southern** NSW trout fisheries. These sites will be sampled annually to provide data on the long term trends in the fishery.
  - id:  backpack # need a unique id for each slide, don't use numbering
    background_url: electro-fishing.jpg #file url
    background_gradient: "to top, rgba(0,0,0,0.6) 30%,rgba(0,0,0,0) 60%" # add in CSS gradient
    text_template: "third" #location of text
    text_layer_class: "bottom block " #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "block-content bg-20-dpi-green"
    text_animation: fly-in-bottom
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      Backpack electrofishing is widely used to monitor stream trout populations throughout the world. Monitoring of the NSW trout populations has adopted international best practice and scientifically rigorous techniques which will allow comparison across years and to previous survey data from NSW streams.
  - id: counting # need a unique id for each slide, don't use numbering
    background_url: vaki.jpg #file url
    background_gradient: "to top, rgba(0,0,0,0.6) 30%,rgba(0,0,0,0) 60%" # add in CSS gradient
    text_template: "third" #location of text
    text_layer_class: "bottom block " #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "block-content"
    text_animation: fly-in-left
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      Stream monitoring forms just one component in how the status of the NSW trout fishery will be being monitored. Other monitoring techniques already being developed or deployed include:

      - Fish counters (e.g., VAKI river watch for stream fish, hydroacoustic biomass estimates)
      - Angler surveys
      - Citizen science
  - id: programs # need a unique id for each slide, don't use numbering
    background_url: stream-grass.jpg #file url
    background_gradient: "to top, rgba(0,0,0,0.6) 30%,rgba(0,0,0,0) 60%" # add in CSS gradient
    text_template: "third" #location of text
    text_layer_class: "bottom block " #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "block-content"
    text_animation: fly-in-bottom
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      The NSW trout monitoring programs will allow managers to track how the fishery is going and where possible make improvements. However, trout populations vary widely and fluctuations in populations are normal in fish populations and trout are particularly good at responding to improvements in their environment.
  - id: cta # need a unique id for each slide, don't use numbering
    background_url: trout-in-hand.jpg #file url
    background_gradient: "to top, rgba(0,0,0,0.6) 30%,rgba(0,0,0,0) 60%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-bottom  block " #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "block-content offset-bottom-15"
    text_animation: fly-in-right
    text_animation_delay: .2
    text_animation_duration: 1
    text_content: |- #type as Markdown---
      The **stream report cards** will provide a snapshot on the health of the fishery each year and allow fishers to be better informed on the performance of their fishery across the state.
    cta_text: Check Out the report cards
    cta_link: "#"
---

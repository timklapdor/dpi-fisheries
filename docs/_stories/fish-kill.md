---

layout:  amp-story
title: How Do DPI Scientists Use Fish Samples Collected from Fish Kills?  
subtitle:
slug: fish-kill
publish_date: July 2019
publisher: NSW Department of Primary Industries # The name of the story's publisher
publisher_logo_src: 00-26fifty.png #logo in 1x1 aspect ratio - .png
brand_logo: 00-dpi-rev.svg
background_colour: "#ffffff"
background_audio:
permalink: :title/index.html
cover:
  logo_placement: right
  background_image: cover.jpg
  background_video:
  filter: "brightness(.8)"
  gradient_overlay: "to bottom, rgba(0,0,0,0.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%"
slides:
  - id:  overview # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: aerial.jpg #file url
    background_brightness: .9 #brightness control 0-1
    background_blur: 0 #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "center-text" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class:
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      A fish kill is defined as *"any sudden and unexpected mass mortality of wild or cultured fish"*.

      There are many and varied causes of fish kills, and a large proportion are due to natural events.

      It is important that any fish kills are reported using the guidelines outlined on the NSW DPI Fish Kills webpage to enable DPI to determine the cause and extent of the kill and what actions might be required.
  - id:  reasons # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: causes-fish-kills.jpg #file url
    background_brightness: #brightness control 0-1
    background_blur: 0 #blur setting - px settings
    text_template: "vertical" #location of text
    text_layer_class: "block vertical-bottom" #styling classes
    text_type: "question" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-accent"
    text_animation: "fly-in-bottom"
    text_animation_delay: .5
    text_animation_duration: 1
    text_list_ordered: false #true for order lists, false for unordered
    text_list_bullet: # for unordered lists - disc, square,
    text_list_pre: |- #type as Markdown
    text_list_items:
    - ""
    text_content: |- #type as Markdown
      The range of causes of fish kills in NSW is shown in this diagram.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: collection.jpg #file url
    background_brightness: #brightness control 0-1
    background_blur: 0 #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-top" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "question bg-20-dpi-orange-d"
    text_animation: "fly-in-top"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      When fish kills occur and the cause and actions identified, NSW DPI scientists may request the collection of samples. These samples could be important for fish kill investigation or integration into other monitoring or research programs.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: collection-2.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur: 0 #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "no-padding vertical-top" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "question bg-20-dpi-orange-d"
    text_animation: "fly-in-top"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      These samples may also be collected for future work or so they can complement a range of other projects. In terms of recreational fishing, this may include assessing stocking effectiveness or looking for tag returns.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: disecting.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur: #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "vertical-bottom no-padding" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-blue"
    text_animation: "fade-in"
    text_animation_delay: 0
    text_animation_duration: 1
    text_content: |- #type as Markdown
      Following collection, fish will be placed on ice to prevent further decay and then transported back to the lab for dissection.

      DPI fisheries scientists and technicians will then identify and measure fish before removing the otoliths. DNA samples may also be collected at this point if the tissue is in a suitable condition.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_vid: dissecting.mp4 #file url
    background_brightness:  #brightness control 0-1
    background_blur: #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "vertical-bottom no-padding" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: "question bg-dpi-blue"
    text_animation: "fade-in"
    text_animation_delay: 0
    text_animation_duration: 1
    text_content: |- #type as Markdown
      A key sample collected from all fish will be the otoliths (ear bones). Otoliths are bone like structures that contain growth rings (much like a tree) and these rings can be used to age fish. The chemistry of these rings can also be examined to determine changes in habitat throughout the fishes life.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: otolith.jpg #file url
    background_brightness:  #brightness control 0-1
    background_blur:  #blur setting - px settings
    background_gradient: "to top, rgba(0,0,0,.45) 0%,rgba(0,0,0,.45) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "vertical-bottom " #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class: ""
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      The combination of age from otoliths and the length of that fish provides information on growth rates, population structure and other factors such as recruitment. When combined with otolith chemistry this can provide a wealth of information on factors such as movement between areas, mixing of populations and potentially important  spawning areas.
  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: cod.jpg #file url
    background_carousel: []
    background_brightness: .9 #brightness control 0-1
    background_blur:  #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.6) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "vertical-top" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class:
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      Murray cod collected from the Menindee fish kill were aged to a maximum of ~25 years for a ???cm individual. The maximum age for golden perch was ?? and silver perch??

  - id:  # need a unique id for each slide, don't use numbering
    auto_advance:
    background_img: river.jpg #file url
    background_carousel: []
    background_brightness: .9 #brightness control 0-1
    background_blur: #blur setting - px settings
    background_gradient: "to bottom, rgba(0,0,0,.45) 0%,rgba(0,0,0,0) 40%,rgba(0,0,0,0) 100%" # add in CSS gradient
    text_template: "vertical" #location of text
    text_layer_class: "vertical-top" #styling classes
    text_type: "block" #choose from list, block, blockquote, question
    text_div_class:
    text_animation: "fade-in"
    text_animation_delay: .5
    text_animation_duration: 1
    text_content: |- #type as Markdown
      Samples from fish kills are an important piece of information for DPI scientists. Therefore, make sure you report all fish kills using the protocols on the [DPI Fish Kills webpage](https://www.dpi.nsw.gov.au/fishing/habitat/threats/fish-kills){: .text-dpi-yellow}.
---

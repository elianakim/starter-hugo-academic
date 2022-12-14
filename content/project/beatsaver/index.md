---
title: "BeatSaver: Conducting Gestures to Metronome Beats"
summary: "Course project in KAIST EE595 Mobile Computing and Systems for Intelligent Living, Fall 2021"
tags:
  - AI
  - Mobile Computing
date: '2021-12-09T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/elianakim/EE595_BeatSaver'
url_pdf: 'uploads/projects/beatsaver/beatsaver_report.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<style>
body{
  font-size: 14pt;
  margin-left: 12%;
  margin-right: 12%;
  /* margin-bottom: -100px; */
}

@media only screen and (max-width: 768px) {
 body {
  font-size: 12pt;
  /* text-align:center; */
  margin-left: 0%;
  margin-right: 0%;
 }
}
</style>

### Project summary

A conductor is a messenger for the composer, and musicians’ duty is to fully understand the conductor’s messages through gestures and produce unified music in a musical ensemble. However, in many cases where the conductor is absent, musicians inevitably resort to their faint memories or abstract note-taking to infer the conductor’s instructions. To revamp this limitation, we propose BeatSaver, that converts conducting gestures to metronome beats. Musical details that a conductor instructed are recorded in beats and dynamics so that musicians can refer to even when they are practicing on their own. BeatSaver consists of Time Signature Classifier, Beat Detector, and Musical Dynamics Classifier, which we prove their effectiveness through real-world experiments. BeatSaver is lightweight and practical as it only utilizes Arduino Nano 33 BLE Sense attached to the conducting baton and an external server to extract the details after the practice session, making it easily applicable in the wild.

### Libraries and frameworks

- PyTorch

<span style="color: gray">
<i>This is done as a course project in KAIST EE595 Mobile Computing and Systems for Intelligent Living, Fall 2021.</i></span>
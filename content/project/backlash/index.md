---
title: Virtual Sensors for Detecting Backlash in Industrial Robots
summary: Development of techniques for early detection of backlash-related issues in robots, starting from available measurements.
tags:
  - Virtual sensor
  - Backlash
  - Industrial robots
  - Industrial collaboration
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Simulink model of the system. The main blocks of the system and their interconnections are showed in (a), while details about motor and link blocks are reported in (b) and (c) respectively. Taken from Giovannitti et al., 2022.
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Gear backlash is quite a serious problem for industrial robots, as it typically causes vibrations and impairs positioning accuracy. Backlash estimation allows targeted maintenance interventions, preserving robot performances and avoiding unforeseen equipment breakdowns. However, a direct measure of the backlash is hard to obtain, and dedicated auxiliary sensors are required for proper measurements.

This project, developed in collaboration with [COMAU](https://www.comau.com/), aims at developing a method for estimating backlash in robotic joints that does not require the installation of additional devices. The method only relies on data gathered from the motor encoder, which is always present in a robotic joint. The approach is based on the observation of a characteristic vibration pattern arising on the motor speed signal when backlash affects the joint transmission. By observing the amplitude of this vibration, information related to the entity of the backlash in the joint can be gathered.

Experimental results on both simulated and real-world data show that the method is viable and robust to noise. The approach is cost-effective, fast, and easily automatable, therefore convenient for the industrial world.

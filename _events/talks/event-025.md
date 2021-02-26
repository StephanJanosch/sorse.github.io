---
affiliations:
- index: 1
  name: Harvard University, Faculty of Arts and Sciences Research Computing (FASRC),
    US
author: &id001
  affiliation: 1
  email: sarahleinicke@g.harvard.edu
  is_speaker: true
  name: Sarah Leinicke
authors:
- *id001
- affiliation: 1
  name: Mahmood Shad
category: posters
date: 2020-09-09
doi: 10.5281/zenodo.4430821
language: English
last_modified_at: 2021-01-14
prerequisites: All experience levels are welcome.
title: Development of an Automated High-Throughput Animal Training Platform
show_in_calendar: false
recording_url: https://youtu.be/ENKp0BYUFlo?t=114
time:
  - - start: 2021-01-20T15:00:00Z
      end: 2021-01-20T16:00:00Z
registration_url: https://indico.scc.kit.edu/event/2295/
---

In traditional neuroscience laboratory research, training animals to execute sensorimotor tasks is time consuming, labor and resource intensive, and prone to human bias and error.  The Research Software Engineering team at Harvard University's Faculty of Arts and Science Research Computing (FASRC) has developed an automated training system pipeline that standardizes and automates animal training.  The pipeline consists of Teensy microcontrollers that monitor animal training events, RaspberryPis that orchestrate and log training instructions, PiCameras that record subjects, and open-source software, including a Vue web interface, a Flask server, and a PostGreSQL database.

The automated training system produces comparable learning rates to the traditional neuroscience model, with a fraction of the effort and at minimal cost.  In this lightening talk, we will review the hardware and software pipelines and describe how researchers use the tool.
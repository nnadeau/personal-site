---
abstract: ""
address:
  city: Montréal
  country: Canada
  postcode: H2X 1X2
  region: QC
  street: 51 Sherbrooke St W
aliases:
- /talk/python-montreal-2017
- /talk/domo-arigato-mr.-roboto-calibrating-robots-with-python/
date: "2017-10-01T00:00:00-04:00"
draft: false
event: 'Montréal-Python 67: Ultramodern Vintage - PyCon Canada Special'
event_url: https://montrealpython.org/en/2017/10/mp67/
header:
  caption: ""
  image: ""
highlight: true
location: Maison Notman House
math: false
projects: []
selected: false
summary: ""
tags:
- application
- calibration
- canada
- environment
- kinematics
- math
- production
- pybotics
- pycon
- python
- talk
- robots
- special
- ultramodern
- vintage
time_start: "2017-10-01T06:00:00-04:00"
title: 'Domo arigato, Mr. Roboto: Calibrating Robots with Python'
url_code: ""
url_pdf: ""
url_slides: ""
url_video: https://youtu.be/wgKoGA69YXQ
---

This talk was presented at [Montréal-Python 67: Ultramodern Vintage - PyCon Canada Special](https://montrealpython.org/2017/10/mp67/)

Modern robotic applications often rely on offline programming to reduce process downtime. In a virtual environment, robot application specialists may program, visualize, and test their robotic application before uploading it to the real production environment, saving time and costs. However, to achieve a high level of fidelity between virtual and production environments, the robot system must be accurate.

Unfortunately, even though most industrial robots are inherently precise (i.e., repeatable), they are not necessarily very accurate. One cost-effective approach to obtaining a more accurate robot is through calibration, where the actual kinematic and non-kinematic parameters of the robot model are identified and improved upon when compared to the nominal model. This talk introduces [`pybotics`](https://github.com/engnadeau/pybotics), an open-source Python toolbox for robot kinematics and calibration. The talk will feature the following topics:

- An introduction to modern industrial robotics
- Spatial descriptions and transformations
- Robot kinematics
- Robot calibration with `pybotics` + `NumPy` + `SciPy`

<iframe width="560" height="315" src="https://www.youtube.com/embed/wgKoGA69YXQ" frameborder="0" allowfullscreen></iframe>

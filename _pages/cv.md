---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/AcademicCV.pdf){: .btn .btn--primary}

Education
======
* M.Sc. in Computer Science and Computer Engineering (Scientific Programming), Moscow Institute of Physics and Technology (MIPT), 2024 - 2026
* B.Sc. in Applied Mathematics and Physics (Theoretical Physics & Astrophysics, joint with P. N. Lebedev Physical Institute (LPI) RAS), Moscow Institute of Physics and Technology (MIPT), 2020 - 2024

Work experience
======
* 2023 - Present: Graduate/Undergraduate Researcher
  * P. N. Lebedev Physical Institute RAS, Moscow, Russia
  * Advisor: Prof. Mikhail Lisakov (Pontifical Catholic University of Valparaíso)
  * Developed supervised, self-supervised, and transfer learning models in PyTorch for morphological classification of parsec-scale AGN jets in Astrogeo VLBI FITS images
  * Generated over 200,000 synthetic Blandford-Königl jet images, preprocessed more than 130,000 observations from the Astrogeo database, and trained a ResNet-18 with SIDDA domain adaptation, achieving 86% accuracy on real VLBI images
  * Master's thesis: "Domain Adaptation of Simulation Data for Morphological Classification of Relativistic Jets"
  * Bachelor's thesis: "Morphological Classification of Active Galactic Nuclei"

* 2021 - 2025: Undergraduate Researcher (hybrid)
  * Institute of Astronomy and Astrophysics, Academia Sinica, Taipei, Taiwan
  * Advisors: Dr. Hsien Shang, Dr. Ruben Krasnopolsky
  * Derived analytical solutions for the compressed ambient medium and stellar wind, matched across the contact discontinuity
  * Implemented an exact planar Riemann solver for the one-dimensional Euler equations to model shock structures
  * Studied self-similar stellar-wind bubbles and developed a numerical solver for the hydrodynamic system
  * Published the resulting work as a first-author article in PASP

* 2021 - 2024: Undergraduate Researcher (hybrid)
  * Special Astrophysical Observatory RAS, Nizhnij Arkhyz, Russia
  * Advisor: Prof. Grigorii Beskin
  * Investigated the transition between quasi-spherical and disc accretion for supersonic isolated stellar-mass black holes moving through molecular clouds
  * Analysed black hole population-synthesis data and obtained a joint probability map of black-hole mass and velocity

* 2021 - 2023: Undergraduate Researcher
  * Moscow Institute of Physics and Technology (MIPT), Dolgoprudny, Russia
  * Advisor: Prof. Vasily Beskin
  * Modelled the electric potential above the polar caps of orthogonal interpulse pulsars in the vacuum approximation, finding non-stationary secondary-particle production
  * Constructed synthetic mean radio profiles for eight pulsars while accounting for the non-axisymmetric plasma outflow
  * Developed algorithms for analysing the kinetic equation governing the neutron-star distribution function

* Apr. 2026 - Jun. 2026: Machine Learning Engineer, Voice Input Service (full-time, on-site)
  * Yandex, Moscow, Russia
  * Trained CatBoost models on audio-quality features to automate side-by-side evaluation and reduce human-assessment cost
  * Implemented and evaluated quantization-aware training for audio models
  * Analyzed firmware parameters of a new device and their impact on input audio quality

* Feb. 2026 - Jun. 2026: Computer Vision Engineer (part-time, remote)
  * Scientific Programming Centre, Dolgoprudny, Russia
  * Developed a real-time computer vision system for flotation monitoring: YOLOv11-based bubble segmentation from RTSP streams and extraction of bubble-size and distribution metrics
  * Implemented a module for recognizing digital readings from industrial camera footage
  * Built an IP camera control module for Hikvision devices using ISAPI and RTSP

* Jun. 2025 - Mar. 2026: Robotics Software Engineer (full-time, on-site)
  * Laboratory of Intelligent Robotics Technologies, MIPT, Dolgoprudny, Russia
  * Robotic Arm: Developed ROS2 software and a C++/pybind11 backend for communication with robotic-hand sensors and motors over RS485/Modbus
  * Warehouse Robot: Containerized and debugged an ORB-SLAM3 pipeline for real-time room mapping and robot localization against a prebuilt map, using gyroscope data for improved positioning

Skills
======
* Programming
  * Python: PyTorch, Lightning, CatBoost, scikit-learn, NumPy, SciPy, Astropy
  * C/C++: CMake, Boost, MPI
* Astronomy Software
  * Difmap, CASA, CARTA
* Languages
  * Russian (native)
  * Chinese (fluent)
  * English (fluent)
  * French (elementary)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* Co-Investigator (PI: R. Rao), Submillimeter Array Proposal 2024B-S045 - 4 hours awarded

Professional development
======
* IAIFI Summer Workshop, Massachusetts Institute of Technology, MA, Jul. 2026
* IAIFI Summer School, University of Massachusetts, MA, Jul. 2026
* The 20th Heidelberg Summer School, University of Heidelberg, Germany, Sep. 2025 - Attended a program on AI in Astronomy, including Domain Adaptation, Simulation-based Inference, and Generative Modelling
* Zwicky Transient Facility Summer School, University of Minnesota, remote, Jul. 2025 - Completed hands-on training in time-domain astronomy, covering ZTF Alert Stream Processing, and Rubin/LSST Filtering
* AstroAI Workshop, Center for Astrophysics \| Harvard & Smithsonian, remote, Jul. 2025 - Participated in lectures and tutorials on AI/ML in Astrophysics, including Image Reconstruction and Probabilistic Inference
* Submillimeter Array Interferometry School, Center for Astrophysics \| Harvard & Smithsonian, Hilo, HI, Jan. 2025 - Led a 3-member team in preparing an observing proposal for the pre-stellar core L1551-MC; trained in Interferometry, Calibration, and Imaging with CASA; analysed SMA & JCMT data of L1551-MC
* International Internship Pilot Program NSTC, Institute of Astronomy and Astrophysics, Academia Sinica, Taipei, Taiwan, Jul.-Aug. 2024 - Completed lectures on different fields of Astronomy, and conducted research on hydrodynamic bubbles (Zagorulia et al. 2025)
* Summer Program in Radio Astronomy, Pushchino Radio Astronomy Observatory RAS, Pushchino, Russia, Jul. 2022 - Co-organized a 10-student program, attended lectures on FRBs and VLBI, and mapped jets in 3C 273 and M87 using Difmap

Outreach
======
* 2024: Cosmic Wednesday @ MIPT.Radio - Founder & Podcast Co-host (6 episodes)

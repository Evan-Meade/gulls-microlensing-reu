# gulls-microlensing-reu
Collection of public presentations and reports related to my 2020 NSF-funded REU at LSU; worked under Dr. Matthew Penny

[Evan Meade](https://github.com/Evan-Meade), 2020

*Project completed as part of a Research Experience for Undergraduates, sponsored by the National Science Foundation under grant **NSF PHY-1852356***

## Presentations

* [**LSU Physics REU 2020 Colloquium**](https://youtu.be/9WO6SxuDR3k) - July 31, 2020
* **UT Dallas Society of Physics Students Colloquium** - September 2, 2020

## Abstract

Nancy Grace Roman Space Telescope is NASA’s next flagship astrophysics mission, slated to follow the launch of the James Webb Space Telescope. One of Roman’s primary missions is to conduct a wide-field microlensing survey toward the Galactic bulge, in order to study cold exoplanet demographics (>1 AU). Roman’s Wide Field Instrument will be observing in the infrared band, covering a field 100 times larger than Hubble Space Telescope, though at a similar resolution. Roman will observe the same field continuously, every 15 minutes for 72 days at a time. While Roman provides better resolution than can be achieved from the ground, its point spread function (PSF) will be undersampled, making resolution of stars in the dense Galactic bulge starfields challenging. In this project, we adapt and expand upon the GULLS codebase--originally developed to simulate time-series microlensing data--to simulate imaging and subtraction of dithered Roman images. Dithering is the process of taking multiple exposures at small sub- or super-pixel offsets in order to recover sub-pixel resolution and fully resolve the point spread function of the instrument. This technique allows higher spatial resolution images to be produced when images are combined, but can lead to larger systematic photometric errors in individual time-series data. We aim to quantify the systematic noise induced by dithering when Roman images are analyzed using standard photometric reduction packages, and investigate ways to mitigate them. We will present a preliminary analysis of the photometric reduction of simulated Roman data using the difference imaging package ISIS. Code developed during this project has been added to the GULLS codebase and will be used as part of a pipeline for continued simulation and design of Roman. The techniques we develop for minimizing systematic photometry errors may be adopted by the real Roman microlensing survey pipeline.

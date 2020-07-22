


<h1> 2D ultrasonic phased arrays for quantitative characterisation of complex defects </h1>
By Jerzy Dziewierz

A thesis presented in fulfilment of the requirement for the degree of Doctor of Philosophy, 2015

* TOC
{:toc}

# Abstract

Ultrasonic inspection can be considered as one of many ways the technical system - installation or vehicle - can be made economical and safe. 

Contemporary ultrasonic systems are capable of detecting a wide variety of mechanical defects and flaws that may or may not affect the operation of a given product. Ultrasonic testing techniques are widely accepted for quality control and material testing. Moreover, the technology is proven, well-understood and widely used. 

Upon detecting a flaw, a decision has to be made to ensure the component is fit for the purpose: is the flaw acceptable or is repair of the given part or its replacement? 

Here, 2D ultrasonic phased arrays hold promise to quickly deliver detailed, 3D resolved information about the extent and nature of the flaw. This information can then be used to develop and justify the technical and economic decision concerning the existing state of the product. In effect, an opportunity exists for significant cost savings by using ultrasonic 2D phased array systems for defect characterisation.

The interest of the work is to establish a process of designing and manufacturing of piezoelectric, 2D phased array ultrasound probes for application in non-destructive evaluation of materials. Furthermore, implementation of practical signal processing method is investigated. 

In the first part of the work the sensor mechanical and electrical design is addressed. The properties of piezoelectric ceramic composite materials are studied. Detailed numerical models have been used to analyse conditions required for crafting materials of desirable properties.

A novel technique has been demonstrated that allows design of well-behaved triangular cut piezoelectric composite. Built into a single array element (of hexagonal shape by taking 6 triangular pillars) this new composite exhibits properties comparable to a reference rectangular composite (sensitivity of 0.60nm/V for hexagonal, 0.62nm/V for square; and inter-element crosstalk of -21.2dB for hexagonal and -21.9dB for square element). This composite then allows building of compact, dense-layout2D phased array transducers with hexagonal or sparse element layout.

The benefits of hexagonal element layout over classic, rectangular layout have been analysed theoretically and showed to be beneficial. Importantly, using hexagonal elements enables increasing the aperture of individual array elements by approximately 10% without the corresponding drop in acceptance angle. This in turn allows a commensurable rise in the sensitivity of the sensor or alternatively, reduction in array element count for a given overall array aperture by **over 20%** without the corresponding drop in the image quality measurements/levels. 

In the second part of the work, the problem of high output impedance of the miniature ultrasonic sensor is addressed by means of an in-probe miniature signal conditioning circuit. This improved the response amplitude of the element by 36dB and **shortened its impulse response by a factor of 1.6**. The novelty and practical benefit in this case lies in the fact that no high power components are needed in the probe body. 

In the third part of this work, an emerging General-Purpose Graphics Processing Unit (GP-GPU) computer architecture is considered for the opportunities it offers to rethink the implementation of algorithms typically used in ultrasonic signal processing. Single-way beamforming, and two-way TFM and PCF beamforming have been developed for execution on the new platform, and show increase in performance of over 930 times compared to CPU processor. 

This software platform has been further enhanced by a new approach to solving the refracted ray Time of Flight problem in a way that is particularly well suited for this architecture. This resulted in a further increase of performance, i.e. **56x over the best published result** found in the literature. The unprecedented performance and low cost of this new approach enables industrial deployment of advanced beamforming methods, as well as building of practical CAD tools for engineering and education.

# Chapters 
Chapter 1. Introduction

Chapter 2. Design of piezoelectric ceramic composite

Chapter 3. Properties of hexagonal elements

Chapter 4. Triangular-Cut Piezoelectric Composite

Chapter 5. In-probe active impedance matching module

Chapter 6. GP-GPU accelerated ultrasonic CAD

Chapter 7. GP-GPU accelerated ultrasonic signal processing

Chapter 8. Concluding remarks and future work

Appendix A. Snell’s law of refraction and polynomial fit equations processed using Wolfram Mathematica

Appendix B. About a bug  in Matlab’s fminsearch

# Link to Full text

Download the full text pdf from github using [this link](https://github.com/jerzydziewierz/2D-ultrasonic-phased-arrays-for-quantitative-characterisation-of-complex-defects/blob/master/2015%20Dziewierz%20-%202D%20ultrasonic%20phased%20arrays%20for%20quantitative%20characterisation%20of%20complex%20defects.pdf)


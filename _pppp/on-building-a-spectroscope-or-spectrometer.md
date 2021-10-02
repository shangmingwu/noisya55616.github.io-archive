---
layout: pppp_post
mathjax: true
title: "On building a spectroscope or spectrometer"
date: 2021-09-29
categories: research
---

# Preamble

This post is to document my efforts into research on how I can go about building a homemade spectroscope or spectrometer, so that I can have a physical demonstration of spectroscopy and how it can be applied to the analysis of celestial objects. I outline the parts of a spectroscope that I'll need to construct or simulate, and ways that I will be able to do so.

# What does a spectroscope do?

A spectroscope is a tool that splits light into a spectra of the various wavelengths it's made up of, so that the spectrum of the light can be viewed and analyzed for information. A spectrometer is a type of spectroscope that is able to quantitatively measure the intensity of light at the various wavelengths that it's made up of, so that quantitative measurements and calculations can be made of the spectra, rather than just qualitative observations.

![Homemade spectroscope built using a paper tube and a CD](/school/pppp/assets/teacher-discussion-on-demonstration/cd.png)

Image 1. Homemade spectroscope, suitable for children to make, which is one of the possible routes I might take on this project. It uses a CD as a diffraction grating to break light into a spectrum. Primitive as it might seem, it's actually pretty good at displaying visible spectra and demonstrating concepts in spectrometry. From [https://buggyandbuddy.com/homemade-spectroscope/](https://buggyandbuddy.com/homemade-spectroscope/)

![Homemade spectrometer from an online tutorial](/school/pppp/assets/teacher-discussion-on-demonstration/spectrobox.png)

Image 2. More refined homemade spectrometer, which is made of wooden planks painted black. There is a slit in the front to allow light through: not visible is the camera in the back, which has a piece of broken DVD mounted in front of it as a crude diffraction grating, similar to the handheld spectroscope made of the cardboard tube. A project like this would allow me to make quantitative measurements and observe non-visible parts of the spectrum (such as ultraviolet and infrared light) but might be difficult to complete under the time constraint of this year. From [https://www.youtube.com/watch?v=MgogwcXUIoc](https://www.youtube.com/watch?v=MgogwcXUIoc)

![Aluminum plate used in the Sloan Digital Sky Survey](/school/pppp/assets/teacher-discussion-on-demonstration/plate.png)

Image 3. Optical fibres being plugged into a large aluminum plate: each hole in the plate represents the position of a celestial object that the Sloan Digital Sky Survey wishes to gather spectral data about, and the spectrometer is able to measure spectra from hundreds of different celestial objects at once. This is the kind of equipment that I'll be aiming to approximate and explain with my own crude home experiment. From [the Sloan Digital Sky Survey](http://www.sdss3.org/dr8/spectro/spectro_basics.php)

# How does the spectroscope work?

## Light slit or hole

In order to ensure that the spectra observed with the spectroscope is specifically of the desired light source, the amount of light allowed into the spectroscope has to be limited with something like a slit or a hole. Usually, a homemade device will use a slit due to ease of construction: a professional device like the ones used for the Sloan Digital Sky Survey will often use optical fibre cables that are plugged into holes in a plate (see Image 3). This slit or hole will ensure that only the desired light source is being fed to the spectrometer.

### How can I build this?

This part is pretty simple: all I'll need to do is make a thin slit or hole in whatever apparatus I construct so that the light coming in will be from only the source that I want it to be.

## Splitting light

The spectroscope needs to have some way to separate the light coming in into a spectrum, in a process also known as **diffraction**. This can be done in many different ways: prisms are quite well known as diffractors, but **diffraction gratings** are commonly used to split light into spectra as well, for various purposes.

![Album cover of "The Dark Side of the Moon" by Pink Floyd](/school/pppp/assets/on-building-a-spectroscope-or-spectrometer/pinkfloyd.png)

Image 4. Cover of the album "The Dark Side of the Moon", illustrating how the white light going into the side of the prism is diffracted into a spectrum.

![Diagram of diffraction occurring due to a diffraction grating](/school/pppp/assets/on-building-a-spectroscope-or-spectrometer/diffraction.bmp)

Image 5. Illustration of how a single incident beam of light is split into its spectrum, with the result being a rainbow emitted from the diffraction grating. From [OpenStax University Physics III](https://phys.libretexts.org/Bookshelves/University_Physics/Book%3A_University_Physics_(OpenStax)/Book%3A_University_Physics_III_-_Optics_and_Modern_Physics_(OpenStax)/04%3A_Diffraction/4.05%3A_Diffraction_Gratings)

### How can I build this?

A diffraction grating is much easier to obtain and use for this purpose than a prism will be. CDs and DVDs have many, many grooves in their surface that serve as diffraction grating - this is why you see a rainbow spectrum of colours whenever you look at light reflected off of a DVD or CD. I have a lot of these laying around at home, many of which I will be able to "repurpose" due to them already being damaged.

## Measuring light

A spectrometer, after splitting light into a spectrum will also measure the intensity of the various wavelengths of light in the spectrum, which will provide a quantitative view of the spectrum for better and more detailed analysis.

### How can I build this?

I might not have enough time to construct a full spectrometer apparatus along with the rest of my research, but if I were to try this, I could do this using a spare webcam with the diffraction grating directing the spectrum of light into its sensor, which could then be graphed and analyzed with software.

# Sources and further reading

[Camera spectrometer construction guide](https://www.theremino.com/wp-content/uploads/files/Theremino_Spectrometer_Construction_ENG.pdf)

[DIY spectrometer instruction video](https://www.youtube.com/watch?v=MgogwcXUIoc)

[Homemade spectroscope construction guide](https://buggyandbuddy.com/homemade-spectroscope/)

[4.5: Diffraction Gratings from OpenStax University Physics III](https://phys.libretexts.org/Bookshelves/University_Physics/Book%3A_University_Physics_(OpenStax)/Book%3A_University_Physics_III_-_Optics_and_Modern_Physics_(OpenStax)/04%3A_Diffraction/4.05%3A_Diffraction_Gratings)
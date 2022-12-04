---
layout: pppp_post
mathjax: true
title: "General secondary research"
date: 2021-10-24
categories: research
---

# Modelling the spectrum of a star

## The Rayleigh-Jeans law

The Rayleigh-Jeans law was a law that used to be used to describe the intensity of electromagnetic radiation from blackbodies (which would include objects like stars), but was a very flaw approximation because it predicted intensity that approached infinity as wavelength was reduced/frequency was increased—this was known as the **ultraviolet catastrophe**. We weren't being baked alive whenever we went outside, so this obviously wasn't matching our observations and experiences, and as time went on, better approximations were developed.

![Ultraviolet catastrophe graph comparison of Rayleigh-Jeans predictions vs. real observations](/school/pppp/assets/general-secondary-research/ultraviolet-catastrophe.png)

Comparison of observed behaviour of light intensity from stars vs. expected behaviour modeled by the Rayleigh-Jeans law. Image is in the public domain, from the [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Black_body.svg). 

## Later models for light emitted from a star

**Wien's approximation** was derived by Wilhelm Wien in 1896: it roughly describes high-frequency thermal emission (which is where the Rayleigh-Jeans law was failing) but did not accurately describe low-frequency thermal emission data.

$$B(\nu, T) = \frac{2h\nu^3}{c^2}e^{-\frac{h\nu}{kT}} \longleftrightarrow B(\lambda, T)=\frac{2hc^2}{\lambda^5}e^{-\frac{hc}{\lambda kT}}$$

**Planck's law** was derived by Max Planck in 1900, from the based on the behaviour of a blackbody radiator. It did match actual observations from stars, and resolved the ultraviolet catastrophe, along with being a pioneering concept of quantum mechanics and modern physics as a whole.

$$B(\nu, T) = \frac{2h\nu^3}{c^2}\frac{1}{e^{\frac{h\nu}{kT}}-1} \longleftrightarrow B(\lambda, T) = \frac{2hc^2}{\lambda^5}\frac{1}{e^{\frac{hc}{\lambda kT}}-1}$$

## The relation between Wien's approximation and Planck's law

Wien's approximation is fairly accurate when the frequency $$\nu$$ of the radiation being modelled is very large, and there is a very interesting mathematical basis for this. When $$\nu$$ is very large, $$h\nu \gg kT$$. Because of this, we know that $$e^{\frac{h\nu}{kT}}$$ will be quite large, and we can neglect the effect of subtracting $$1$$ in the Planck's law equation..

$$\begin{align*}
e^{\frac{h\nu}{kT}}-1\approx e^{\frac{h\nu}{kT}}\therefore B(\nu, T) &= \frac{2h\nu^3}{c^2}\frac{1}{e^{\frac{h\nu}{kT}}-1}\\
B(\nu, T)&\approx \frac{2h\nu^3}{c^2}\frac{1}{e^{\frac{h\nu}{kT}}}\\
B(\nu, T)&\approx \frac{2h\nu^3}{c^2}e^{-\frac{h\nu}{kT}}
\end{align*}$$

When we apply that approximation for very high frequencies, we actually recover the Wien's approximation from Planck's law.

## Making comparisons

I'd like to compare spectral data from real stars, graphed against predicted intensities from the Rayleigh-Jeans law, the Wien's approximation and Planck's law. It would demonstrate the importance of modern physics concepts (quantum theory/quantum mechanics) in accurately depicting and analyzing the world around us, as well as certain phenomena such as absorption lines from stellar atmospheres and possibly adjustments from the Doppler effect.

# Spectral analysis

Spectra of the light emitted by stars and other celestial objects can be analyzed by researchers to predict or infer properties of the object that emitted the light. The colour, chemical composition, movement and size of stars can all be predicted by analyzing measured light spectra.

## The temperature of a star and its peak wavelength

The maximum-intensity wavelength in the spectrum of light emitted from a star can be used to determine the temperature of the star.

### The Wien's displacement

The Wien's displacement law is derived from Planck's law, which describes the spectral radiance of a particular frequency of light coming from a blackbody (usually a star in this context) that has a particular temperature. Using calculus and a bunch of annoying math, it is possible to derive an expression that relates the maximum-intensity wavelength of light and the temperature of the star that emits it.

$$\lambda_{\text{peak}}=\frac{b}{T}$$

The constant $$b$$ is the Wien's displacement constant, which has a value of about $$2.8978\times10^{-3}\text{m}\cdot\text{K}$$. The higher the temperature, shorter the wavelength of the highest-intensity radiation emitted by the star—this makes sense, given the intuition that low wavelength (high frequency) radiation is higher-energy than long wavelength radiation.

## Spectral lines

When you display the continuous spectrum of light emitted from a star or celestial object, you'll often see absorption lines in the spectrum, which are dark lines in the spectrum that result from certain frequencies/frequency ranges of light being absorbed when passing through gas or dust clouds in space.

![Dark spectral lines in a light spectrum](/school/pppp/assets/general-secondary-research/spectral-lines.png)

Continuous light spectrum with dark lines resulting from the absorption of light. Image is in the public domain, from the [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Spectral-lines-absorption.svg).

### Stellar atmosphere compositions

These lines in the spectrum can tell you a lot about where the light came from. For example, when these spectral lines appear in the spectrum of light emitted from a star, those dark lines will usually be due to the absorption of certain light spectrums by the stellar atmosphere around a star.

- Example: the **hydrogen line**, or $$21$$-centimeter line, is a spectral line that appears due to the absorption of $$21$$-centimeter wavelength light by hydrogen atoms. Hydrogen is usually very abundant in the atmosphere around stars, so it appears very often.

### The Doppler effect

The Doppler effect describes how the wavelength or frequency of a wave changes when the source of the wave is moving relative to the observer of the wave.

![Diagram of Doppler effect changes on wavefronts of a wave for a moving sound source.](/school/pppp/assets/general-secondary-research/doppler.png)

Diagram of the different observer views of a moving wave source. From [Lumen Learning](https://courses.lumenlearning.com/astronomy/chapter/the-doppler-effect/).

The Doppler effect also applies to light waves, and because stars are often moving relative to us as the observers, their spectrum of light will often be shifted in comparison to their expected spectrum. This can be measured using the shifting of spectral lines from their expected positions in the light spectrum (e.g. when the spectrum of light is shifted, you can see that shift in the spectral lines that would normally appear at, say, the $21$ centimeter wavelength.). This offset from their expected positions can be used to determine the radial velocity of the light emitting object from us.

The phenomenon of **redshift** also arises from the Doppler effect. When stars move away from us as observers, their spectrum of light will be shifted due to the Doppler effect: specifically, all of the wavelengths of visible light will move towards the red end of the visible spectrum, because the Doppler shift of light from objects moving away from us will increase the wavelength of all of the light in the visible spectrum, making those stars look more red to us.

# Sources of information

- [The Theory of Heat Radiation](https://archive.org/details/theoryofheatradi00planrich/) - Max Planck
    - It's very convoluted, but it goes into great detail on Planck's derivation of Planck's law from the basic concepts of blackbody radiation (radiation emitted by a body based on temperature, such as that from a star).
- [Max Planck: the reluctant revolutionary](https://iopscience.iop.org/article/10.1088/2058-7058/13/12/34) - Helge Kragh
    - A very interesting article on the origins of quantum theory and quantum mechanics from the work of Max Planck.
- [The Wien approximation](https://www.chemeurope.com/en/encyclopedia/Wien_approximation.html) - ChemEurope
    - It describes some of the issues with the Wien approximation, and how it relates to Planck's law.
- [Deriving the Wien's Displacement Law from Planck's Law](https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Supplemental_Modules_(Physical_and_Theoretical_Chemistry)/Quantum_Mechanics/02._Fundamental_Concepts_of_Quantum_Mechanics/Deriving_the_Wien%27s_Displacement_Law_from_Planck%27s_Law) - Chemistry LibreTexts
    - As said by the title, shows how the Wien's displacement, used to relate the peak wavelength of a star's spectrum and its temperature.
- [Formation of Spectral Lines](https://opentextbc.ca/astronomyopenstax/chapter/formation-of-spectral-lines/) - OpenTextBC
    - An article describing the formation of spectral lines, especially the spectral lines formed by hydrogen atoms absorbing energy from light.
- [The Doppler Effect](https://courses.lumenlearning.com/astronomy/chapter/the-doppler-effect/) - Lumen Learning
    - An article on how the Doppler effect and the resulting shifts in spectral lines relate to the velocity of a star emitting radiation.
The file 'gaussian_beam_generation_v3_NA 1p3.nb' includes the Mathematica code used for focused Gaussian beam generation with an oil-immersion objective. The formulism is based on Chapter 3 in [Novotny, L., and B. Hecht. 2012. Principles of Nano-Optics. Cambridge University Press, Cambridge].

The input of this code is the numerical aperture (NA), index of the air n_1, index of glass n_2, aperture filling ratio f_0, wavelength λ_0, and radius of the spherical boundary that the Gaussian beam is mapped to after being focused. 

This code exports six files describing the mapped electric field (amplitude and phase of the 3D components) of the focused Gaussian beam at a spherical boundary. Those electric fields are expressed in terms of (ρ, φ), where x=ρ cos⁡φ and y=ρ sin⁡φ.
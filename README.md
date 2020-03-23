# covid19-R0
In this notebook we extrapolate data from Wuhan, China, in order to compute the  𝑅0  of Covid19 with Bayesian estimation, 
using the PyMC3 library.

Since  𝑅0  depends on social concentrations of the population that an epidemic targets, it is challenging 
to apply it to different populations. Nevertheless, an upper and lower bound on the epicenter of the epidemic 
provides us with an estimate of the contagiousness of the virus, which is higher than the flu or SARS. 

This data was available early on in the epidemic and this extrapolation could have easily been carried out by 
government agencies throughout, so that countries could have been better prepared for what they're going through now.

I would like to thank my TA, Feng Huang, for pointing me to the Chinese data and for the idea of the notebook as homework.

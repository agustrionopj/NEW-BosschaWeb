+++
title = "Exoplanet WASP-74b Transit Observation"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = ""

date = 2016-11-17T05:53:24+07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin"]

# Is this a featured post? (true/false)
featured = true

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["exoplanet", "internal"]
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

An exoplanet is a term used for a planet that orbits a star apart from our Sun. Up until now, more than 3400 exoplanets have been found and confirmed. There are a lot of methods to detect the existence of a planet in another star. The easiest and most used method is (astronomical) transit. Exoplanet transit is a phenomenon when an exoplanet passes directly between a star and the observer, resulting in a dimming of the star’s light (just like an eclipse or Venus/Mercury transit). This dimming, then, can be detected as an indicator of the existence of an exoplanet. 

{{< figure src="ilustrasi_transit.png" title="Illustration of an exoplanet transit (credit: www.nasa.gov)" >}}

One of the things that we do, here on Bosscha Observatory, is looking for a new exoplanet and also confirming the existence of (already found) exoplanets. We presented an observation result of WASP-74b exoplanet transit from our site. This exoplanet was observed with the Planewave CDK 14” (f/7.2) and CCD detector FLI Proline 11002. 

WASP-74b is an exoplanet that orbits around a star with 9.7 magnitude, which makes this system the brightest planetary system ever observed in the southern hemisphere. This (exo-)planet was found using the transit method by the WASP team and confirmed with further radial velocity measurement. The discovery of this exoplanet is explained well by Coel Hellier (2014). Planet WASP-74b has a mass of 0.95 times Jupiter’s and a radius of 1.56 Jupiter's, orbiting a F9 class star with a mass of 1.48 times Sun’s and a radius of 1.64 times Sun’s, with a period of 2.1378 days.

Light curves during transit as shown in the plot below are obtained after photometric data reduction. Of the two transit light curves (interval of 2 days) obtained, only one is displayed (results on 28 July 2016).

{{< figure src="lightcurve_wasp-74b.png" title="Light curve of WASP-74b" >}}

The visible changes in the brightness of the star, its drop and rebound, indicate the existence of objects that block the starlight, in this case, the planet WASP-74b that is passing in front of the star. This transit data then can be processed to obtain physical parameters of the planet. The most important parameter is the ratio between the radius of the planet and the radius of the star.

Although the light curve looks pretty flat, it is still possible to have data contamination (noise) that can come from the instrument, the star itself (e.g. star activity), or the air mass in our atmosphere. Red noise like those can be eliminated if we know the source of the noise. After removing the correlated noise (known as the detrending process among exoplanet observers), a new fitting can be performed to obtain the physical parameters of the planet. In fact, it is very difficult to directly eliminate this noise. To simplify the case, the de-trending and fitting process is carried out together by simplifying the correlated light curve model (which is applicable for short transit data). The shape of the light curve from shortly before until shortly after transit is modelled with a curved shape (quadratic equation) and then dimming effect due to the transit of the planet ($F_\mathrm{ratio}$) is added.

$$
  \Delta m = A - 2.5 \log (F_\mathrm{ratio}) + B(t - \bar{t}) + C(t - \bar{t})^2
$$

This method is also carried out on <a href="http://var2.astro.cz/EN/" target="_blank"> the Czech Republic exoplanet transit observation data collection site </a>. The difference, in this work, the fitting was done with the Bayesian approach (i.e. <font color='red'>Markov Chain Monte Carlo</font> method or <font color='red'>MCMC</font>). For the transit model ($F_\mathrm{ratio}$), we applied the Mandel & Agol equation (2002); quadratic limb darkening, with the limb darkening coefficient parameterized following Kipping (2013) to facilitate advance prior.

The results of the fitting are shown in the following plot,

{{< figure src="featured.png" title="Light curve's fitting of WASP-74b" >}}

with the parameter values of the fitting results are shown in the following table (median + 1-sigma error taken from quantile 0.16 and 0.84).

{{< figure src="table1.png" width="400px" title="Fitting results of data to the model (Mandel & Agol + de-trending)" >}}

{{< figure src="table2.png" width="400px" title="Other parameters derived from the fitting results" >}}



The final *Posterior Density Function* (PDF) of the MCMC results after checking the convergence of parameters along with the "burning" and "thinning" process can be seen in the following plot.

{{< figure src="cornerplot.png" title="PDF from WASP-74b’s light curve MCMC process" >}}

We actually cannot be certain with the existence of a planet in a transit from the observation of light curves alone. It could be a (periodical) decrease in starlight intensity due to other physical things, for example, if this star is a close double star whose orbit happens to experience very little digging (eclipsing binary) which produces a light curve similar to the transit of a planet. Confirmation of whether the decrease in starlight intensity is caused by a transit of a planet or not can be done by observing radial velocity (this has been done by the WASP team that discovered the planet) or by observing transit in various special filters. Transit observations can also only constrain or limit the ratio between the radius of the planet to the star, as well as the ratio of semi-major orbits of the planet to the radius of the star (bright stars covered by large planets will produce changes in the same light flux as faint stars covered by small planets). This means that other datasets are needed to get the actual planet dimensions; for example the mass or radius of a star from observations using other methods.

If we use stellar-mass data of $1.48 \pm 0.12$ solar masses, the radius of WASP-74b can be derived from this observational data, which is $1.53 \pm 0.1$ Jupiter's radius. These results are still in accordance with the calculations of the WASP team, which is equal to $1.56 \pm 0.06$ Jupiter radius.

These observations prove that with the deteriorating sky conditions in Lembang due to light pollution, observations of exoplanet transit can still be done with the order of delta magnitude, $\Delta m = 0.01$ (for parent stars with a brightness of 9.7 magnitude). On the other hand, observations of radial velocity still need to be done to confirm the existence of this planet. Unfortunately, Bosscha Observatory does not have a high-resolution instrument (spectrograph) yet that can detect changes in radial velocity down to order below 100 m/s.

These observations and analyses were presented at <font color='red'>the International Conference on Mathematics and Natural Sciences (ICMNS)</font> held at Institut Teknologi Bandung on November 2nd and 3rd, 2016.

Data observations and reduction were carried out by Muhammad Yusuf (Research assistant, young crescent moon record-breaker observation and robotic telescope developer at Bosscha Observatory), while the analysis was carried out by Ridlo W. Wibowo (Research assistant, doctoral student in astronomy at ITB). 
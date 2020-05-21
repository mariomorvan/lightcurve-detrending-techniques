# Lightcurve detrending techniques

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 

## Cotrending
Where the shared systematics between all lightcurves are seeked (often using a subset).

### Singular Value Decomposition 
- [Kepler Presearch Data Conditioning I - Architecture and Algorithms for Error Correction in Kepler Light Curves] (https://arxiv.org/abs/1203.1382) (Stumpe et al 2012)
- [Kepler Presearch Data Conditioning II - A Bayesian Approach to Systematic Error Correction] (https://arxiv.org/abs/1203.1383) (Smith et al 2012)
	
### Principal Component Analysis 
- [A systematic search for transiting planets in the K2 data](https://arxiv.org/abs/1502.04715) (Foreman-Mackey et al 2015)
	
### Half-sibling regression
- [Removing systematic errors for exoplanet search via latent causes] (https://arxiv.org/abs/1505.03036) (Schölkopf et al 2015)
- [A Causal, Data-Driven Approach to Modeling the Kepler Data] (https://arxiv.org/abs/1508.01853) (Wang et al 2015)
- [Modeling confounding by half-sibling regression](https://www.pnas.org/content/113/27/7391) (Schölkopf et al 2016)

### Removal of astrophysical component
- [Detrending light curves using strictly periodic variable stars](https://ui.adsabs.harvard.edu/abs/2020AAS...23528703P/abstract) (Prsa and Horvat 2020)


## Single light curve detrending
Where the detrending is done independently for each target lightcurve. 
### Pixel decorrelation
- [EVEREST: Pixel Level Decorrelation of K2 Light curves](https://arxiv.org/abs/1607.00524) (Luger et al 2016)

	
#### ICA
- [Of `Cocktail Parties' and Exoplanets] (https://arxiv.org/abs/1106.1989) (Waldmann 2011)
- [A blind method to detrend instrumental systematics in exoplanetary light-curves](https://arxiv.org/abs/1503.05309) (Morello 2015)

	
### Gaussian Processes 
- [A Gaussian process framework for modelling instrumental systematics: application to transmission spectroscopy](https://arxiv.org/abs/1109.3251) (Gibson et al 2011)

### Auto-regressive
- [AutoRegressive Planet Search: Methodology](https://arxiv.org/abs/1901.05116) (Caceres et al 2019)
- [Detrending Exoplanetary Transit Light Curves with Long Short-Term Memory Networks](https://arxiv.org/abs/2001.03370) (Morvan et al 2020)

### Various
- [Wotan: Comprehensive time-series de-trending in Python](https://arxiv.org/abs/1906.00966) (Hippke et al 2019)


# Sotware links
- Kepler and Tess vaious pipelines: [https://heasarc.gsfc.nasa.gov/docs/tess/software.html](https://heasarc.gsfc.nasa.gov/docs/tess/software.html)
- Wotan: [https://github.com/hippke/wotan](https://github.com/hippke/wotan)

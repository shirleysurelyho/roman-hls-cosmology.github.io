---
layout: default
---

***

# Public Products

***

Our Science Investigation Team will release codes, products and artificial data sets, with the goals of building awareness of and broad support for the WFIRST dark energy program and inspiring the community to develop methods and carry out investigations that will maximize the cosmological return from WFIRST.

## A WFIRST module has been added to the GalSim package

GalSim is an open-source software for simulating images of astronomical objects (stars, galaxies) in a variety of ways. The bulk of the calculations are carried out in C++, and the user interface is in python. In addition, the code can operate directly on "config" files, for those users who prefer not to work in python. The impetus for the software package was a weak lensing community data challenge, called [GREAT3](http://great3challenge.info/). 

However, the code has numerous additional capabilities beyond those needed for the challenge, and has been useful for a number of projects that needed to simulate high-fidelity galaxy images with accurate sizes and shears. For details of algorithms and code validation, please see [Rowe et al. 2015](http://adsabs.harvard.edu/abs/2015A%26C....10..121R).

The GalSim sofware package including the WFIRST module is available [here](https://github.com/GalSim-developers/GalSim). The versions past v1.4 include a WFIRST module. This module will be periodically updated by SIT members as the WFIRST hardware and survey parameters are adjusted. The next update is planned for June 2017.

## Cosmological parameters forecast chains (last updated on 01/05/17)

Please find below some cosmological parameters MCMC chains corresponding to forecast for the current survey of the WFIRST High Latitude Survey, combining weak-gravitational lensing (WL), cluster count (CC) and redshift space distortions (GRS). These chains were computed using the CosmoLike software [Krause & Eifler 2016](https://arxiv.org/abs/1601.05779).

### Multi-probe cosmology forecasts (incl SN from both SN teams) with realistic systematics budget

The tightest constraints on cosmological models including cosmic acceleration, modifid laws of gravity, neutrino physics will come from a joint analysis of multiple cosmological probes. Figure 1 shows the forecasted constraints of "traditional" single probe analyses for clusters (yellow), BAO+RSD (red), and weak lensing (green) and a multi-probe analysis that utilizes these and several other observables that can be extracted from the data: galaxy-galaxy lensing, photometric galaxy, cluster weak lensing, clustering, SN from WFIRST (forecasts from David Rubin and Dan Scolnic), SN from the existing Joint Lightcurve Analysis, existing Baryon Acoustic Oscillation information from BOSS, and CMB information from Planck. These contours show statistical errors only (shape/shot-noise and cosmic variance). Since multi-probe analyses are highly constraining they impose tight requirements on systematics control. Figure 2 compares the this statistical errors only (blue) to forecasts that contain a realistic systematics budget (green). These systematics include uncertainties in the estimation of galaxy shapes and redshifts (photo-z, spec-z), cluster mass calibration, galaxy bias, and intrinsic alignment. Uncertainties due to baryonic effects (SN and AGN feedback, cooling) are not included. It is critical over the coming years to study these uncertainties and to develop the capability to control these systematics at the level of WFIRST multi-probe analyses.

**Figure 1, [Chains](https://www.dropbox.com/sh/3apd0js4ncnwkcj/AADIQY3f73DG84FqVGZVWx_Ga/chains_Fig1_WFIRST_ini_vs_multi_pdf?dl=0)**:
![Figure 1:](/images/WFIRST_ini_vs_multi.png)

**Figure 2, [Chains](https://www.dropbox.com/sh/3apd0js4ncnwkcj/AAD_aeLCVlCRoh1gPz2453DNa/chains_Fig2_WFIRST_multi_probe_pdf?dl=0)**
![Figure 2:](/images/WFIRST_multi_probe.png)

***

### WFIRST modified gravity studies

While cosmic acceleration models have a relatively established parameterization, this is not true for modified gravity theories. Figures 3 and 4 show our first forecasts of modified gravity scenarios, where deviations from Einstein's GR are parameterized through \mu and \Sigma (please see [Joyce, Lombriser & Schmidt 2016](https://arxiv.org/abs/1601.06133) for a quick introduction. Figure 3 shows constraints on these modified gravity parameters for a Weak Lensing+Galaxy-galaxy Lensing+galaxy Clustering (photometric) analysis for the nominal WFIRST survey (2,200 deg.^2) and for 2 extended survey scenarios (5,000 deg.^2 and 10,000 deg.^2, respectively). Figure 4 shows the difference of this multi-probe case to a Weak Lensing only analysis.

**Figure 3, [Chains](https://www.dropbox.com/sh/3apd0js4ncnwkcj/AADW64Oo_ksSMsJBYw5Zip0Ia/chains_Fig3_WFIRST_extended_MG_pdf?dl=0)**:
![Figure 3:](/images/WFIRST_extended_MG.png)

**Figure 4, [Chains](https://www.dropbox.com/sh/3apd0js4ncnwkcj/AACRxHbP57_RcRkjg12oAAaYa/chains_Fig4_WFIRST_shear_vs_MP_pdf?dl=0)**:
![Figure 4:](/images/WFIRST_shear_vs_MP.png)

***




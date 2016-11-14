# note from *Imaging Live-Cell Dynamics and Structure at the Single-Molecule Level*

## Although there is diffraction limit, we can break it!

> the latter approaches include near-field scanning optical microscopy (NSOM) as well as far-field techniques such as stimulated emission depletion microscopy (STED), reversible saturable optical fluorescence transitions (RESOLFT)

Why?

> As first noted by Heisenberg ([Heisenberg et al., 1930](javascript:void(0);)), the position of a particle of subdiffractive size can be measured to much greater precision than its apparent width in a diffraction-limited microscope by finding the centroid of its fluorescence distribution

So

![Math Eq](http://www.cell.com/cms/attachment/2031170976/2048350211/si1.gif)

> where τ is roughly equal to the ratio between the background intensity and the peak signal intensity, σ is the standard deviation from the fit, a is the pixel size, and N is the total photon count. This equation reveals two fundamental approaches that we will discuss later to improve the localization precision: (1) applying fluorophores that emit more photons, and (2) designing imaging strategies that increase the signal-to-background ratio (SBR).

## Single-Molecule Localization and Tracking

### Location: a subset of individually labeled molecules are ***stochastically activated*** and imaged in a given frame

> A resolution of ∼20 nm was obtained in fixed cells when more than 2,000 molecules were resolved in one diffraction-limited region through **the serial photoactivation of fluorescent proteins or caged dyes** ([Betzig et al., 2006](javascript:void(0);)). The same principle was demonstrated in vitro with other photoactive fluorophores such as **PA-GFP ([Hess et al., 2006](javascript:void(0);)) or dyes with long-lived dark states** ([Rust et al., 2006](javascript:void(0);)) in the same year, albeit at much lower molecular densities. Eventually, a range of directly excited photoactive dyes was developed in different colors ([Dempsey et al., 2011](javascript:void(0);), [Heilemann et al., 2008](javascript:void(0);),[Heilemann et al., 2009](javascript:void(0);)).

The individual molecules are then localized(via the PSF, the point spread function) and these positions combined to provide a high-resolution map of molecular locations.

### Tracking: single-molecule detections are localized across successive temporally separated images to reconstruct of molecular diffusion trajectories through time and space

Years ago, 

> the FP-fusion protein expression needed to be extremely low to ensure that the molecules were sufficiently well isolated to be localized precisely. This strictly limited the number of events that could be measured.

But

> This problem was eventually circumvented by tracking many temporally separated subsets of photoswitchable FP-tagged molecules in live-cell PALM experiments (sptPALM) ([Hess et al., 2007](javascript:void(0);), [Manley et al., 2008](javascript:void(0);)). 

Unfortunately, 

> even the most photostable FPs do not emit enough photons to enable high-precision single-molecule localization for long track lengths over long times.

and it is important to note that 

> precise single-molecule localization requires the fluorophore to move slowly on a scale compared to the desired precision during the period of image acquisition. The minimum acquisition time is in turn influenced by several factors, including the imaging modality, camera sensitivity and speed, excitation intensity, background, and brightness of the dye. 
>
> These considerations make SPT techniques more suited for detecting ***slow diffusion events***.

## Fluorescence Correlation Spectroscopy


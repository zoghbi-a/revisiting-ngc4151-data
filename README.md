## Revisiting The Spectral and Timing Properties of NGC 4151

These papes contain the data and codes associated with the article entitled: **Revisiting The Spectral and Timing Properties of NGC 4151**, published in the Astrophysical Journal.

### Abstract
> NGC 4151 is the brightest Seyfert 1 nucleus in X-rays. It was the first object to show short time delays in the Fe K band, which were attributed to relativistic reverberation, providing a new tool for probing regions at the black hole scale. Here, we report the results of a large XMM-Newton campaign in 2015 to study these short delays further. Analyzing high quality data that span time scales between hours and decades, we find that neutral and ionized absorption contribute significantly to the spectral shape. Accounting for their effects, we find no evidence for a relativistic reflection component, contrary to early work. Energy-dependent lags are significantly measured in the new data, but with an energy profile that does not resemble a broad iron line, in contrast to the old data. The complex lag-energy spectra, along with the lack of strong evidence for a relativistic spectral component, suggest that the energy-dependent lags are produced by absorption effects. The long term spectral variations provide new details on the variability of the narrow Fe Kα line . We find that its variations are correlated with, and delayed with respect to, the primary X-ray continuum. We measure a delay of tau = 3.3+1.8 −0.7 days, implying an origin in the inner broad line region (BLR). The delay is half the Hβ line delay, suggesting a geometry that differs slightly from the optical BLR.


### Description
The analysis is organized into several python notebooks, which sometimes call outside functions either from the my [toolset package `aztools`](https://zoghbi-a.github.io/aztools/), [the psd/lag calculation package](https://zoghbi-a.github.io/plag/) or the specefic helper scripts: [`spec_helpers.py`](spec_helpers.py), [`timing_helpers.py`](timing_helpers.py) and [`fit.tcl`](fit.tcl).

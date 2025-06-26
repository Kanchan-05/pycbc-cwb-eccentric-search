# Detectability of eccentric binary black holes with matched filtering and unmodeled pipelines during the third observing run of LIGO-Virgo-KAGRA
Bhooshan Gadre<sup>1</sup>, Kanchan Soni<sup>2, 3</sup>, Shubhanshu Tiwari<sup>4</sup>, Antoni Ramos-Buades<sup>5</sup>, and Maria Haney<sup>5</sup>, Sanjit Mitra<sup>3</sup>

## Introduction ##

We present a study of the sensitivity of current gravitational-wave search pipelines to eccentric binary black hole (BBH) mergers using data from the third observing run of the LIGO-Virgo-KAGRA. The detection of BBH mergers with measurable orbital eccentricity would provide clear evidence for a dynamical formation channel for such systems. However, most existing searches are tuned for quasicircular mergers, due to challenges arising from increased waveform complexity and limited availability of efficient eccentric models.

Our study evaluates the performance of the matched-filter-based \texttt{PyCBC} and the unmodeled coherent WaveBurst (\texttt{cWB}) pipelines using injections of spinning eccentric BBH signals modeled with the multipolar, nonprecessing-spin waveform \texttt{SEOBNRv4EHM}. We find that \texttt{PyCBC} loses between 10–20% of sensitivity for sources with eccentricities above 0.2 at 10 Hz, highlighting the impact of template mismatch. In contrast, \texttt{cWB} exhibits a relative gain of ~10% in sensitivity for heavier systems (with chirp mass \mathcal{M} \geq 30M_\odot). However, it remains less sensitive than \texttt{PyCBC} for lighter binaries.


A preprint version of the paper is available on arXiv.
This release contains the injection campaign configuration files and search settings.

A preprint version of the paper is available on [arXiv](https://arxiv.org/abs/2405.04186).

## License and Citation

![Creative Commons License]()

This work is licensed under a 

We encourage the use of these data in derivative works. If you make use of the materials provided here, please acknowledge this project by citing the following reference:

```
@article{PhysRevD.110.044013,
  title = {Detectability of eccentric binary black holes with matched filtering and unmodeled pipelines during the third observing run of LIGO-Virgo-KAGRA},
  author = {Gadre, Bhooshan and Soni, Kanchan and Tiwari, Shubhanshu and Ramos-Buades, Antoni and Haney, Maria and Mitra, Sanjit},
  journal = {Phys. Rev. D},
  volume = {110},
  issue = {4},
  pages = {044013},
  numpages = {14},
  year = {2024},
  month = {Aug},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevD.110.044013},
  url = {https://link.aps.org/doi/10.1103/PhysRevD.110.044013}
}
```

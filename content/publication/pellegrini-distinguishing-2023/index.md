---
title: Distinguishing between- from within-site phase-amplitude coupling using antisymmetrized
  bispectra
authors:
- Franziska Pellegrini
- Tien Dung Nguyen
- Taliana Herrera
- Vadim Nikulin
- Guido Nolte
- Stefan Haufe
date: '2023-10-01'
publishDate: '2024-08-10T00:40:34.425315Z'
publication_types:
- preprint
publication: '*bioRxiv*'
doi: 10.1101/2023.10.26.564193
abstract: Phase-amplitude coupling (PAC) is a form of cross-frequency coupling in
  which the amplitude of a fast oscillation is locked to the phase of a slow oscillation.
  PAC has been proposed as a mechanism for integrating slow large-scale networks with
  fast-oscillating local processes in the brain. On a signal level, PAC can be observed
  in single time series, reflecting local dynamics, or between two time series, potentially
  reflecting a functional interaction between distinct brain sites. To investigate
  the role of PAC as a mechanism of brain signalling, it is important to distinguish
  these two cases. However, when mixtures of underlying signals are observed, between-site
  PAC can spuriously emerge even if the true interaction is only local (within-site).
  This problem arises in electrophysiological recordings where mixing occurs due to
  volume conduction or the presence of a shared electrical reference. To address this
  problem, we propose to estimate PAC using the anti-symmetrized bispectrum (ASB-PAC).
  It has previously been shown that the cross-bispectrum can be used to measure PAC
  while efficiently sup-pressing Gaussian noise, and that the anti-symmetrized bispectra
  vanish for mixtures of independent sources. However, ASB-PAC has so far not been
  used to assess the presence of genuine between-site PAC. Using simulations, we here
  investigate the performance of different algorithms to detect PAC in a mixed signal
  setting as well as the performance of the same methods to distinguish genuine between-site
  PAC from within-site PAC. This is done in a minimal two-channel setup as well as
  in a more complex setting that assesses PAC on reconstructions of simulated EEG
  sources. We observe that bispectral PAC methods are considerably better at detecting
  simulated PAC in the volume conduction setting than three conventional PAC estimators.
  ASB-PAC achieves the highest performance in detecting genuine between-site PAC interactions
  while detecting the fewest spurious interactions. Using the ASB-PAC could therefore
  greatly facilitate the interpretation of future PAC studies when discriminating
  local from remote effects. We demonstrate the application of ASB-PAC on EEG data
  from a motor imagery experiment. Additionally, we present an upgraded version of
  the free ROIconnect plugin for the EEGLAB toolbox, which includes PAC and ASB-PAC
  metriscs based on bispectra.
links:
- name: URL
  url: https://www.biorxiv.org/content/10.1101/2023.10.26.564193v1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

tags:
  - Neuroscience

# Summary. An optional shortened abstract.
summary: Using simulations, we investigate the performance of different algorithms in distinguishing between genuine between-site PAC and within-site PAC.

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Franziska Pellegrini
  - admin
  - Taliana Herrera
  - Vadim Nikulin
  - Guido Nolte
  - Stefan Haufe

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.biorxiv.org/content/10.1101/2023.10.26.564193v1.abstract'
url_code: 'https://github.com/fpellegrini/PAC/tree/master'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

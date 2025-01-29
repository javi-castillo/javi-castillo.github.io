---
title: 'Mapping Pb/Zn-stressed plant communities: challenges of centimetre- to millimetre-scale
  UAV sensing for training deep-learning schemes'
authors:
- Thomas JB Dewez
- Adrien Breton
- Marie De Boisvilliers
- Gaël Bellenfant
- Marion Houlès
- Florent Guiotte
- Bruno Roux
- admin
- Guglielmo Fernandez Garcia
- Sébastien Lefèvre
- Felix Kröber
- Thomas Corpetti
- Florian Delerue
date: '2023-06-01'
publishDate: '2024-12-29T17:29:25.104857Z'
publication_types:
- paper-conference
publication: Virtual Geoscience Conference
abstract: 'Plant interactions play a pivotal role in ecosystem functioning. In stressed
  ecosystems, dominant plants often mitigate environmental stress in their immediate
  vicinity enabling maintenance of low stress-tolerant species. In that case beneficiary
  plants are clustered around their benefactors. This process increases plant diversity
  and develops corresponding plant communities. Metals/metalloids rich environments
  challenge vegetation development making their remediation intricate. The ANR-funded
  SixP project investigates the role of facilitation in Zn/Pb contaminated sites as
  a potential tool for their remediation. Plant mapping is a key project component
  to discover clumped spatial distributions. For this, a set 24 459 plants spread
  over 352 m² , split in 24 distinct sampling patches were identified, located with
  differential GNSS and measured. That is 30 full man-days of effort. UAV acquisition
  could presumably ease the mapping endeavor in three ways: (i) surveying much larger
  surfaces, hence broadening statistical and environmental representativeness; (ii)
  archiving land cover state when the manual survey is performed; (iii) providing
  continuous explanatory variable layers such as topographic context and multispectral
  surface response to feed seemingly effortless deep-learning classification algorithms.
  This contribution means to highlight the challenges of providing accurate and trustworthy
  labels for training AI schemes. A lead/zinc mining district, in Sentein, central
  Pyrenees mountains (southern France) was active up until the 1960’s. Remaining toxic
  wastes act as stress control variable, while the vertical distribution of mining
  activities, over 1000 m of elevation, bring climate control on plant ecosystems.
  L’Avion Jaune company performed Uncrewed Aerial Vehicle (UAV) flights, before the
  growing season (march/june 2020) and at full growth (june/july 2020). Lidar was
  used for overview ground topography (with canopy top density ca. 50 pts/m²) and
  SfM-photogrammetry at two resolutions for land cover: 20 mm/pixel (RGB) before growth
  and 2-3 mm/pixel (RGB+near-infrared) at full growth season. Millimetric resolution
  is justified by metallic toxicity constraining dwarf plant development. Full growth
  mm-resolution covered 7 zones for a total of 1.34 ha (40 times the ground-truth
  surface), while overview cm-resolution data covered 36.6 ha, 1000 times the reference.
  The first lesson: differential-GNSS survey in mountain terrains is not trivial.
  No phone coverage meant no real-time corrections, nor accurate national geodesic
  network tie. A GNSS base station was freely deployed alongside a rover unit to broadcast
  real-time corrections. Base-to-reference-network post-processing tied surveys to
  IGN’s RGP network, but only with a limited accuracy (ca. 20 cm). Stationing a known
  benchmark with the base station would have improved accuracy. Fortunately, plant
  and UAV surveys were performed in a common spring-summer 2020 reference frame, with
  temporary UAV targets positioned by the plant-mapping teams. GNSS plant positions
  are coherent with UAV data to within 10-30 mm. The second lesson: producing UAV
  photogrammetric coverages at 2-3 millimeter pixels of plants is incredibly challenging.
  The UAV flew 10-m above ground to reach image resolution. But flying low strains
  photographic and photogrammetric processing to the limit. The UAV blew wind on the
  tiny gracile leaves and stems. Fast shutter speed of 1/1000 s counter-acted both
  motion blur and pixel ovalization due to UAV vibrations but imposed a wide aperture
  (f/3.5). This mitigated vignetting, refaction and diffraction issues of small apertures.
  Yet narrower apertures would have increased the depth-of-field, but at the cost
  of increasing image electronic noise to preserve shutter speed. Sensor sentivity
  was set at 200 ISO. While with these settings, plants were reasonably sharp, the
  wind shifted the position of mobile plant organs between photos. This challenged
  photogrammetric surface reconstruction and orthophotos mosaicking. Finally, RGB
  and Near-Infrared imagers were flown simultaneously, back-to-back to generate 4-band
  ortho-imagery. But with two points of view, even if only 8 cm apart, the base-line
  was sufficiently large to generate differential parallax between images, challenging
  orthorectification along elevated object edges. This means that RGB pixel signatures
  do not always match the underlying NIR signal depending on the local topography.
  The third lesson: training AI models for class (here species) segmentation requires
  a trustworthy training set. GNSS-tagged labels link a 1D position with a plant label
  and radius. In raster form, it is a label disk map. But the plant may not be exactly,
  at pixel scale, below the GNSS point, due to geometric imprecision. We innovated
  with a fuzzy edge labelling map to accounts for location uncertainty (Guiotte et
  al., in prep.) Finally, can trained models be transposed to different sites? ImageNet
  feature mapping clustered with t-SNE (Castillo-Navarro et al., 2022) maps image
  features to predict the chances of successful classification.'
links:
- name: HAL
  url: https://brgm.hal.science/hal-04113526

tags:
- Ecology
- Remote sensing
---

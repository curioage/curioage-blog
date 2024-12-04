---
title: Introduction to Dust
date: 2024-04-12
draft: false
module:
  mounts:
  - source: content/images
    target: content
genres:
- science
params:
  author: Vishal Kumar
tags:
- dust
- transport
---
# Introduction

## Dust and Sand[^1]

The terms dust and sand usually refer to solid inorganic particles that are derived from the weathering of rocks. In the geological sciences, sand is defined as mineral (i.e. rock derived) particles with diameters between 62.5 and 2000 µm, whereas dust is defined as particles with diameters smaller than 62.5 µm (note that the boundary of 62.5 µm differs depending on particle size classification schemes). In the atmospheric sciences, Dust is usually defined as the material that can be readily suspended by wind whereas sand is rarely suspended and can thus form sand dunes and ripples, which are collectively termed bedforms.


## Aeolian Process[^1]

The wind-driven emission, transport, and deposition of sand and Dust by wind are termed aeolian processes, after the Greek god __Aeolus__, the keeper of the winds.


{{ with .Resources.GetMatch "1.png" }}
  {{ with .Resize (printf "%dx%d r90" .Height .Width) }}
    <img src="{{ .RelPermalink }}" width="{{ .Width }}" height="{{ .Height }}">
  {{ end }}
{{ end }}




**Figure 1**: Dune types[^2]



[^1]: [Kok, J. F.; Parteli, E. J. R.; Michaels, T. I.; Karam, D. B. The Physics of Wind-Blown Sand and Dust. Reports Prog. Phys. 2012, 75 (10), 106901](https://doi.org/10.1088/0034-4885/75/10/106901)
[^2]: [Michael E. Brookfield, 2011. "Aeolian processes and features in cool  climates", Ice Marginal and Periglacial Processes and Sediments, I. P.  Martini, H. M. French, A. PéRez Alberti](https://doi.org/10.1144/SP354.16)

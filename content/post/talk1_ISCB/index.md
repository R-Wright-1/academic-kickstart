---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Aging of bacteria in biofilms, using an Individual-based model to study growth"
subtitle: "UCD Computational and Molecular Biology PhD Symposium December 2016 (Dublin, Ireland)"
summary: "UCD Computational and Molecular Biology PhD Symposium December 2016"
authors: []
tags: ["Talk"]
categories: []
date: 2013-06-06T21:58:12-06:00
lastmod: 2020-05-06T21:58:12-06:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: true

---
<i class="fas fa-file-pdf"></i>[Download slides](iscb_compress.pdf)&nbsp;&nbsp;&nbsp;&nbsp;


_Oral presentation (15 mins)_

{{< figure src="featured.png" title="" lightbox="true" >}}

<h2>Submitted abstract</h2></br>
<strong>Background:</strong> Aging has been defined as an accumulation of damage, or a loss of function, with increasing age. For bacteria, one strategy to cope with damage is asymmetric segregation of damage at division, so that the old pole cell inherits all of the damage and the new pole cell is rejuvenated. Another, often neglected, mechanism is to repair the damage and our previous computational modeling work has found that an optimal rate of repair is fitter than damage segregation in well-mixed environments. Here, we investigate aging in biofilms, the predominant mode of growth for bacteria, with the individual-based model iDynoMiCS. We introduced an adaptive repair strategy, with and without damage segregation, to the previously used damage segregation and fixed optimal repair strategies. These are investigated in a constant environment, a chemostat, and in biofilms and the damage is considered to be either toxic or inert.</br></br>
<strong>Results:</strong> In the constant environment, symmetric division combined with fixed optimal repair was the fittest strategy for toxic damage, and adaptive repair with segregation of damage was fittest for inert damage. In the chemostat, symmetric division combined with adaptive repair was the fittest strategy. For biofilms, the fittest strategy depended upon the initial spatial distribution of cells. Where cells of competing strategies were placed in two side-by-side blocks, asymmetric damage segregation without repair was the fittest strategy. Where cells were placed in an alternating manner, the fittest strategy was symmetric optimal fixed repair.</br></br>

<strong>Conclusions:</strong> Adaptive repair was not always the fittest strategy, as was expected, because the model did not allow protein previously allocated to repair machinery to be redistributed to growth machinery even when repair was no longer beneficial, therefore hindering growth.
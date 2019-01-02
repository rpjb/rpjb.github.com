---
layout: paper
author: robert barretto
description: natural enzyme to tackle the great pacific garbage patch
categories: science
image: /img/posts/2000-01-01-paper-plastic-degrading-enzyme_c0o7vy.png

title: A bacterium that degrades and assimilates poly(ethylene terephthalate)
authors: Yoshida
lab: Oda
pmid: 26965627
type: translational
date: 2019-01-01
---

### Need for an industrial process to break down plastics

Plastic is very useful because of its ability to resist degradation.  But because of this property, disposal isn't trivial.  In 1997, Charles Moore was on a yacht in the Pacific Ocean and found a large swath of ocean littered with plastic debris (see [National Geographic](https://news.nationalgeographic.com/2018/03/great-pacific-garbage-patch-plastics-environment/))

![https://news.nationalgeographic.com/2018/03/great-pacific-garbage-patch-plastics-environment/](/img/posts/2000-01-01-paper-plastic-degrading-enzyme_vw2sh4.png)

From the Yoshida paper:
> About 56 million tons of PET was produced worldwide in 2013 alone, prompt- ing further industrial production of its monomers, terephthalic acid (TPA) and ethylene glycol (EG), both of which are derived from raw petroleum.

### Screening for a bacterial that can break down PET

To find new bacterial species that can metabolize PET, they ran a simple screen of 250 different environmental samples (containing entire biomes of species) and looked for signs of PET degradation.  

![Breakdown](/img/posts/2000-01-01-paper-plastic-degrading-enzyme_c0o7vy.png)

This is a pooled screen, so they could find a sample that did degrade PET, and then iteratively dilute to identify a causative species.  This is easier said than done, because the ability of a single species to succeed in PET metabolism potentially could dependent on other species being present.

They called the target species: Ideonella sakaiensis

### Mining the genome for an enzyme that can hydrolyze PET

To find candidate genes, use the following pipeline:

- assemble a draft sequence
- identify all open reading frames
- look for ORFs with similarities to known PET hydrolases. 
- create recombinant proteins
- test for function in cell-free systems

The nice feature of this PETase enzyme, is that it is secreted by Ideonella sakaiensis, so must be able to function in a cell-free assay.

### Transcriptional upregulation of TPAase

Lastly, one might expect that if PET is a nutrient source for Ideonella sakaiensis, that this bacterium would create more PETase in the presence of PET and not in the presence of an unrelated nutrient source.

![Upregulation](/img/posts/2000-01-01-paper-plastic-degrading-enzyme_jx5cr3.png)

### What can one do next

Now that there is a good template for what a good PETase looks like genetically, it would be interesting to mine the genomes for better functioning PETases.  

This could be quite useful for industrial cleanup purposes.  Would be nice if one could further engineer a kill switch for the enzyme, as one wouldn't want this enzyme out in the wild.

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Understanding microbial community dynamics to improve optimal microbiome selection"
subtitle: "<b>Robyn J. Wright</b>, Matthew I. Gibson and Joseph A. Christie-Oleza"
summary: "<b>Robyn J. Wright</b>, Matthew I. Gibson and Joseph A. Christie-Oleza (2019) <em>Microbiome</em>"
authors: []
tags: ["Publication", "View online"]
categories: []
date: 2019-06-06T21:58:12-06:00
lastmod: 2020-05-06T21:58:12-06:00
featured: true
draft: false

links: 
- icon: file-pdf
  icon_pack: fas
  link: files/publ1.pdf
  name: Download paper
- icon: binoculars
  icon_pack: fas
  link: https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-019-0702-x
  name: View online
- icon: biorxiv
  icon_pack: ai
  link: https://www.biorxiv.org/content/10.1101/474742v1
  name: Preprint

image:
  caption: ""
  focal_point: "Center"
  preview_only: false

---
<i class="fas fa-file-pdf"></i>[Download paper](publ1.pdf)&nbsp;&nbsp;&nbsp;&nbsp;
<i class="fas fa-binoculars"></i> [View online](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-019-0702-x)&nbsp;&nbsp;&nbsp;&nbsp;
<i class="ai biorxiv"></i> [Preprint](https://www.biorxiv.org/content/10.1101/474742v1)


Published: _June 2019_
</br>
In: _Microbiome_

<h2>Summary</h2>
As many of you reading will know, one of my central PhD aims was to find out whether plastics are being degraded in the oceans. You will often hear that plastics could take hundreds of years to break down, and people are therefore increasingly looking to the microbes - and biodegradation of plastics - to find a solution to this problem. But if they take such a long time to break down, how can we look for the degradation of materials such as plastics - which are a type of polymer (a substance that has a molecular structure consisting of a large number of identical units bonded together)? In order to do that, we first needed to have a more labile (easier to degrade) polymer to understand degradation. We chose chitin - it is the most abundant natural polymer in the oceans (and second most abundant on earth, the most abundant is cellulose), it makes up the shells of organisms like crabs, shrimps and lobsters, and, most importantly for us, it is readily degraded by marine microbes and the enzymes (molecules that act as biological catalysts) used for this are already well characterised. Because we already know that chitin is degraded in the oceans, we wanted to find out whether we could do anything to speed up the degradation process and to look at the microbial communities that were doing this degradation: do they carry out this degradation at a constant rate? Do we have a whole community of chitin degraders? Do they work together, or are they competing with each other?</br></br>

To try to speed up the chitin degradation, we applied the method of artificial selection - what we use to produce different species of dog, or improve the yield of crop plants - to whole microbial communities. To do this, we grew 30 different cultures of microbial communities with chitin as the only source of both carbon and nitrogen. After we have grown these communities for nine days, we measure the activity of chitinases (enzymes that degrade chitin). We then take the three communities with the highest chitinase activities (these should be the fastest at degrading the chitin) and combine them to inoculate another 30 cultures. This is repeated up to 20 times (which would be over 20 generations), and the aim is that at the end we should have microbial communities that are both fast and efficient at degrading chitin. So that we could compare this with a control, we also did this with a second set of 30 communities each time - this time, instead of taking the three communities with the highest chitinase activities, we just took three communities at random and used these to inoculate the next generation (this imitates natural selection). We call the set of communities where we take the highest chitinase activities the positive selection and the set where we take the three communities at random the random selection. 

{{< figure src="selection.png" title="Depiction of the artificial selection of whole microbial communities, described above (modified from Figure 1 of the paper for an article that I wrote for the Biological Sciences Review, a science magazine aimed at 16-18 year olds)" lightbox="true" >}}

To be able to compare our two treatments, we calculated the difference between our positive and random selections at each generation (each time we selected the three best communities). Intriguingly, we found that after a number of generations, we weren't really seeing that the positive selection had higher chitinase activities than the random, and in fact, at a number of points, the random actually had higher chitinase activity than the positive selection (the green line in panel A of the below figure). In order to try to find out what was going, we measured the chitinase activity within a generation - within the nine days that we grow the communities for. In some preliminary work, we'd found that nine days was the optimal amount of time to grow my communities for, but we found that by generation 15, this optimal time had been reduced to four days (panel B in the below figure). We decided to carry on with the selection that grew communities for nine days between selection events, but to also grow communities for only four days between selection events for the remaining five generations (the orange line in panel A of the below figure). When we did this, we found that initially the chitinase activity increased in the positive selection, but by generation 20 the activity had again fallen below that of the random selection. When we checked the chitinase activity within the four days of incubation at generation 20, we found that the optimal incubation time had again been reduced - this time to two days (panel C of the below figure)!

{{< figure src="Figure 2.png" title="The chitinase activity that we measured (A) across all 20 generations, (B) within generation 15 and (C) within generation 20 (Figure 2 in the paper)" lightbox="true" >}}

Across the whole experiment, we had saved the DNA from each community - freezing it until we were ready to use it. So to try to figure out why the optimal incubation time kept being reduced, we sequenced all of the microbial communities. When we do this, we find out the sequence of an organisms' DNA - the order that the nucleotides (molecules that make up DNA) appear in - and we can use this to tell us about a specific gene that we're interested in. In this case, we sequenced two genes - called the 16S and 18S rRNA genes - which have both evolved relatively slowly and are therefore highly conserved between closely related species. They can therefore be used to identify the microbes in our communities, with the 16S gene being used to identify bacteria and the 18S gene being used to identify the eukaryotes. When we know which species are in our communities, we can use this to predict how they might grow and what they might be capable of, based on what we know about other similar species. We process this data computationally and use it to see how abundant each species is in our community (by determining the relative abundance of the sequences that we have that are made up by each species). </br></br>

When we did this, we found that there were some very clear patterns within the four days of incubation, and the abundance of certain species was correlated with chitinase activity. The figure below shows us the bacteria (16S rRNA gene) and eukaryotes (18S rRNA gene) that are in our communities across these four days - each colour in panel B identifies a different species, with each species labelled 'ASV' (this stands for amplicon sequence variant, but these numbers are just used as an identified) with the Latin name for the species that it is closest to shown next to this. Sometimes the DNA sequence that we get for a species is similar to more than one known organism, and in these cases we just show the lowest classification that we can for this. Panel A just shows a measure of the diversity of the communities. What we can see from this is that the 16S ASVs 3 and 4 (<em>Thalassotalea</em> and Cellvibrionaceae) are very likely to be correlated with chitinase activity - we expect the measured activity to lag slightly behind the abundance of these organisms, and these two are very abundant on days one and two (activity is highest on days two and three) and then they decrease strongly in abundance on days three and four. At the same time, the 18S ASVs 1 and 2 (both <em>Cafeteria</em>) increase strongly in abundance between days one and four. 

{{< figure src="Figure 3.png" title="Relative abundance of bacteria (left) and eukaryotes (right) across four days of incubation at generation 20 (Figure 3A and 3B in the paper)" lightbox="true" >}}

These findings actually fit really nicely with what we already know about microbial community ecology - we often see an initial colonisation phase, characterised by an abundance of organisms that are just good at attaching to particles. We then see a selection phase, characterised by high abundances of organisms that are actually able to degrade the chitin, and then a succession phase, where these degraders are overtaken by cheaters, grazers and viruses. These "cheaters" would be the organisms that can't degrade the chitin themselves, but are able to benefit from those that do by using the sub-products of the chitin degradation. 

{{< figure src="cheaters.png" title="Microbial community succession (the white blobs show the polymer subunits)" lightbox="true" >}}

To try to prove this a little more thoroughly, we isolated 20 bacteria from our communities. We found that our isolates that were most similar to 16S ASVs 3 and 4 were able to degrade chitin, while many of those that were abundant at on days three and four were only able to use the sub-products of chitin degradation (and some weren't able to use these and would instead rely on the mix of other nutrients that are produced by communities. <em>Cafeteria</em>, which is the organism that is closest to the 18S ASVs 1 and 2, is known to be a protist (single-celled organism that can swim around) that grazes on (eats) bacteria. We also did another experiment where we grew a "cheater" bacterium with a chitin degrader - without the chitin degrader, the cheater bacterium didn't grow at all, but when the chitin degrader was present, the cheater was also able to grow. 

So what does this mean for chitin degradation? The chitin activity didn't actually increase very much across our whole experiment, so how do we select for better chitin degradation? What we'd found out so far is that the optimal incubation time kept changing. So we decided to carry out a new artificial selection experiment, where instead of incubating our communities for a fixed amount of time between generations (four or nine days), we measured the chitinase activity every day and selected the new communities once we had seen a peak in chitinase activity. We did this for 50 days, and found that this produced chitinase activities that were 90 times higher than in our first experiment (see below figure)!

{{< figure src="Figure 6.png" title="The improved artificial selection method (Figure 6 of the paper), showing chitinase activity for means (all 30 communities) and highest (the three communities with the highest activity that are used to inoculate the next generation)" lightbox="true" >}}

In this paper, we proved the validity of artificially selecting a natural microbial community to better degrade chitin, but highlighted the caveats for achieving this goal, which require a better understanding of the ecology of the system. We find that future artificial selection experiments should adjust selection incubation times to enzyme activity maxima to successfully evolve enhanced communities.

The full paper can be downloaded or viewed online using one of the links at the top of this page, along with a link to the preprint (an earlier version of this paper). 
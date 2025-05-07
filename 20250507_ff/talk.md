<!-- .slide: data-background="assets/ghibli_microbiome4.jpeg" class="dark no-logo" -->

# From environment to intervention:<br> Getting more from metagenomics data

Christian Diener<br>
D&RI of Hygiene, Microbiology and Environmental Medicine

<img src="assets/meduni/logo_slogan_dark.png" width="30%">

<br><br>
<div class="footer" style="margin-top: 6em">
<a href="https://creativecommons.org/licenses/by-sa/4.0/"><i class="fa-solid fa-camera-retro"></i>CC BY-SA 4.0</a>
<a href="https://dienerlab.com"><i class="fa-solid fa-house-signal"></i></i>dienerlab.com</a>
<a href="https://github.com/dienerlab"><i class="fa-brands fa-github"></i>dienerlab</a>
<a href="https://bsky.app/profile/cdiener.com"><i class="fa-brands fa-bluesky"></i></i>@cdiener.com</a>
</div>

---

## The blood-microbiome axis

<img src="assets/mets.png" width="80%" />


The human gut microbiome impacts physiology through a complex *interplay* between *microbes*, the *environment*,
and the *host*.

---

## Metagenomic sequencing

Metagenomics, while highly scalable, mostly focuses on *bacteria* and other microbial organisms and associating
their (gene) abundances to phenotypes.

![](assets/metagenome.png)

Can we glean information about the *environment* from metagenomics data?

---

<!-- .slide: data-background="var(--primary)" class="dark" -->

## Metagenomic estimation of dietary intake

Many foods we consume contain highly specific DNA sequences.

DNA can potentially comply with the requirements of a biomarker and there are some established
marker genes (<i>trnL</i> or 12S rRNA gene).

Can we leverage total fecal DNA as a biomarker for food intake?

<div class="footnote">

Cuparencu et al. 2024, Nature Metabolism, https://doi.org/10.1038/s42255-024-01067-y

Petrone et al. 2023, PNAS, https://doi.org/10.1073/pnas.2304441120

</div>

---

<!-- .slide: data-background="var(--primary)" class="dark" -->

<img src="assets/medi.png" width="100%" />

<br>

<div class="footnote">

Diener* et al. 2025, Nature Metabolism, https://doi.org/10.1038/s42255-025-01220-1

</div>

---

## A database of food DNA database linked to nutrients

<img src="assets/db.png" width="80%" />

---

## A decoy-aware mapping strategy

<img src="assets/fig2.png" width="90%" />

---

## Validation with controlled-feeding studies

<img src="assets/cfs.png" width="100%" />

---

## Predicted nutrient content correlates with food diaries

<img src="assets/nuts.png" width="100%" />

---

## Metagenomic food quantifications across infants and adults

<div style="display: flex; align-items: center; justify-content: space-evenly">

<img src="assets/lifespan.png" width="50%">

<div style="width: 40%">

Lots of dropouts.

Anticipates onset of solid food consumption in infants.

Good correspondence with FFQs and higher correspondence with gut microbiome composition (Mantel test) than FFQs.

</div>

</div>

---

<!-- .slide: data-background="assets/backdrop.webp" class="dark" -->

## Microbial community-scale metabolic modeling

We can see the *pieces* of the game, but what are the *rules*?

Knowing how diet *causally* affects the function of microbial communities is and how
we can *intervene* is the basis for therapeutic use. One possible set of rules are posed
by *metabolism*.

What can we learn about *metabolism* from metagenomic data?


---

## Quantifying metabolism through fluxes

<img src="assets/fluxes.png" width="45%">
<video width="45%" autoplay loop>
  <source src="assets/fluxes.mp4" type="video/mp4">
</video>

"How fast does a species grow?" and "How much of this metabolite is produced?" are
questions about *fluxes, not concentrations*.

---

## Flux Balance Analysis (FBA)

![](assets/fba.png)

---

## Mechanistic modeling from metagenomic data

![](assets/micom_quick.png)

Predicts *steady state fluxes* of individual taxa in complex communities and *single samples*.

Integrates interactions with (emergent) *environment*.

<div class="footnote">

Diener et al. 2020, mSystems, https://doi.org/10.1128/mSystems.00606-19<br>
Diener & Gibbons 2023, mSystems, https://doi.org/10.1128/msystems.01270-22<br>
Quinn-Bohmann, Carr, Diener* & Gibbons*, Nature Microbiology 2025, https://doi.org/10.1038/s41564-025-01972-2
</div>

---

## Screen and ex vivo validation

<img src="assets/approach.png" width="90%">


---

## Rational prediction of SCFA production after fiber intervention

<img src="assets/fig2def.png" width="80%">


<div class="footnote">

Quinn-Bohmann, ..., Diener* & Gibbons*, Nature Microbiology 2024, https://doi.org/10.1101/2023.02.28.530516

</div>

---

## Strong association with host blood chemistries

<img src="assets/fig5b.png" width="60%">

Arivale cohort (n=3,129), adjusted for sex, age, and BMI

---

## There is no one-fits-all intervention for butyrate production

<img src="assets/fig6.png" width="55%">


---

<!-- .slide: data-background="var(--primary)" class="dark" -->

## Take home messages

- remaining food DNA can be identified in metagenomic sequencing by decoy-aware mapping
  - there might be use in *sequencing deeper*
- while generally low abundance food DNA can give insights into habitual *intake* and nutrient
  content
  - *simultaneous* measurement
- microbial community metabolic modeling can predict the effect of select interventions
  - *rational* prediction
- large-scale screening and validation by <i>in silico</i> ⇋ <i>ex vivo</i> loops
  - <i>ex vivo</i> assays running soon* at ZMF2

---

<!-- .slide: data-background="assets/meduni/flags.png" class="hero no-logo" -->

# Thanks! :smile:

<div style="display: flex; align-items: center; justify-content: space-evenly">

<div style="width: 40%">

<a href="https://dienerlab.com"><i class="fa-solid fa-house-signal"></i></i>&nbsp;https://dienerlab.com</a>

<br>

**MedUni Graz**<br>
Klara Filek<br>
Christine Moissl-Eichinger<br>
Gregor Georkiewicz

**ISB**<br>
Sean Gibbons<br>
Nick Quinn-Bohmann<br>
Kat Ramos-Sarmiento<br>
Alex Carr

</div><div style="width: 40%">

**U of I Urbana-Champaign**<br>
Hannah Holscher

**AdventHealth**<br>
Karen Corbin

**Funding**<br>
<img src="assets/coe.jpg" width="42%">&nbsp;
<img src="assets/niddk.svg" width="50%">


Other topics:

- drug-microbiome interactions (statins)
- microbiome during aging

</div></div>

---

<img src="assets/flux_cone.png" width="100%">


---

## Genome-scale metabolic models - pretty well-behaved

<img src="assets/gsmm.webp" width="100%">

<div class="footnote">

Schuetz et al. 2012, https://doi.org/10.1126/science.1216882<br>
Harcombe et al. 2013, https://doi.org/10.1371/journal.pcbi.1003091

</div>

---

## Community-scale metabolic models - pretty rowdy

<img src="assets/csmm.webp" width="100%">

<div class="footnote">

Diener et al. 2023, https://doi.org/10.1128/msystems.01270-22<br>
Senne de Oliveira Lino et al. 2021, https://doi.org/10.1038/s41467-021-21844-7

</div>

---

## Anaerobic <i>ex vivo</i> fermentation

<img src="assets/ex_vivos.png" width="85%">
# **Research Methods qPCR Assignment** 
## ***By: Ben Berman***

### Part 1: Gene Invetsigation Using qPCR

**Species: *Symbiodinium microadriaticum***

<u>Target Gene 1: H<sup>+</sup>-ATPase </u>

Why did you choose this gene:
This gene is essential for secreting H+ ions to provide membrane diffusion potential and aid in carbon dioxide coversion for photosynthesis.

It's known or suspected biological function.
This gene encodes for a proton pump in these dinoflagelate alage that is only expressed by endoosymbiotic Symbiodinium to transport cations across cell membranes. 

What changes in gene expression do you expect to observe and why?
Expression changes will be observed upon symbiosis in coral hosts to improve symbiotic energy aquisition, where expression of H<sup>+</sup>-ATPase will be dmoninant in symbiosis.

Which stress, treatment, environmental condition, or experimental manipulation do you plan to test? 

I would investigate the impact of thermal stress by drastic heat waves on H<sup>+</sup>-ATPase to determine the effects of this protein pump when climate change induced global warmin is present at abdormal extremes.

Why is the selected gene relevant to that condition?
H<sup>+</sup>-ATPase is a critical player in supporting the zooxanthale-coral symbioytic relationship, and would likely experience expression challenges when the symbiotic alage and coral are indiviudally and coopertaively suffering from heat stress challenges.

<u> Target Gene 2: HSP70 </u>

Why did you choose this gene?
This gene represents a clas of heat shock proteins that are essential for uspporting this dinoflagelate under high thermal stress,

It's known or suspected biological function.
Assisting in the folding and assembly of newly synthesized proteins within the endoplasmic reticulum (ER) anf can repair and refold of damaged proteins.

What changes in gene expression do you expect to observe and why?
Gene expression will increase when thermal stress is more dominant to cope with this environmental challenge.

Which stress, treatment, environmental condition, or experimental manipulation do you plan to test? 
Experiemtal manipulation will include how these genes respond to heat stress induced from global warming and climate change.

Why is the selected gene relevant to that condition?
This gene is important to maintain zooxanthaale and coral homeostasis when thermal pressures are present and place thi key symbiotic relationship at risk of collapse.

Reference gene: Cox1 (Cytochrome c Oxidase Subunit I)

why you expect its expression to remain stable under your experimental conditions.
The expression of this gene will remai stable under artifical heat stress as it is consistently stabaly expressed in mitochondria of these phytoplankton.

Well-supported explanation of hypotheses and expected outcomes demonstrating the scientific reasoning behind your choices. 

1. **Hsp70 Hypothesis:**  
   Light extremes will induce Hsp70 upregulation to initiate the heat stress response to best manage excess thermal energy. This will result in the *Symbiodinium microadriaticum* cell, proteins, membranes and other biological qualities to have better heat tolerance as a coping strategy. 

2. **H+-ATPase Hypothesis:**  
   Stress conditions will likely increase expression fron enhanced demand of proton regulation and intracellular pH homeostatic maintenance. A stronger presence of this protein would allow cells to better sequester energy to symbiotic coral hosts to protect them against thermal stress.

3. **cox1 Hypothesis (Control):**  
   cox1 expression will remain stable across all treatments, validating its use as a reference gene. No change at the genotypic and phenotypic leel would occur.


### Part 2: Relative Quantification Data Interpretation

**Introduction:**

To perform a relative quantification analysis of qPCR data, the Delta-Delta Ct Method or Livak method is employed. This method is effective for determining the change in gene product of a target gene in comparison to a housekeeping gene when a stres factor is intriduced. The Lival/ΔΔCT method assumes that target and reference gene amplification efficiencies around 100%, with refrence/housekeeping gene expression stably consistant in every samle and in experiment conditons.

**Methods**
Calculations: 

- Cycle Threshold (Ct) values, which represent when the fluorescent signal from replicated DNA exceeds that of the background level threshold, was obtained from performing qPCR. Tubulin acts as a strong housekeeping gene given stable and consistent expression.
- The Delta Ct parameter was calculated using the appropriate formuala (ΔCt = Ct target - Ct reference) to normalize the expression of the target gene to the reference gene to correct against potential sample variability. 
- The Delta-Delta Ct parameter was calculated using the appropriate formula (ΔΔCt = ΔCt experimental - ΔCt control) to normalize target gene expression of the experimental treatment sample to the experimentally controlled sample.
- The Relative Quantification or fold change was calculated using the appropriate formula (fold change = 2^−ΔΔCt) which indicates the difference in exprression of the target sample compared to the control sample.

**Results**
Final graph & tables

**Table 1:** Cycle Threshold (Ct) of qPCR for analyzed genes under control (DMSO) and treatment (inhibitor) experimental conditions. Target genes are indicated in ***bold and italicized text***, with the excepition of *Tubulin*, which acted as the reference gene (indicated by an asterix [x]), being evident from no change Ct between control and treatment conditions.

| Condition | *Tubulin** | *ascs* | *Delta* | *ets* | *foxA* | *gcm* | *NGN* | *opt* | *pak3* | *pak4* | *pitx* | *SM30* | *sm50* | *soxC* | *synB* |
|------------|-----------|------|-------|------|------|------|------|------|------|------|------|------|------|------|------|
| DMSO Control | 23.30 | 29.09 | 25.96 | 24.72 | 24.37 | 28.35 | 28.35 | 31.02 | 25.41 | 25.57 | 29.68 | 20.97 | 23.70 | 25.07 | 24.13 |
| Inhibitor Treatment | 23.30 | 28.51 | 25.54 | 24.44 | 23.72 | 28.18 | 27.35 | 31.71 | 25.29 | 25.25 | 31.72 | 21.77 | 24.81 | 24.33 | 24.06 |



**Table 2:** Computation and analysis of relative quantification parameters of target genes. Relative quantification parameters were calculated as previously described in the Methods. Target genes are indicated in ***bold and italicized text***. 

| Relative Quantification Parameter |  *ascs* | *Delta* | *ets* | *foxA* | *gcm* | *NGN* | *opt* | *pak3* | *pak4* | *pitx* | *SM30* | *sm50* | *soxC* | *synB*|
|-------------|------|-------|------|------|------|------|------|------|------|------|------|------|------|------|
| DMSO Control ΔCt | 5.798492039 | 2.668118854 | 1.421209753 | 1.070320705 | 5.058759526 | 5.055620436 | 7.724890764 | 2.110212597 | 2.275558495 | 6.382601514 | -2.326773173 | 0.404644329 | 1.776511123 | 0.830644553 |
| Inhibitor Treatment ΔCt | 5.213096166 | 2.242432664 | 1.141776254 | 0.426898078 | 4.882689152 | 4.057358850 | 8.412595342 | 1.999217137 | 1.956972448 | 8.428596513 | -1.529216886 | 1.515168132 | 1.032331749 | 0.763907434 |
| ΔΔCt | -0.585395873 | -0.425686191 | -0.279433499 | -0.643422627 | -0.176070374 | -0.998261586 | 0.687704578 | -0.110995460 | -0.318586047 | 2.045994999 | 0.797556287 | 1.110523803 | -0.744179374 | -0.066737119 |
| Fold Change (2^-ΔΔCt) | 1.500450654 | 1.343211224 | 1.213718202 | 1.562030504 | 1.129802324 | 1.997591498 | 0.620840863 | 1.079973162 | 1.247107688 | 0.242155387 | 0.575322865 | 0.463125852 | 1.675021222 | 1.047345268 |



![qPCR_chart.png](https://benberman1.github.io/Ben-Research-method-2026/images/qPCR_chart.png)
**Figure 1:** Quatified fold change for each target gene analyzed. Values greater than 1 indicate target gene upregulation, while values less than 1 indicate target gene downregulation, relative to the expression of the housekeeping gene *Tubulin* in treatment conditions compared to control conditions.


**Discussion**
interpretations:

Genes that were upregulated in the treatment condition (fold change value greater than 1) are *ascs*, *Delta*, *ets*, *foxA*, *gcm*, *NGN*, *pak3*, *pak4*, *soxC*, and *synB*. Contrarily, were upregulated in the treatment condition (fold change value less than 1) are *opt*, *pitx*, *SM30*, and *sm50*. Therefore, we would expect greater genotype presence and phenotypic effects from the upregulated genes, and a decrease in genotype and associated phenotype in downregulated genes.

## Using the ribulose-1,5-bisphosphate carboxylase/oxygenase large subunit gene *rbcL* for Primer Design and Phylogenetic Analysis of *Padina thivyi*.  

### Objective
The goal of this protocol is to design specific primers targeting the rbc1 gene for identification of *Padina thivyi* and constructing an acompaning phylogenetic tree.

### Materials and Reasoning

- The target algal species to be examined is *Padina thivyi*; a group of photosynthetic marine dinoflagellates often existing as symbionts in multicellular ocean organisms.
- The target gene inestigated is rbcL; a gene that encodes for the catalytic subunits of the carbon-fixating chloroplast enzyme RuBisCo (Ribulose1,5-bisphosphate carboxylase/oxygenase). 
- The rbcL gene is structurally conserved among photosynthetic organisms, however possesses small variable species-specific evolutionairy-induced sequence differences. Given this, and its strong representation in GenBank data, rbcL is a suitable marker for species identification and taxanomic classification.
- Producing primers for *Padina thivyi* will allow specific amplification of the rbcL gene for species identification and further investigation, while phylogenetic analysis of *Padina thivyi* will demonstrate the evolutionairy history and common ancestry of this species.

### Methods 
####Primers
#####Sequence Collection
- Navigated to [NCBI](https://www.ncbi.nlm.nih.gov/).
- Flitered databases to "Nucleotide" and searched for "Padina".
- Located the sequence for the [Padina thivyi chloroplast rbcL gene for ribulose-1,5-bisphosphate carboxylase/oxygenase large subunit, partial cds, country: Japan: Kagoshima, Tanegashima](https://www.ncbi.nlm.nih.gov/nuccore/AB358933.1)
- Obtained the FASTA sequence of the rbcL gene for [*Padina thivyi*](https://www.ncbi.nlm.nih.gov/nuccore/AB358933.1?report=fasta) 

CCGGCGTGGATCCTGTAGAGGCTGCTGCCGCAGTAGCTGGAGAATCTTCAACTGCTACGTGGACTGTTGT
TTGGACTGATTTATTAACAGCCTGTGACATTTATCGAGCAAAAGCCTATCGAGTAGATCCAGTACCTGGT
ACAAATGATCAATTCTTTGCTTATATAGCATACGAATGTGATTTATTTGAAGAAGGTTCATTAGCTAATT
TAACAGCATCTATTATTGGTAATGTTTTTGGATTTAAAGCTGTTAAAGCTTTACGTCTAGAAGATATGCG
AATTCCTTTTGCTTATTTAAAAACATTCCAAGGTCCTGCTACTGGTGTAATTGTTGAACGAGAAAGATTA
GATAAATTTGGTCGTCCTTTATTAGGAGCAACAGTAAAACCTAAGTTAGGTCTTTCTGGAAAAAACTATG
GTCGTGTTGTTTATGAAGGTTTACGAGGTGGACTTGACTTCTTAAAAGATGATGAGAATATTAACTCACA
ACCTTTTATGCGTTGGAAAGAACGTTTTCTTTACTGTATGGAAGGTGTAAACCGCTCTGTAGCAGCAACA
GGTGAAGTTAAAGGGTCATACTTAAATGTAACGGCATCAACAATCGAACAAATGTATGAACGTGCTGAGT
ATGCAGATTCTTTAGGGAGTGTAATTGTTATGATTGACTTAGTAATTGGGTATACAGCAATCCAAACTAT
GGCAATCTGGGCACGTAAAGCTCAAATGATCTTACATTTACACCGTGCAGGAAACTCAACTTATGCCCGT
CAAAAAAACCATGGTATAAACTTCCGTGTTATTTGTAAGTGGATGCGTATGTCAGGTGTGGATCATATTC
ATGCAGGAACTGTTGTTGGTAAATTAGAAGGTGACCCTCTAATGGTAAGAGGTTTTTATAACACATTACT
ACTAACTGAGTTAAAAGTTAATTTAGCTGAAGGTCTATTCTTCGATATGAGCTGGGCTTCTCTTCGTAAA
TGTGTTCCAGTAGCTTCTGGTGGAATCCATTGTGGACAAATGCATCAACTTTTATACTACTTAGGAGACG
ACGTAGTATTACAATTTGGAGGTGGTACAATTGGTCATCCAGATGGTATTCAATCTGGTGCTACTGCTAA
TCGTGTAGCTTTAGAAGCTATTGTTTTAGCTCGAAATGAAGGTCGTGATTATGTAGCTGAAGGACCAGAA
ATTCTACGTACTGCTGCAGCTACATGTGGTCCATTAAAAACAGCTTTAGATTTATGGAAAGATATTACTT
TTGAATACACATCAACAGATACTACAGACTTCGTAG

Compared it to the FASTA sequences of the chloroplast rbcL gene for [*Padina tetrastromatica*](https://www.ncbi.nlm.nih.gov/nuccore/AB512554.1?report=fasta), [*Padina okinawaensis*](https://www.ncbi.nlm.nih.gov/nuccore/AB490398.1?report=fasta), [*Padina undulata*](https://www.ncbi.nlm.nih.gov/nuccore/AB489952.1?report=fasta), and [*Padina terricolor*](https://www.ncbi.nlm.nih.gov/nuccore/AB489948.1?report=fasta) obtained using the same method.

#####Sequence Alignment
- To allign Padina speices rbcL gene equences, the MEGA (Molecular Evolutionairy Genetics Analysis) software [version 12.1](https://www.megasoftware.net/) was implemented.
- The sequences that were compared were DNA.

![Padina_rbcL](https://benberman1.github.io/Ben-Research-method-2026/images/Padina_rbcL.png)
Figure 1: Allignment of the rbcL gene sequence between *Padina thivyi* (AB358933.1), *Padina tetrastromatica* (AB512554.1), *Padina okinawaensis* (AB490398.1), *Padina undulata* (AB489952.1), and *Padina terricolor* (AB489948.1). Sequences were retrieve as FASTA outputs from NCBI. Far left collumn lists the sequences of 5 algae species in NCBI acession format (as listed in brackets next to the species). Nucleotide region displayed in each row is 1-109, 110-218, 219-327, 328-436, 437-545, 546-654, 655-763, 764-872, 873-981, 982-1090, 1091-1199, 1200-1308, 1309-1319
Unhighlighted nucleotides are conserved regions, highlighted nucleotides identific variable regions. A total of 100 ​single nucleotide polymorphisms (SNPs) were present, specifically at nucelotide posiitions 119, 137, 146, 149, 167, 200, 209, 218, 233, 251, 267, 311, 329, 330, 335, 345, 395, 419, 422, 431, 444, 455, 476, 518, 545, 548, 550, 560, 575, 582, 593, 594, 605, 617, 626, 629, 632, 635, 639, 647, 674, 680, 683, 686, 707, 731, 749, 758, 767, 791, 800, 809, 830, 833, 836, 845, 857, 864, 879, 889, 899, 905, 912, 920, 938, 944, 945, 947, 953, 956, 962, 992, 1010, 1037, 1040, 1049, 1052, 1059, 1106, 1121, 1127, 1130, 1142, 1194, 1196, 1201, 1208, 1209, 1219, 1220, 1223, 1253, 1265, 1268, 1271, 1284, 1286. One indel (insertion-deltion) is present at the end of the gene sequence, either an insertion or deletion of nucleotides 1297-1319. Produced using the MEGA (Molecular Evolutionairy Genetics Analysis) software [version 12.1](https://www.megasoftware.net/).

#####Sequence Alignment
- Impletemented the primer designing software Primer3.
- Inserted the FASTA gene sequence of the chloroplast rbcL gene for *Padina tetrastromatica*.
- Prompter the software to generate ("pick") primers.

*_Primer characteristics_*

|Primer Type| Sequence | Length (base pairs) | Melting Temperature (Tm)| GC content | Expected Amplicon Size (base pairs)|Sequence Position (sequence nucleotide number)
|------|------|------|----------------|-----------|-----|-------|
| Forward |ACGGCATCAACAATCGAACA|20|58.48|45.00|239|591-611
| Reverse |ACACCTGACATACGCATCCA|20|59.10|50.00|239|829-810


Verify your primer pair using NCBI Primer-BLAST.

#####Phylogenetic Analysis
- Impleted the MEGA (Molecular Evolutionairy Genetics Analysis) software [version 12.1](https://www.megasoftware.net/)
- Sequences were alligned using the ClustalW method.
- Tree-building method was the Neighbor-Joining method.
- Substitution model was the Kimura 2-parameter

•	Number of bootstrap replicates

![Padina_Tree1](https://benberman1.github.io/Ben-Research-method-2026/images/Padina_Tree1.png)
Figure 2: Phylogentic tree of 5 algae species from the genus Padina: *Padina thivyi* (AB358933.1), *Padina tetrastromatica* (AB512554.1), *Padina okinawaensis* (AB490398.1), *Padina undulata* (AB489952.1), and *Padina terricolor* (AB489948.1). NCBI acession name indicates species phylogenic tree position and history. Made using MEGA (Molecular Evolutionairy Genetics Analysis) software [version 12.1](https://www.megasoftware.net/).

**Phylogenetic Results**
- *Padina okinawaensis* and *Padina terricolor* cluster closest to gether on the phylogeneic tree, meaning they are most strongly related from these 5 algae species and decended from a more recent common ancestor.
- *Padina thivyi* is not the most distantly related species, and thus being phylogenetically situated in between other Padina algae makes sense and meets expected position for this species.

•	Bootstrap values supporting the main branches

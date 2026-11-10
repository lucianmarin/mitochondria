# Chapter 7: The Second Genome: Mitochondrial DNA, Peptides, and Epigenetics

While the nuclear genome sits in a single two-copy vault per cell, the mitochondrial genome (**mtDNA**) exists as a dynamic population of **hundreds to hundreds of thousands of circular genomes** distributed throughout the mitochondrial network of a single cell. Measuring just **16,569 base pairs** in humans, this tiny loop of double-stranded DNA violates almost every textbook rule of Mendelian genetics: it is inherited exclusively from the mother, lacks histones and introns, uses a modified genetic code, replicates independently of the cell cycle, and segregates randomly and selectively across cell divisions.

## Architecture of the 16,569-Base-Pair Circle

The two strands of human mtDNA differ in their nucleotide composition (G+T vs. C+A content), allowing them to be separated by buoyant density centrifugation into a **Heavy (H) strand** (guanine-rich) and a **Light (L) strand** (cytosine-rich). Over 93% of the circle is coding sequence, with only one major non-coding regulatory region: the **1,124-bp Control Region** housing the **Displacement loop (D-loop)**, the transcriptional promoters (**LSP, HSP1, HSP2**), and the origin of heavy-strand replication (**$\text{O}_H$**).

The **37 canonical genes** encode:
* **13 OXPHOS Core Polypeptides:**
  * **7 subunits of Complex I:** *MT-ND1, MT-ND2, MT-ND3, MT-ND4, MT-ND4L, MT-ND5,* and *MT-ND6* (the only protein encoded on the Light strand).
  * **1 subunit of Complex III:** *MT-CYB* (cytochrome $b$).
  * **3 subunits of Complex IV:** *MT-CO1, MT-CO2,* and *MT-CO3*.
  * **2 subunits of Complex V (ATP Synthase):** *MT-ATP6* and *MT-ATP8* (whose open reading frames physically overlap by 46 nucleotides!).
* **2 Ribosomal RNAs:** *MT-RNR1* (12S rRNA) and *MT-RNR2* (16S rRNA).
* **22 Transfer RNAs:** Sufficient to read all 60 amino-acid codons of the vertebrate mitochondrial genetic code using super-wobble base pairing (where **UGA** encodes tryptophan rather than stop, **AUA** encodes methionine rather than isoleucine, and **AGA/AGG** act as frame-shifting stop signals).

### Nucleoids and TFAM Packaging
Contrary to an old myth that mtDNA is "naked" and unprotected, each mtDNA molecule is tightly compacted into a ~100-nanometer protein-DNA sphere called a **nucleoid** by **TFAM (Mitochondrial Transcription Factor A)**. As **Nils-Göran Larsson** and **Claes Gustafsson** demonstrated, TFAM dimers bind mtDNA every 15–20 base pairs and bend the DNA backbone by sharp $180^\circ$ U-turns. The cellular level of TFAM directly regulates mtDNA copy number and compaction: lightly coated nucleoids are open for replication and transcription, whereas heavily TFAM-compacted nucleoids are transcriptionally silent storage units.

### Replication and the Replisome
Mitochondrial DNA is replicated by a dedicated four-part minimal **replisome** distinct from nuclear DNA polymerases:
1. **DNA Polymerase $\gamma$ (POLG):** A heterotrimer of one catalytic subunit (*POLGA*, possessing $5'\to 3'$ polymerase and $3'\to 5'$ proofreading exonuclease activities) and two accessory processivity subunits (*POLGB*).
2. **Twinkle (*TWNK*):** The hexameric $5'\to 3'$ replicative helicase (homologous to bacteriophage T7 gp4 helicase) that unwinds the double helix ahead of POLG.
3. **mtSSB:** The tetrameric single-stranded DNA-binding protein that protects displaced single strands and stimulates Twinkle and POLG.
4. **POLRMT:** The mitochondrial RNA polymerase, which synthesizes both polycistronic mRNA transcripts (processed via **RNase P** and **ELAC2/RNase Z** at tRNA junctions, followed by **mtPAP** polyadenylation) and the RNA primers required to initiate DNA replication at $\text{O}_H$ and $\text{O}_L$.

In the predominant **strand-displacement model** (supported by Claes Gustafsson and Maria Falkenberg), replication begins at $\text{O}_H$, displacing the parental H-strand as a single-stranded loop coated by mtSSB (or hybridized to processed RNA transcripts in the **RITOLS/bootlace model** described by Ian Holt) until the replication fork passes two-thirds of the way around the circle and exposes the stem-loop origin of light-strand replication (**$\text{O}_L$**), triggering synthesis of the second strand in the opposite direction.

## Beyond 37 Genes: Mitochondrial-Derived Peptides (MDPs)

One of the most paradigm-shifting discoveries of the 21st century is that the mitochondrial genome encodes far more than 37 genes. Pioneered by **Pinchas Cohen** and **Changhan David Lee** at the USC Leonard Davis School of Gerontology, along with **Ikuo Nishimoto** and **Shigeo Ohta**, researchers discovered that short open reading frames (**sORFs**) nested inside the 12S and 16S rRNA genes produce bioactive microproteins called **Mitochondrial-Derived Peptides (MDPs)** that act as intracellular and systemic hormones:

* **Humanin (24 amino acids, encoded within *MT-RNR2* / 16S rRNA):** Discovered in 2001 as a neuroprotective factor rescuing neurons from Alzheimer's amyloid-$\beta$ toxicity, Humanin binds BAX to block apoptosis and signals extracellularly through the trimeric CNTFR/WSX-1/gp130 receptor complex to suppress inflammation and oxidative stress. Circulating Humanin levels correlate with longevity in centenarians and their offspring.
* **MOTS-c (16 amino acids, encoded within *MT-RNR1* / 12S rRNA):** Discovered by Lee and Cohen in *Cell Metabolism* (2015), MOTS-c acts as an **"exercise mimetic" hormone**. It is translated in the cytoplasm using the standard genetic code from exported 12S rRNA fragments. By inhibiting the folate-methionine cycle, MOTS-c causes accumulation of the endogenous purine intermediate **AICAR**, which directly activates **AMPK**, stimulates skeletal muscle glucose uptake, and prevents high-fat-diet-induced obesity and insulin resistance. Even more remarkably, in 2018–2021 (*Cell Metabolism*; *Nature Communications*), Lee and Cohen proved that upon metabolic or oxidative stress—or during vigorous exercise in humans—**MOTS-c physically translocates into the cell nucleus**, where it binds chromatin alongside **NRF2** and **ATF1** to directly regulate nuclear stress-response genes!
* **SHLP1–6 (Small Humanin-Like Peptides 1–6):** Six additional microproteins encoded within the 16S rRNA region; notably, **SHLP2** acts as a chaperone-like stabilizer of Complex I and protects dopaminergic neurons against Parkinson's disease pathology (Kim et al., *Molecular Psychiatry* 2024).

## Maternal Inheritance, Heteroplasmy, and the Germline Bottleneck

Why do we inherit mtDNA exclusively from our mothers? During mammalian fertilization, the mature oocyte contains **200,000 to 600,000 copies of mtDNA**, whereas the sperm midpiece brings only **50 to 100 copies**. Even before fertilization, during spermiogenesis in humans, **Dmitry Temiakov** and colleagues showed (*Nature Genetics* 2023) that human spermatozoa actively strip out nearly all their mtDNA nucleoids because TFAM is phosphorylated and blocked from entering sperm mitochondria. Any residual paternal mitochondria that enter the egg at fertilization are rapidly tagged with ubiquitin and destroyed by **allophagy** (selective paternal mitophagy mediated by Parkin, MUL1, p62, and CPS-6 endonuclease).

Because each cell carries thousands of mtDNA molecules, a person can harbor two or more genetically distinct populations of mtDNA within the same cell or tissue—a state called **heteroplasmy** (contrasted with **homoplasmy**, where all copies are identical).

Two fundamental principles govern how heteroplasmic mtDNA mutations cause disease:

1. **The Bioenergetic Threshold Effect:** Wild-type mtDNA copies within the fused mitochondrial network complement mutant copies until the percentage of mutant mtDNA crosses a critical biochemical threshold—typically **60% to 70%** for large deletions and **80% to 90%** for tRNA point mutations. Below that threshold, a carrier may be completely asymptomatic; just a few percentage points above it, ATP synthesis collapses and severe clinical disease emerges.
2. **The Mitochondrial Genetic Bottleneck and Purifying Selection:** A mother with 40% heteroplasmy for the MELAS m.3243A>G mutation might have one child with 5% mutant load (completely healthy) and another child with 85% mutant load (severely affected). Why? During early female embryonic development, as primordial germ cells (PGCs) specify, the effective number of segregating mtDNA units drops dramatically to a tight **bottleneck** (~100–200 segregating units) before re-amplifying to >200,000 copies in the mature oocyte.
   Moreover, the bottleneck is not merely passive statistical drift. Landmark studies by **Patrick Chinnery**, **Doug Turnbull**, **Nils-Göran Larsson**, and **Hansong Ma** (2019–2025) revealed that the developing female germline actively subjects mitochondria to **purifying selection**: oocytes fragment their mitochondrial network into individual units so that organelles carrying severe protein-coding mutations cannot be rescued by fusion and are selectively eliminated by **germline mitophagy** (involving *BCL2L13*, *ULK1*, and *BNIP3*) or outcompeted during replication by healthy mitochondria. Conversely, certain non-coding variants or tRNA mutations evade this filter—or even replicate selfishly faster than wild-type mtDNA—explaining why mutations like m.3243A>G recur so frequently in human clinics.

## mtDNA Haplogroups: Human Migration and Climate Adaptation

In the 1980s and 1990s, **Douglas C. Wallace**, **Rebecca Cann**, **Mark Stoneking**, and **Allan Wilson** used maternal mtDNA sequence variation across indigenous global populations to reconstruct the evolutionary tree of modern *Homo sapiens*, tracing all living humans back to a maternal common ancestor in Africa ("Mitochondrial Eve," ~150,000–200,000 years ago) and mapping the human diaspora across the globe via sequential **mtDNA haplogroups**:
* **African Lineages:** Macro-haplogroup **L** (L0, L1, L2, L3).
* **Out-of-Africa Eurasian and American Lineages (derived from L3):** Macro-haplogroups **M** (giving rise to Asian/Native American haplogroups **C, D, G, Z**) and **N** (giving rise to European haplogroups **H, J, T, U, K, V, W, X, I** and Asian/Native American **A, B**).

Wallace proposed that key missense mutations defining northern haplogroups (such as **A, C, D, G, J, T, and X**) were positively selected during Ice Age migrations into Siberia, Northern Europe, and the Arctic because they slightly reduced proton-pumping coupling efficiency—trading maximal ATP yield per calorie for slightly higher basal proton leak and **endogenous heat production** to survive extreme cold.

In the modern industrial environment of caloric excess and sedentary living, however, these ancient adaptive haplogroups confer distinct clinical susceptibilities: tightly coupled haplogroups (such as **H**) generate more ATP per calorie—conferring higher survival during acute sepsis and higher maximal $\text{VO}_2\text{max}$ in endurance athletes—but also generate higher resting membrane potential and ROS when overfed, increasing the relative risk of late-onset Alzheimer's and Parkinson's diseases compared to partially uncoupled haplogroups like **J, T, or U**.

## Ongoing Somatic NUMTogenesis

Finally, the flow of DNA from mitochondrion to nucleus did not stop two billion years ago. In a 2022 *Nature* study of 66,083 human whole genomes (by **Wei Wei** and **Patrick Chinnery**) and a 2024 *PLOS Biology* study of 1,187 human postmortem brains and cultured fibroblasts (by **Ryan Mills**, **Martin Picard**, and **Patrick Chinnery**), researchers proved that fragments of mtDNA leak out of stressed mitochondria and stitch themselves into nuclear chromosomes via non-homologous end joining throughout human life (**somatic NUMTogenesis**). In the human dorsolateral prefrontal cortex, individuals who accumulated more *de novo* nuclear insertions of mtDNA died at younger ages, and chronic glucocorticoid stress or mtDNA instability markedly accelerated the rate at which mitochondrial DNA fragments invaded the nuclear genome.
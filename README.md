# Manually Curated Microdeletion and Microduplication Syndromes
**Download Instructions**: *Click on the File you wish to view and select "View Raw" to start the download.*
- **Dataset 1**: Microdeletion and Microduplication Syndromes
   - *We identified 192 recurrent and non-recurrent Microdeletion and Microduplication Syndromes which were divided up into 320 individual CNV intervals and 141 non-overlapping CNV regions. Of these intervals, 25% (n=80) had consensus coordinates from ClinGen and/or DECIPHER. Coordinates for the remaining CNV intervals (n=240) were determined manually by leveraging over 2500 patient CNVs, defined SRO(s) or minimal region(s) from the medical literature.*
- **Dataset 2**: Reported Patient CNVs. *A list of patient CNVs, with original and hg19 coordinates, which were reported in the medical literature identified during the creation of this MMS list. The publication source, associated MMS, and subgroup (if applicable) are also recorded. This table is formatted so that the first four columns comply with BED format.*
- **Dataset 3**: hg19 BED File.
- **Dataset 4**: GRCh38 BED File.

- **Datafile 1**: CNV Coordinate Determination by Chromosome.
   - *This document contains a list of all CNVs which did not have consensus coordinates available from ClinGen or DECIPHER. For each CNV, one or more figures are included which depict the coordinates of reported patients with this CNV as well as the coordinates for each SRO, minimal region, or whole region which were defined and included.*
- **Datafile 2**: Reference List for Microdeletion and Microduplication Syndromes



**Materials & Methods**

A non-redundant list of microduplication and microdeletion syndromes (MMS) was obtained from the following databases and publications: Clinical Genome Resource (ClinGen; www.clinicalgenome.org) [1] via UCSC's Table Browser (iscaCuratedPathogenic; n= 61) [2, 3], DatabasE of genomiC varIation and Phenotype in Humans using Ensembl Resources (DECIPHER; https://decipher.sanger.ac.uk/; n= 66) [4], Online Mendelian Inheritance in Man (OMIM; www.omim.org) [5] via the Gene2Map file (keywords: contiguous gene, chromosome (exclude: open reading frame), deletion, duplication, triplication, and quadruplication; n=115), Nevado et al. [6] (n=99), Table 2 of Bentacur [7] (n=39), Supplemental Tables 1 and 2 of Kaminsky et al. [8] (n=41), Additional File 5 of Marcinkowska et al. [9] (n=20) and Table 1 of Wiese et al. [10] (n=193). The non-redundant list was curated to exclude disorders which were only described in a single patient (e.g. 3p11.2‐p12.1 [11, 12]) or family and disorders which are not asssociated with congenital disease (e.g. 8p11 myeloproliferative syndrome; OMIM 613523). CNV disorders were retained even if only the duplication or deletion has been observed or assoicated with human disease. When possible, coordinates for the CNV disorders were obtained from either DECIPHER or ClinGen (accessed August 2021). For all remaining MMS without consensus coordiantes, CNV coordinates for each reported patient were identified as were the coordiantes for any defined shortest region of overlaps (SRO) or minimal regions (Supplementary Table 4). All coordinates were converted from their initial assembly into hg19 coordinates using UCSC's Liftover Tool [13]. These patient and minimal regions were utilized to define the representative CNV interval and when applicable minimal region(s) of overlap. Some MMS were divided into multiple interval regions to account for: recurrent CNVs with multiple breakpoints (e.g. 15q11.2 BP1-2 vs 15q11.2 BP1-3 vs 15q11.2 BP2-3), size differences due to the presence of segmental duplications within a CNV call (1q21.1 TAR Susceptibility Locus), and to account for mutliple minimal CNV regions (e.g. 1q24-q25).



**Literature Cited**

1.	Rehm HL, Berg JS, Brooks LD, Bustamante CD, Evans JP, Landrum MJ, Ledbetter DH, Maglott DR, Martin CL, Nussbaum RL et al: ClinGen — The Clinical Genome Resource. New England Journal of Medicine 2015, 372(23):2235-2242 https://doi.org/doi:10.1056/NEJMsr1406261.
2.	Kent WJ, Sugnet CW, Furey TS, Roskin KM, Pringle TH, Zahler AM, Haussler D: The human genome browser at UCSC. Genome Res 2002, 12(6):996-1006 https://doi.org/10.1101/gr.229102.
3.	Karolchik D, Hinrichs AS, Furey TS, Roskin KM, Sugnet CW, Haussler D, Kent WJ: The UCSC Table Browser data retrieval tool. Nucleic Acids Res 2004, 32(Database issue):D493-496 https://doi.org/10.1093/nar/gkh103.
4.	Firth HV, Richards SM, Bevan AP, Clayton S, Corpas M, Rajan D, Van Vooren S, Moreau Y, Pettett RM, Carter NP: DECIPHER: Database of Chromosomal Imbalance and Phenotype in Humans Using Ensembl Resources. Am J Hum Genet 2009, 84(4):524-533 https://doi.org/10.1016/j.ajhg.2009.03.010.
5.	Online Mendelian Inheritance in Man, OMIM®. In. McKusick-Nathans Institute of Genetic Medicine, Johns Hopkins University (Baltimore, MD): World Wide Web: https://omim.org/.
6.	Nevado J, Mergener R, Palomares-Bralo M, Souza KR, Vallespin E, Mena R, Martinez-Glez V, Mori MA, Santos F, Garcia-Minaur S et al: New microdeletion and microduplication syndromes: A comprehensive review. Genetics and molecular biology 2014, 37(1 Suppl):210-219 https://doi.org/10.1590/s1415-47572014000200007.
7.	Betancur C: Etiological heterogeneity in autism spectrum disorders: more than 100 genetic and genomic disorders and still counting. Brain research 2011, 1380:42-77 https://doi.org/10.1016/j.brainres.2010.11.078.
8.	Kaminsky EB, Kaul V, Paschall J, Church DM, Bunke B, Kunig D, Moreno-De-Luca D, Moreno-De-Luca A, Mulle JG, Warren ST et al: An evidence-based approach to establish the functional and clinical significance of copy number variants in intellectual and developmental disabilities. Genet Med 2011, 13(9):777-784 https://doi.org/10.1097/GIM.0b013e31822c79f9.
9.	Marcinkowska M, Szymanski M, Krzyzosiak WJ, Kozlowski P: Copy number variation of microRNA genes in the human genome. BMC genomics 2011, 12:183 https://doi.org/10.1186/1471-2164-12-183.
10.	Weise A, Mrasek K, Klein E, Mulatinho M, Llerena JC, Hardekopf D, Pekova S, Bhatt S, Kosyakova N, Liehr T: Microdeletion and Microduplication Syndromes. Journal of Histochemistry and Cytochemistry 2012, 60(5):346-358 https://doi.org/10.1369/0022155412440001.
11.	Gat-Yablonski G, Frumkin-Ben David R, Bar M, Potievsky O, Phillip M, Lazar L: Homozygous microdeletion of the POU1F1, CHMP2B, and VGLL3 genes in chromosome 3--a novel syndrome. American journal of medical genetics Part A 2011, 155A(9):2242-2246 https://doi.org/10.1002/ajmg.a.34136.
12.	Nevado J, Mergener R, palomares bralo M, Souza K, Vallespin E, Cruz R, Martinez-Glez V, Mori M, Santos F, García-Miñaur S et al: New microdeletion and microduplication syndromes: A comprehensive review. Genetics and molecular biology 2014, 37:210-219 https://doi.org/10.1590/S1415-47572014000200007.
13.	Hinrichs AS, Karolchik D, Baertsch R, Barber GP, Bejerano G, Clawson H, Diekhans M, Furey TS, Harte RA, Hsu F et al: The UCSC Genome Browser Database: update 2006. Nucleic Acids Res 2006, 34(Database issue):D590-598 https://doi.org/10.1093/nar/gkj144.


# Citation
If you use this MMS list, please cite: TBD

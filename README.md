# Phylogeny and Comparative Genomics
Supporting material for MMG 801 Lectures on 'Phylogeny and Comparative Genomics.' <br>
[PDF slides not accessible enough? Please reach out to [me](mailto:janani@msu.edu)]

# Learning Objectives
- Phylogeny & Construction of Phylogenetic Trees (species and gene)
- Comparative Genomics & Pangenomes
- In class hands-on demo for two most useful tools:
  - [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) for similarity searches, MSA (multiple sequence alignment) and phylogenetic trees
  - PATRIC for Microbial genomics (esp. as a database)
  - For this, please explore the web-versions for the 'how' + papers to orient you on the 'why' & 'what'
  - Example input files in the [data](https://github.com/jananiravi/2020-phylogeny-compgenomics/tree/master/data) folder: fasta + saved BLAST search strategy.
  - We will address your Qs + use these with the web-tools in class on Thursday!

# Outline
## Lectures 1 & 2 | Phylogenetics
### 2020: [slides](https://drive.google.com/file/d/1rMiWt9N85EOfqAiJ3KOGEiEine_EGDkX/view?usp=sharing) | [video](https://drive.google.com/file/d/1B4HI5IeCmG7rP9F1ATKjdUwLUigVUGnF/view?usp=sharing) | [HW](https://forms.gle/PB2nQXK1NYRadSKD9)
### 2021: [slides](https://drive.google.com/file/d/1Y-ASEVRtDO2YJNtVkVtCj7x7CEQPM9mf/view?usp=sharing) | [HW](https://forms.gle/99Ku7k5uNVfhGALc6)
_PDF, video, homework assignment are all accessible w/ your MSU ID Google login._

- Intro to phylogeny
  - Evolution of desserts
  - _Activity_: Pizza tree
  - Phylogeny and Phylogenetic trees
    - Carl Woese and the three domains of life
    - Bacterial evolution
    - Species trees _vs_ gene trees
      - Homologs, Orthologs, Paralogs
      - Tangled tree
  - Methods to build phylogenetic trees
    - Distance-based methods | UPGMA, Neighbor-joining
    - Character-based methods | Max. parismony, Max. Likelihood, Bootstrap confidence estimation
    - Strengths and Weaknesses of each approach
    - _Qn_: Which alignment is better?
  - Sequence evolution & sequence alignment
    - The amazing Margaret Dayhoff
    - BLOCKS db and BLOSUM substition matrix
    - _Activity_: How do you cluster these? Distance -> Clusters -> Trees
    - _Qn_: Vertical distance in hierarchical rooted trees
  - Gene trees & sequence alignment (w/ BLAST)
    - [NCBI Protein](https://www.ncbi.nlm.nih.gov/protein/)
    - [NCBI BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome)
    - Protein of interest -> [Accession Number -> Fasta sequence] -> BLAST for homologs
    - Demonstration of paralogs vs orthologs w/ [Ravi 2018](https://github.com/jananiravi/psp-actino) actinobacterial PspA tree
  - Tools to explore
    - [iTol: Interactive Tree of Life](https://itol.embl.de/itol.cgi)
    - [TimeTree](http://www.timetree.org)
    - [NextStrain](https://nextstrain.org/ncov/global) for _CoV, Ebola, Dengue, Mtb and more_!
    - For similarity searches: [BLAST](https://blast.ncbi.nlm.nih.gov) (BLASTp, DELTA-BLAST)
    - For multiple sequence alignment: [MUSCLE](https://www.ebi.ac.uk/Tools/msa/muscle/), [T-Coffee](http://tcoffee.crg.cat/), [Jalview](https://www.jalview.org/)
    - For tree building: [FigTree](http://tree.bio.ed.ac.uk/software/figtree/), [FastTree](http://www.microbesonline.org/fasttree/)
    - For phylgoenetic trees using distance-based and character-based methods: [BEAST](http://beast.community/), [MEGA](https://www.megasoftware.net/home)
  - Suggested reading:
    - Review on Phylogenetic Methods | a good overview of the phylogenetic tree-building techniques |
    [Molecular phylogenetics: principles and practice.  Yang Z, Rannala B. Nat Rev Genet. 2012;13(5):303-314.](https://pubmed.ncbi.nlm.nih.gov/22456349/)
    - BLAST Original paper | harder to read |
    [Basic local alignment search tool. Altschul SF, Gish W, Miller W, Myers EW, Lipman DJ. J Mol Biol. 1990 Oct 5;215(3):403-10.](https://www.ncbi.nlm.nih.gov/pubmed/2231712)
    - BLAST | easier to read paper |
    [Steps Used by the BLAST Algorithm. Mount DW. CSH Protoc. 2007 Jul 1;2007:pdb.ip41. doi: 10.1101/pdb.ip41.](https://www.ncbi.nlm.nih.gov/pubmed/21357114)
    - [Wiki: BLAST (biotechnology)](https://en.wikipedia.org/wiki/BLAST_(biotechnology))
    - The book, [Tangled Tree](https://www.goodreads.com/book/show/36373639-the-tangled-tree) by _David Quammen_


## Lecture 3 | Comparative genomics and pangenomes
### 2020: [slides](https://drive.google.com/file/d/1oewDvcQsNrdKQvbELSVme5UaMi7X_SK7/view?usp=sharing) | [HW](https://forms.gle/wXStT447ZSKNtJP78)
### 2021: [slides](https://drive.google.com/file/d/1Y3Wuh7vjGoazt-IzPrVSVmb85dJqwp-2/view?usp=sharing) | [HW](https://forms.gle/1mXxQXhab2wwqv4S7)
- Species trees
- Genome sequencing
- Genome assembly
- Whole genome alignment
- Comparative genomics
- Pangenomes
- PATRIC

# Questions?
- [Email](mailto:janani@msu.edu)
- MSU Microsoft Teams (direct message to: Janani Ravi)
- [2020 Office hours](https://msu.zoom.us/j/92001861449) (202009) at 4p on Friday (Sep 11) and Tuesday (Sep 16)
- 2021 Office hours: Friday 1–2p; Monday 10–11a

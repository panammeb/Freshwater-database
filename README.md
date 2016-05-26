# Freshwater-database 

A microbial database with a taxonomy focused on the typical freshwater clades (built by Didier Debroas)

This dabase was craeted from SILVA NR115 for bacteria and archaea and NR108 for eukaryotes  (Pruesse et al., 2007). 16S and 18S sequences were extracted from the SSURef SILVA database according to the following criteria: length > 1,200 bp, quality score >75% and a pintail value > 50. In addition, the taxonomy of this reference database was modified to take account for the typical freshwater lineages defined in the following works:
Bacteria: 

Newton RJ, Jones SE, Eiler A, McMahon KD, Bertilsson S. (2011). A Guide to the Natural History of Freshwater Lake Bacteria. Microbiol Mol Biol Rev 75:14–49.
Eukaryotes:

Debroas D, Hugoni M, Domaizon I. (2015). Evidence for an active rare biosphere within freshwater protists community. Mol Ecol 24:1236–1247.

Lefranc M, Thénot A, Lepère C, Debroas D. (2005). Genetic diversity of small eukaryotes in lakes differing by their trophic status. Appl Environ Microbiol 71:5935–5942.

Lepère C, Domaizon I, Debroas D. (2008). Unexpected Importance of Potential Parasites in the Composition of the Freshwater Small-Eukaryote Community. Appl Environ Microbiol 74:2940–2949.

Mangot J-F, Debroas D, Domaizon I. (2011). Perkinsozoa, a well-known marine protozoan flagellate parasite group, newly identified in lacustrine systems: a review. Hydrobiologia 659:37–48.


For example in the Taxonomy file (../bd_ssrna/Taxonomy):

FJ827872	Bacteria;Actinobacteria;AcI;AcI-A;AcI-A6;	Actinobacteria

DQ244037	Eukaryota;Alveolata;Perkinsea;Perkinsea_2;	Alveolata

These sequences can be found in the fasta files in the forder:  ../bd_ssrna/Reference_all/Reference_bases/Reference_base_(bacteria|archaea|eukaryota).fasta

With the hmmer profiles and aligned sequences included in this repository, this dabase can be used with PANAM or for a sequence similarity searching  (BLAST, vsearch...)

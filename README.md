# Anti-coronavirus Drugs
Systematic annotation, ontology representation, and analysis of anti-coronavirus drugs

To successfully fight against future coronavirus infections, intensive studies have been undertaken to identify effective and safe drugs. Many drugs have been identified to be effective against the infection of human coronavirus (including SARS-CoV, SAR-CoV-2, and MERS-CoV) in vitro or in vivo in an experimental or clinical setting. A systematic collection, annotation, representation, and analysis of these drugs, including chemical drugs and biological antibodies, would help us better understand the mechanisms under these drugs and facilitate future rational design. With this rationale in mind, we have conducted semi-manual and manual literature collection and annotation of these drugs and perform systematic study on them.  

The Coronavirus Infectious Disease Ontology (CIDO) has been used as an ontological platform to represent the anti-coronaviral drugs, active chemical compounds of these drugs, drug targets, biological processes, viruses, and the relations among these entities. For drug study, CIDO reuses many terms from existing ontologies including ChEBI, DrON, NDF-RT, and GO, and also developed new relations and axioms to semantically link and represent different entities together for integrative representation and analysis. We have also conducted many CIDO-based systematic analysis on our manually annotated anti-coronavirus drugs. 

This research has been primarily conducted at the University of Michigan Medical School, Ann Arbor, MI, USA.

## Developers and collaborators 

Our research team include the following developers and collaborators:  
- Yingtong Liu
- Junguk Hur
- Wallace K.B. Chan
- Zhigang Wang
- Jiangan Xie
- Duxin Sun
- Samuel Handelman 
- Jonathan Sexton
- Hong Yu 
- Jamie Ngai
- Oliver He 

## Our manually annotated data   
- The file includes one sheet for all drugs with at least one ontology ID (ChEBI, NDF-RT, or DrON), one sheet for drugs without ontology ID, and one sheet for antibody. 
- Both sheets for chemical drugs include chemical names in the literatures, ChEBI ID, NDF-RT ID, DrON ID,  Drug Bank ID, names in Drug Bank, targeted virus, potential mechanism, in vitro or in vivo, and PMIDs. 
- There are subtitutes name for some chemicals, which are included in brackets. And for some chemicals, they have the same drug names and ID in Drug Bank. 
- Targeted viruses include SARS-CoV, MERS-CoV and SARS-2-CoV. 
- Potential mechanisms are categoried into inhibition of entry, inhibition of virus replication and modulation on immune response. 
- The sheet for antibody includes name, antigen, in vitro or in vivo, type(monoclonal, or polyclonal), targeted vrius and PMIDs. 

## Analysis results
- Our systematic literature collection and annotation identified 106 chemical drugs and 31 antibodies effective against the infection of at least one human coronavirus (including SARS-CoV, SAR-CoV-2, and MERS-CoV) in vitro or in vivo in an experimental or clinical setting. A total of 168 drug protein targets were identified, and 128 biological processes involving the drug targets were significantly enriched based on a Gene Ontology (GO) enrichment analysis. 
- These 152 anti-coronavirus drugs include 106 active drug compounds that can be mapped to at least one of the three ontologies: ChEBI, DrON, and NDF-RT, 15 drugs that do not have any record in these ontologies, and 31 biological drugs (which are all monoclonal or polyclonal antibodies) specifically targeting on coronavirus proteins (e.g., S protein).
- Our study found that 32 drugs inhibiting viral entry to host cells, 50 drugs that inhibit viral replications inside host cells, and 10 drugs modulating host immune responses to coronavirus infection. 
 

## Methodology  
- Peer-reviewed articles in PubMed, Google Scholar, and PubMed Central literature databases were searched using relevant keywords,. The keywords used in our search includinge: coronavirus, SARS, MERS, CoVID-19, drug, therapy and medicine.Chemical or biological drugs that exhibited anti-coronavirus properties in lab settings were collected from research papers published until May 17, 2020. To be included in our list, each drug was required to demonstrate a significant level of viral inhibition in vitro or in vivo. For in vitro studies, all drugs exhibiting some extent of inhibition (EC50 > 0) are collected. Drugs in clinical studies showing statistical significance (≤ 0.05) are included. For each identified drug, we recorded its targeted virus, mechanism, experimental model, assay, and paper citation(s). Antibodies mentioned in this literature were also recorded with their types and antigens.

## Citation
Liu Y, Chan W, Wang Z, Hur J, Xie J, Yu H, He Y. Ontological and bioinformatic analysis of anti-coronavirus drugs and their Implication for drug repurposing against COVID-19. Preprints. 2020, 2020030413 (doi: 10.20944/preprints202003.0413.v1). 
https://www.preprints.org/manuscript/202003.0413/v1


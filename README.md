# Anti-coronavirus Drugs
Systematic annotation, ontology representation, and analysis of anti-coronavirus drugs

To successfully fight against future coronavirus infections, intensive studies have been undertaken to identify effective and safe drugs. Many drugs have been identified to be effective against the infection of human coronavirus (including SARS-CoV, SAR-CoV-2, and MERS-CoV) in vitro or in vivo in an experimental or clinical setting. A systematic collection, annotation, representation, and analysis of these drugs, including chemical drugs and biological antibodies, would help us better understand the mechanisms under these drugs and facilitate future rational design. With this rationale in mind, we have conducted semi-manual and manual literature collection and annotation of these drugs and perform systematic study on them.  

The Coronavirus Infectious Disease Ontology (CIDO) has been used as an ontological platform to represent the anti-coronaviral drugs, active chemical compounds of these drugs, drug targets, biological processes, viruses, and the relations among these entities. For drug study, CIDO reuses many terms from existing ontologies including ChEBI, DrON, NDF-RT, and GO, and also developed new relations and axioms to semantically link and represent different entities together for integrative representation and analysis. We have also conducted many CIDO-based systematic analysis on our manually annotated anti-coronavirus drugs. 

This research has been primarily conducted at the University of Michigan Medical School, Ann Arbor, MI, USA.

## Developers and collaborators 

Our research team include the following developers and collaborators at the University of Michigan:  
- Yingtong Liu
- Wallace K.B. Chan
- Duxin Sun
- Samuel Handelman 
- Jonathan Sexton
- Yongqun "Oliver" He 

Our collaborators also include: 
- Junguk Hur, University of North Dakota School of Medicine and Health Sciences, Grand Forks, ND 58202, USA. 
- Zhigang Wang, Department of Biomedical Engineering, Institute of Basic Medical Sciences and School of Basic Medicine, Peking Union Medical College and Chinese Academy of Medical Sciences, Beijing 100005, China 
- Jiangan Xie, School of Bioinformatics, Chongqing University of Posts and Telecommunications, Chongqing 400065, China.
- Hong Yu, Department of Respiratory and Critical Care Medicine, Guizhou Province People’s Hospital; Department of Basic Medicine, Guizhou University Medical College, Guiyang, Guizhou 550025, China. 

## Methods    
- Targeted viruses include SARS-CoV (cause of SARS), MERS-CoV (cause of MERS), and SARS-2-CoV (cause of COVID-19). 
- Peer-reviewed articles in PubMed, Google Scholar, and PubMed Central literature databases were searched using relevant keywords. The keywords used in our search includinge: coronavirus, SARS, MERS, CoVID-19, drug, therapy and medicine.Chemical or biological drugs that exhibited anti-coronavirus properties in lab settings were collected from research papers published. To be included in our list, each drug was required to demonstrate a significant level of viral inhibition in vitro or in vivo. For in vitro studies, all drugs exhibiting some extent of inhibition (EC50 > 0) are collected. Drugs in clinical studies showing statistical significance (≤ 0.05) are included. For each identified drug, we recorded its targeted virus, mechanism, experimental model, assay, and paper citation(s). Antibodies mentioned in this literature were also recorded with their types and antigens.
- Drug mechanisms are classified into three categories: inhibition of entry, inhibition of virus replication, and modulation of immune responses. 

## Results
- See the files in our GitHub folder: (i) https://github.com/CIDO-ontology/anti-coronavirus-drugs/blob/master/docs/Anti-coronavirus-chemical-drugs-with_ontoIDs.xlsx; (ii) https://github.com/CIDO-ontology/anti-coronavirus-drugs/blob/master/docs/Anti-coronavirus-chemical-drugs-without_ontoID.xlsx; (iii) https://github.com/CIDO-ontology/anti-coronavirus-drugs/blob/master/docs/Anti-coronavirus-antibodies-without_ontoID.xlsx. These files includes one sheet for all drugs with at least one ontology ID (ChEBI, NDF-RT, or DrON), one sheet for drugs without ontology ID, and one sheet for antibody. Both sheets for chemical drugs include chemical names in the literatures, ChEBI ID, NDF-RT ID, DrON ID,  Drug Bank ID, names in Drug Bank, targeted virus, potential mechanism, in vitro or in vivo, and PMIDs. There are subtitutes name for some chemicals, which are included in brackets. And for some chemicals, they have the same drug names and ID in Drug Bank. The sheet for antibody includes name, antigen, in vitro or in vivo, type(monoclonal, or polyclonal), targeted vrius and PMIDs. 

- Our systematic literature collection and annotation identified 106 chemical drugs and 31 antibodies effective against the infection of at least one human coronavirus (including SARS-CoV, SAR-CoV-2, and MERS-CoV) in vitro or in vivo in an experimental or clinical setting. A total of 168 drug protein targets were identified, and 128 biological processes involving the drug targets were significantly enriched based on a Gene Ontology (GO) enrichment analysis. 

- These 152 anti-coronavirus drugs include 106 active drug compounds that can be mapped to at least one of the three ontologies: ChEBI, DrON, and NDF-RT, 15 drugs that do not have any record in these ontologies, and 31 biological drugs (which are all monoclonal or polyclonal antibodies) specifically targeting on coronavirus proteins (e.g., S protein).

- Our study found that 32 drugs inhibiting viral entry to host cells, 50 drugs that inhibit viral replications inside host cells, and 10 drugs modulating host immune responses to coronavirus infection. 

## Citation
Liu Y, Chan W, Wang Z, Hur J, Xie J, Yu H, He Y. Ontological and bioinformatic analysis of anti-coronavirus drugs and their Implication for drug repurposing against COVID-19. Preprints. 2020, 2020030413 (doi: 10.20944/preprints202003.0413.v1). 
https://www.preprints.org/manuscript/202003.0413/v1


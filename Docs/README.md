**lycopene34: Ortholog scan of ispA in pLYC72I**

What the project is about
The biology and context of the ispA gene
Why you chose your orthologs (biochemical rationale, functional hypotheses, etc.)
Any literature you consulted

The goal of this project is to do an ortholog scan of the ispA gene from the lycopene-producing plasmid pLYC72I and create the necessary files to facilitate the insertion of the orthologs found into pLYC72I. The ispA gene encodes the enzyme farnesyl diphosphate synthase(FPPS), which is essential in the MEP isoprenoid biosynthetic pathway. This pathway leads to the production of biomolecules that are very important for survival, like cholesterol for lipid membrane structure or ubiqionones for cellular respiration. 
  
FPPS is responsible for the condensation of dimethylallyl diphosphate(DMAPP) isopentenyl diphosphate(IPP) to make geranyl diphosphate(GPP), as well as the addition of another IPP to GPP to make farnesyl diphosphate(FPP). 
<img width="618" alt="Image" src="https://github.com/user-attachments/assets/5ea80372-d386-4e2b-a2fc-984ca8354c66" /> The lycopene production pathway (Furubayashi, Maiko, et al.).


**FPPS structural biochemistry**

A search into literature revealed the active site and I-VII conserved regions in FPPS structure that correlate with the efficiency of the enzyme(Szkopińska, Anna, and Danuta Płochocka.). Here are some notable regions that effect FPPS catalysis:
- First aspartic rich motif(FARM): DDXX(XX)D, located in region II, faces SARM in active pocket, binds DMAPP, GPP, or FPP, mutation results in severe loss in catalytic activity.
- Second aspartic rich motif(SARM): DDXXD, located in region VI, faces FARM in active pocket, binds IPP, mutation results in severe loss in catalytic activity.
- FQ located 4bp upstream of SARM: properly positions DMAPP or GPP for condensation with IPP, mutations result in 1,000-100,000 fold decrease in catalytic activity.
- Lysine in region I and V: aids binding of IPP, mutations result in decrease of catalytic activity. 
- Fourth and fifth postion before FARM: effects the chain length determination of the product due to its position at the "bottom" of the active pocket.

*D  = Asp and X = any amino acid


**Selection of the Orthologs**

Eight initial orthologs were chosen that had from 70% to 80% sequence similarity to the original ispA gene:
- _Pectobacterium carotovorum_
- _Yersinia kristensenii_
- _Pantoea agglomerans_
- _Klebsiella pneumoniae_
- _Brenneria roseae_
- _Atlantibacter subterranea_
- _Cronobacter dublinensis_
- _Buttiauxella brennerae_

A phylogenetic tree was made using species names and NCBI, and four of the least related, with each coming from different families, but all from the order _Enterobacterales_, were chosen.
- _Pectobacterium carotovorum_
- _Yersinia kristensenii_
- _Pantoea agglomerans_
- _Klebsiella pneumoniae_




References

Furubayashi, Maiko, et al. “A High-Throughput Colorimetric Screening Assay for     Terpene Synthase Activity Based on Substrate Consumption.” PLoS ONE, vol. 9, no. 3, 28 Mar. 2014, doi:10.1371/journal.pone.0093317. 

Szkopińska, Anna, and Danuta Płochocka. “Farnesyl Diphosphate Synthase; Regulation of Product Specificity.” Acta Biochimica Polonica, vol. 52, no. 1, 31 Mar. 2005, pp. 45–55, doi:10.18388/abp.2005_3485.

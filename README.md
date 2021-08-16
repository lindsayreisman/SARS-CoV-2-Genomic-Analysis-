# Sequence-Analysis-Pipeline-of-SARS-CoV-2

SNPs were mapped to the gene strains using a function to iterate over all the gene strains. Once the mutations were mapped using Entrez from Bio Python, the locus IDs were queried to load the translated coding sequences into a new file. The file then was used as input for Clustalo to perform the Multiple Sequence Alignment (MSA).


# Bioinformatic
These codes are a pre-processing data o in order to get a data that can be inderstood by the machine for model training and extraction of epigenetics biomarkers of a specific diseases,I used genes implicated in diseases as input to determine epigenetic alterations in the entire gene, including its promoter region.
The first step involves selecting the diseases using data processing and analysis tools from the file containing all gene-disease associations in DisGeNET, 
The genes are located in the human reference genome. The input for this step consists of the gene IDs implicated in diseases, and the output is the positioning of the gene in the human genome, including the start and end positions of the gene responsible for the disease. The query is executed automatically by an algorithm that searches the NCBI genetic database using the ID of each gene to retrieve its location on the chromosome.
Epigenomic data representing the positions of epigenetic modifications have been used in the construction of our numerical vectors containing epigenetic modifications for each disease. 
Here I've showed the exctraction of gene methylation, including CpG methylation.

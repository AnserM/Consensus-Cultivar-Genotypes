# Consensus-Cultivar-Genotypes
##This Python notebook is tailored to derive consensus genotypes of cultivars. This is valuable when SNP genotypes originate from diverse sources for the same cultivar.

### Dependencies:
NumPy version: 1.23.5

Pandas version: 2.0.2

### Inputs:

*Genotypes in HapMap format

*txt file containing snp conversion information (change to your species if not working with Glycine max)

*csv file containing VCF header information

### Using the notebook

This notebook is catered to our specific study. Please modify file paths, genotype names,  etc according to your analysis.

### Output

The notebook outputs a VCF file containing consensus genotypes. Before using VCF file for your analysis, run it through bcftools. This makes the VCF file useable for different analysis. 


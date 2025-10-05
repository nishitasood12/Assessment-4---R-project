# EXAMINING BIOLOGICAL SEQUENCE DIVERSITY
SEQUENCE - Salmonella enterica subsp. enterica serovar Weltevreden (GCA_005518735)

## INTRODUCTION 
Comparative sequence analysis is a central tool in molecular biology and evolutionary genomics. By examining coding DNA and protein sequences between different organisms, researchers can uncover functional similarities, evolutionary divergence, and species-specific adaptations (Sharp 1991; Koonin et al. 1995).
In this project, we compared Escherichia coli and Salmonella enterica using their complete sets of coding DNA sequences (CDS). E. coli serves as a model organism with a well-annotated genome, while Salmonella represents a closely related but pathogenic bacterium. The analysis quantifies differences in coding sequence composition, codon usage, and amino-acid patterns, illustrating how sequence diversity reflects evolutionary and functional variation (McClelland & Wilson 1998).
The workflow applies R-based computational methods to quantify genome-wide differences, visualise distributions, and statistically interpret variation following accepted frameworks of biological sequence analysis (Briefings in Bioinformatics 2005).

## PURPOSE 
The aim of this task was to investigate the degree of biological sequence diversity between E. coli and Salmonella enterica by analysing their CDS datasets.
Specific objectives were to:

* Count and compare the number of coding sequences in both organisms.
* Determine the total coding DNA length (genome-wide sum of CDS bases).
* Analyse and compare gene length distributions using boxplots and summary statistics.
* Calculate nucleotide and amino-acid composition frequencies and visualise them with bar plots.
* Construct and compare codon-usage tables, identifying bias and preference patterns.
* Detect over- and under-represented protein k-mers (3–5 aa) and examine their evolutionary implications.

Through this comparative analysis, we gain insights into the molecular evolution, translation efficiency, and genome organisation of closely related bacteria.

## BIOLOGICAL & REAL WORLD SIGNIFICANCE 
1. *Evolutionary Insight* - Comparing coding regions between related species highlights selective pressures, mutation rates, and genetic drift. Sharp (1991) showed that codon-usage bias reflects adaptive evolution in microbial genomes.
2. *Functional Genomics* - Koonin et al. (1995) demonstrated that sequence similarity aids in predicting protein function — a principle mirrored in this study’s codon and k-mer analysis.
3. *Public Health Applications* - Understanding genomic differences between E. coli and Salmonella informs studies of virulence, antibiotic resistance, and vaccine-target discovery (McClelland & Wilson 1998).
4. *Statistical Validation* - Following guidance from Briefings in Bioinformatics (2005), our analysis treats observed sequence biases as statistically testable features, ensuring that biological conclusions are grounded in quantitative evidence.

## INPUTS AND OUTPUTS 
### Input File Description 

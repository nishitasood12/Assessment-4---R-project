# RNA SEQUENCE GENE EXPRESSION AND TREE GROWTH ANALYSIS 

## INTRODUCTION 
Accurate quantification of gene expression is central to understanding how biological systems respond to developmental, environmental, or experimental changes. RNA sequencing (RNA-seq) has become the dominant technology for transcriptome profiling because it enables genome-wide measurement of RNA abundance with high sensitivity and dynamic range (Kukurba & Montgomery 2015).
This R project comprises two complementary bioinformatics exercises designed to build foundational data-analysis skills using authentic biological and environmental datasets:

### 1. Part 1 – RNA-seq Gene Expression Analysis
This section focuses on count-based transcriptomic analysis, where raw sequencing reads are quantified per gene to estimate relative expression levels. It demonstrates how to read, summarise, and visualise RNA-seq count data in R to understand genome-wide transcriptional activity (Anders et al. 2013; Kukurba & Montgomery 2015).

### 2. Part 2 – Tree Growth Analysis
This section applies biostatistical principles to longitudinal environmental data, analysing tree-circumference measurements collected at control and treatment sites over 20 years. It introduces comparison of site-specific growth rates, visualisation via boxplots, and the use of statistical tests such as the t-test to evaluate environmental effects on plant growth.

Together, these parts represent how computational biology integrates quantitative reasoning with real biological questions—from microscopic gene activity to macroscopic ecological patterns. The study mirrors typical workflows used by molecular biologists, ecologists, and data scientists to extract meaningful insights from complex biological data. It emphasizes transparent coding, well-annotated scripts, and reproducible visualization practices—core competencies in modern computational biology.

## PURPOSE 
The goal of this project was to strengthen analytical competency in R for life-science research while reinforcing scientific reasoning and reproducibility. 

* Learn how to import and structure raw RNA-seq count data in R.
* Compute mean gene expression to identify global expression trends.
* Detect highly and lowly expressed genes, providing biological insight into transcript abundance.
* Generate visualisations (histograms) to evaluate expression distribution across the genome.

These steps form the foundation of differential expression analysis workflows such as DESeq2 and edgeR, which rely on raw count data for statistical inference (Rapaport et al. 2013).

## REAL-WORLD SIGNIFICANCE OF THE STUDY 
In research and industry, these analyses provide critical insights

*Gene Expression Analysis* - Understanding transcriptional regulation supports drug-target discovery, disease diagnostics, and biotechnological strain improvement (Anders et al. 2013). It is routinely used in personalised medicine and microbial engineering to identify candidate genes for intervention.

*Growth Analysis* - Quantifying growth trends helps ecologists and agricultural scientists evaluate the effects of climate, soil, and management practices on productivity and sustainability. The ability to implement such pipelines in R demonstrates transferable computational literacy valued across biomedical and environmental sciences.

## INPUTS & OUTPUTS 
### Input Files	Description
1. gene_expression.tsv	- Tab-separated table containing raw RNA-seq read counts. Each row represents a gene, and each column represents a sample. This file serves as the foundation for expression quantification and visualization.
2. growth_data.csv - Longitudinal dataset of tree-circumference measurements collected from Control and Treatment sites over a 20-year period. Each record contains the year, site, and measured circumference.

Each R script contains detailed in-line comments explaining purpose, inputs, and outputs for every code chunk.

### What was done 
1. Imported and explored RNA-seq count data to familiarise with the structure and dimensionality of a real transcriptomic dataset.
2. Computed mean expression values for each gene to quantify overall activity.
3. Identified the top 10 most expressed genes, which likely correspond to core housekeeping or abundant transcripts.
4. Quantified low-expression genes (mean < 10) to highlight potential background noise.
5. Generated a histogram plot to visualise expression distribution and detect skewness or outliers.
6. Documented each step with clear in-line comments, promoting transparency and reproducibility.

### Outcomes of the study 
A complete and reproducible exploratory RNA-seq analysis pipeline in R — from raw count data to summary statistics and visual inspection — forming a solid basis for future differential expression and functional genomics analyses.

## KEY LEARNING OUTCOMES 
* Developed practical skills in R data import, processing, and visualisation.
* Understood how count-based expression summaries form the foundation of DESeq2/edgeR analysis.
* Produced interpretable outputs (tables and plots) ready for reporting or further statistical testing.
* Demonstrated good coding practice with comments and structured chunks.

## RELEVANCE AND FUTURE SCOPE 
This analysis exemplifies the first step in transcriptomic data analysis pipelines used globally in bioinformatics. Understanding how to summarise, visualise, and interpret RNA-seq counts empowers researchers to:
1. Identify candidate genes for functional or differential studies.
2. Build predictive models for disease biomarkers or treatment responses.
3. Integrate gene expression data with other omics layers for systems biology research.
As data volume in biotechnology grows, the ability to perform reproducible R-based analysis is an essential scientific skill.

This project demonstrates the integration of molecular and ecological bioinformatics approaches through reproducible R-based workflows, bridging data analytics with biological interpretation.

## CITATIONS 
1. Anders S, McCarthy D J, Chen Y, Okoniewski M, Smyth G K, Huber W & Robinson M D 2013, Count-based differential expression analysis of RNA sequencing data using R and Bioconductor, Nature Protocols, 8(9): 1765–1786. https://www.nature.com/articles/nprot.2013.099
2. Kukurba K R & Montgomery S B 2015, ‘RNA sequencing and analysis’, Cold Spring Harbor Protocols, 2015(11): pdb.top084970. https://cshprotocols.cshlp.org/content/2015/11/pdb.top084970.short
3. Rapaport F et al. 2013, ‘Comprehensive evaluation of differential gene expression analysis methods for RNA-seq data’, Genome Biology, 14(9): R95. https://doi.org/10.1186/gb-2013-14-9-r95

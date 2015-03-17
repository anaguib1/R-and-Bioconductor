
MMTV_c-MYC
Statistical analysis pipeline using R and Bioconductor to identify discriminant genes in a microarray dataset
-Test for outlier samples and provide visual proof
-Filter out genes that have low expression values using criterion CVs < 5%
-Feature selection with two-sample test – Retain genes with pv < .05
-Visualize the samples in two-dimensional space using dimensionality reduction methods
-Classify the samples using LDA
-Identify gene information for the top 5 discriminant genes

========================================================================================================================

R script cdc15

comparing the transcript profiles from data	set	includes 3 different experiments,
each with its own time course for measuring	transcript levels that are induced by
various cyclins

========================================================================================================================

R script Eisen DLBCL 

identify 2 distinct forms of DLBCL that indicate different stages of B-cell differentiation
using expression profiling and hierarchical clustering 


Calculate the pooled variance, and calculate the minimum sample size necessary to detect a 1.5 fold difference (at 80% power and 99% confidence).

Calculate the sample size required for the selected gene using the empirically determined delta between the two groups, assuming 99% confidence and 80% power.

Load the ssize and gdata libraries, calculate the standard deviation for each gene in the matrix, and plot a histogram of the standard deviations. 

Calculate and plot a proportion of genes vs. sample size graph to get an idea of the number of genes that have an adequate sample size for confidence=95%, effect size=3 (log2 transform for the function), and power=80%.

========================================================================================================================

R script HGU95Av2 array - fibroblast cell lines 

determine clustering and classification in transcript profiles between all 3 species: human, bonobo, and gorilla

hierarchical clustering,  spectral k-means clustering
sample classification

========================================================================================================================

R script  HGU133A array -  breast cancer data

identifying transcripts that were differentially expressed in different histologic grade tumor samples
to evaluate whether gene expression profiling could be used to improve histologic grading


dimensionality reduction (DR) methods to evaluate the amount of variance that is explained by differences in processing sites

========================================================================================================================

R script  lung cancer data 

identifying transcripts that are both differentially expressed 
between different cancer types and normal tissue and can be subsequently used to 
classify unknown tissue into the appropriate cancer type

calculate linear discriminant analysis (LDA)

train a model on a subset of the arrays,
then test the predictability of this model on the remaining arrays, for identifying the
correct cancer (and normal) class

========================================================================================================================

R script RAE230A array - rat KD

determine differences in mRNA levels between brain hippocampi of animals fed a ketogenic diet (KD) and animals fed a
control diet

two-sample test for each gene/probe on the array to identify differentially expressed genes/probes
between ketogenic rats and control diet rats

========================================================================================================================

R script HGU133A array - renal cell carcinoma

molecular pathogenesis of cRCC - normal and stage 1 or stage 2 clear cell renal cell carcinoma (cRCC)

outlier analysis
missing value imputation
assess the accuracy 

========================================================================================================================

R script SLE B Cells

comparing the transcript profiles from peripheral B lymphocytes
between patients with systemic lupus erythematosus (SLE) and normal
healthy controls

========================================================================================================================


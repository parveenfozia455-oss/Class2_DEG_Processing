# DEG Classifier – AI & Omics Internship 2025

This R script processes differential gene expression (DEG) data from two datasets and classifies genes as Upregulated, Downregulated, or Not Significant based on logFC and adjusted p-values.

## Files Included
- `Class2_assign.R`: Main script with comments
- `Results/`: Contains processed data and summary tables

## Classification Logic
- **Upregulated**: padj < 0.05 and logFC > 1
- **Downregulated**: padj < 0.05 and logFC < -1
- **Not Significant**: All other cases

## Output
- Combined summary of both datasets in `combined_summary.csv`

## Submission
Submitted as part of Class 2 assignment for the AI & Omics Research Internship 2025.

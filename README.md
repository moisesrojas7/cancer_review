# cancer_review

GTEx-based gene expression profiling and visualization of tissue-specific differential expression patterns.

The analysis integrates gene expression data from the GTEx Portal ([v10](https://www.gtexportal.org/home/tissueSummaryPage)) with differential expression results to generate heatmaps illustrating tissue-specific expression profiles and transcriptional changes.

## Main features

* GTEx expression profiling: Retrieve RNA-seq expression data for CALHM, connexin, and pannexin gene families across selected human tissues.

* Expression heatmaps: Visualize mean TPM values using log-transformed expression levels and identify tissues with the highest expression variability.

* Differential expression profiling: Generate heatmaps representing tissue-specific gene up/downregulation.

* Log2 fold-change visualization: Compare transcriptional changes across tissues, incorporating statistical significance annotations based on FDR thresholds.

## Input data

The analysis uses GTEx Portal expression data retrieved through the gtexr package, together with preprocessed differential expression results supplied as TSV and XLSX files (```data/``` and ```data_rev/```directories).

## Output

Heatmaps in PNG format, illustrating gene expression patterns, tissue-specific upregulation, and log2 fold-change profiles across human tissues (```plot/``` and ```/plots_rev``` directories).

## R Markdown files

- ```Cancer_analysis.Rmd```
- ```Cancer_analysis_rev.Rmd```

## Author

**Moises A. Rojas**

Laboratory of Genomics and Evolution (MolEvol lab) @ [CINV](https://cinv.uv.cl/) Nov 2026

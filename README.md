# ODBC-GAN: An integrated GAN model for outlier detection and batch correction in multi-sample and multi-modal transcriptomics
We propose a Generative Adversarial Networks called **ODBC-GAN** (**O**utlier **D**etection and **B**atch **C**orrection
**GAN**), which can detect different types of outlier observations (cells or spots), detect the subtypes of outliers further,
and correct batch effects among multi-sample datasets. ODBC-GAN has two main modes (SC and SRT), which can be suitable for
single-cell or spatially resolved transcriptomics dataset. ODBC-GAN in SC mode can solve these problem by gene expression
of cells, and SRT mode combines gene expression, position information, and slice image of spots.

<br/>
<div align=center>
<img src="https://github.com/Catchxu/ODBC-GAN/blob/master/figures/logo.png" width="400px">
</div>
<br/>

## Applicable tasks
- Outlier detection:
  - Detect outlier cells on single-cell datasets.
  - Classify subtypes of the outlier cells.
  - Detect outlier spots on spatial transcriptomics datasets.
  - Classify subtypes of the outlier spots.

- Batch correction:
  - Correct the batch effects among single-cell datasets.
  - Correct the batch effects among vertical slice spatial transcriptomics datasets.
  - Correct the batch effects among horizontal slice spatial transcriptomics datasets.

## Advantages
- Superior performance.
- Integrated outlier detection and batch correction in multi-sample transcriptomic data.
- Avoid negative values after batch correction.
- Keep the original data space after batch correction.
- Applicability to both scRNA-seq and SRT.

## Citation
Coming soon.

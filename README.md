# ODBC-GAN: An integrated GAN model for outlier detection and batch correction in multi-sample and multi-modal transcriptomics
We propose a Generative Adversarial Networks called ODBC-GAN, which can detect different types of observations (cells or spots), 
and correct bacth effects among multi-sample datasets.

## Applicable tasks
- Outlier detection:
 -- Detect outlier cells on single-cell datasets.
 -- Classify subtypes of the outlier cells.
 -- Detect outlier spots on spatial transcriptomics datasets.
 -- Classify subtypes of the outlier spots.

-Batch correction:
 -- Correct the batch effects among single-cell datasets.
 -- Correct the batch effects among vertical slice spatial transcriptomics datasets.
 -- Correct the batch effects among horizontal slice spatial transcriptomics datasets.

## Advantages
- Superior performance.
- Integrated outlier detection and batch correction in multi-sample transcriptomic data.
- Avoid negative values after batch correction.
- Keep the original data space after batch correction.
- Applicability to both scRNA-seq and SRT.

## Tested environment
- CPU: Intel(R) Xeon(R) Platinum 8255C CPU @ 2.50GHz
- CPU Memory: 256 GB
- GPU: NVIDIA GeForce RTX 3090
- GPU Memory: 24 GB
- System: Ubuntu 20.04.5 LTS
- Python: 3.9.15


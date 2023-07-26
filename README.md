# ODBC-GAN: An integrated GAN model for outlier detection and batch correction in multi-sample and multi-modal transcriptomics.
We propose a Generative Adversarial Networks called ODBC-GAN, which can detect different types of observations (cells or spots), 
and correct bacth effects among multi-sample datasets.

## Applicable tasks
Outlier detection:
1. detect outlier cells on single-cell datasets.
2. classify subtypes of the outlier cells.
3. detect outlier spots on spatial transcriptomics datasets.
4. classify subtypes of the outlier spots.

Batch correction:
1. correct the batch effects among single-cell datasets.
2. correct the batch effects among vertical slice spatial transcriptomics datasets.
3. correct the batch effects among horizontal slice spatial transcriptomics datasets.

## Advantages
1. Superior performance.
2. Integrated outlier detection and batch correction in multi-sample transcriptomic data.
3. Avoid negative values after batch correction.
4. Keep the original data space after batch correction.
5. Applicability to both scRNA-seq and SRT.

## Tested environment
- CPU: Intel(R) Xeon(R) Platinum 8255C CPU @ 2.50GHz
- CPU Memory: 256 GB
- GPU: NVIDIA GeForce RTX 3090
- GPU Memory: 24 GB
- System: Ubuntu 20.04.5 LTS
- Python: 3.9.15


# A Parallel Method for Anatomical Structure Segmentation based on 3D Seeded Region Growing

This repository contains the source code to a novel method for the parallel 3D seeded region growing segmentation of anatomical structures, based on GPU architectures.

The results observed with a sample of five CT scans of rodents showed that the method is promising both in terms of efficiency in correctly segmenting the region and in the processing time when compared to a sequential algorithm. 

**Source code**: [jupyter notebook](https://github.com/placerda/region-growing/blob/master/automatic_3d_region_growing_ijcnn.ipynb).

**Dataset**: [rodents CTs](https://drive.google.com/drive/folders/1IzdrMYtHQFH176dkQszdXCGrIBLgb5dK).

Ground truth (manual segmentation): [ground truth](https://drive.google.com/drive/folders/1PuGviaEh8i9Tbdac01P1RyeoZx-yB2yv).

To run this notebook in Colab, please copy the scans folder contents in this GDrive path: **data/ratos/dataset**.

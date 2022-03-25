---
title: "Point Cloud Stacking: A Workflow to Enhance 3D Monitoring Capabilities
  Using Time-Lapse Cameras"
publication_types:
  - "2"
authors:
  - Blanch
  - Xabier
  - Antonio Abellan
  - and Marta Guinau
doi: https://doi.org/10.3390/rs12081240
publication: Remote Sensing
draft: false
featured: false
image:
  filename: https://www.mdpi.com/remotesensing/remotesensing-12-01240/article_deploy/html/images/remotesensing-12-01240-ag.png
  focal_point: Smart
  preview_only: true
summary: his paper presents a new workflow called Point Cloud Stacking
  (PCStacking) that overcomes these restrictions by making the most of the
  iterative solutions in both camera position estimation and internal
  calibration parameters that are obtained during bundle adjustment.
date: 2022-03-25T13:44:04.803Z
---
The emerging use of photogrammetric point clouds in three-dimensional (3D) monitoring processes has revealed some constraints with respect to the use of LiDAR point clouds. Oftentimes, point clouds (PC) obtained by time-lapse photogrammetry have lower density and precision, especially when Ground Control Points (GCPs) are not available or the camera system cannot be properly calibrated. This paper presents a new workflow called Point Cloud Stacking (PCStacking) that overcomes these restrictions by making the most of the iterative solutions in both camera position estimation and internal calibration parameters that are obtained during bundle adjustment. The basic principle of the stacking algorithm is straightforward: it computes the median of the Z coordinates of each point for multiple photogrammetric models to give a resulting PC with a greater precision than any of the individual PC. The different models are reconstructed from images taken simultaneously from, at least, five points of view, reducing the systematic errors associated with the photogrammetric reconstruction workflow. The algorithm was tested using both a synthetic point cloud and a real 3D dataset from a rock cliff. The synthetic data were created using mathematical functions that attempt to emulate the photogrammetric models. Real data were obtained by very low-cost photogrammetric systems specially developed for this experiment. Resulting point clouds were improved when applying the algorithm in synthetic and real experiments, e.g., 25th and 75th error percentiles were reduced from 3.2 cm to 1.4 cm in synthetic tests and from 1.5 cm to 0.5 cm in real conditions
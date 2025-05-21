# CI-3DFScode
The relevant code of CI-3DFS
Overview
Causal Inference-based Three-Dimensional Fluorescence Spectroscopy (CI-3DFS) achieves background interference removal by introducing interventions on data features to preserve true causal features. This repository provides the code implementation of CI-3DFS, which consists primarily of two components:
1）Image preprocessing: baseline correction of dark noise, smoothing, linear interpolation, and removal of Rayleigh scattering.
2）Intervention: training the WGAN, selecting suitable intervention-generated images, and validating true and spurious causal relationship, this is the major computational part, also refered to as CI3DFS.

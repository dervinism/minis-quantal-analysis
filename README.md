[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14288653.svg)](https://doi.org/10.5281/zenodo.14288653)

# minis-quantal-analysis
This repository contains quantal analysis Matlab code for [minis](https://github.com/dervinism/minis) software. It contains all the analysis code required to reproduce main Figures 1, 2, 7-12, and all supplementary figures of the minis quantal analysis [manuscript](https://doi.org/10.1101/2024.07.05.602190).

## Installation Instructions
Download the code repository and add it to the Matlab path, including its subfolders. If you are using Windows, place the code repository in your system's root folder, because ABF files have long names. Subsequently, download the minis benchmarking data [repository](https://gin.g-node.org/dervinism/minis-benchmarking-data2) and the minis quantal analysis data [repository](https://gin.g-node.org/dervinism/minis-quantal-analysis-data) and place them both inside the minis-quantal-analysis [repository](https://github.com/dervinism/minis-quantal-analysis).

Additionally, you must download external code dependencies which include:
- [Circular Statistics Toolbox](https://github.com/circstat/circstat-matlab).
- [Nonparametric circular statistics toolbox](https://github.com/dervinism/circStatNP)
- [dervinism/dervinis-lab-matlab](https://github.com/dervinism/dervinis-lab-matlab)

The analysis code in this repository also depends on the minis software source code. Therefore, you also need to download and install minis [repository](https://github.com/dervinism/minis/tree/main/source_code).

## Instructions for Reproducing Manuscript Figures
Once all the required repositories are downloaded and Matlab path is set up, it is straightforward to reproduce the figures: Simply run ```drawMSFigs.m``` file in Matlab.

## Locating Figures
### Figure 1
```./Fig01/noisePlusSimMinis_p131a```

### Figure 2
```./fitFigures/preprocessingFigures_p103a```

### Figure 7
```./fitFigures/Amplitude_distributions_for_recording_p108b```
```./fitFigures/Rise_time_distributions_for_recording_p108b```

### Figure 8
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p106b```

### Figure 9
```./fitFigures/SourceDistros4pFigures_p131c```

### Figure 10
```./fitFigures/Minis'_incidence_rates```

### Figure 11
```./fitFigures/Fitted_amplitudes_vs_1_capacitance_noTxt```
```./fitFigures/Fitted_vs_subtracted_amplitudes_noTxt```

### Figure 12
```./fitFigures/Generic_minis_distribution```
```./fitFigures/Generic_minis_distribution_rotated```
```./fitFigures/Generic_minis_amplitude_distribution```
```./fitFigures/Generic_minis_10-90%_rise_time_distribution```

### Supplementary Figures 1-13
```./fitFigures/preprocessingFigures_p106b```
```./fitFigures/preprocessingFigures_p108a```
```./fitFigures/preprocessingFigures_p108b```
```./fitFigures/preprocessingFigures_p108c```
```./fitFigures/preprocessingFigures_p120b```
```./fitFigures/preprocessingFigures_p122a```
```./fitFigures/preprocessingFigures_p124b```
```./fitFigures/preprocessingFigures_p125a```
```./fitFigures/preprocessingFigures_p127c```
```./fitFigures/preprocessingFigures_p128c```
```./fitFigures/preprocessingFigures_p129a```
```./fitFigures/preprocessingFigures_p131a```
```./fitFigures/preprocessingFigures_p131c```

### Supplementary Figure 14
```./fitFigures/Amplitude_distribution_fit_for_recording_p131c```

### Supplementary Figures 15-27
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p103a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p108a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p108b```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p108c```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p120b```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p122a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p124b```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p125a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p127c```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p128c```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p129a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p131a```
```./fitFigures/DistroFittingStatsNormalisedRepeatedFigures_p131c```

### Supplementary Figures 1-13
```./fitFigures/SourceDistros4pFigures_p103a```
```./fitFigures/SourceDistros4pFigures_p106b```
```./fitFigures/SourceDistros4pFigures_p108a```
```./fitFigures/SourceDistros4pFigures_p108b```
```./fitFigures/SourceDistros4pFigures_p108c```
```./fitFigures/SourceDistros4pFigures_p120b```
```./fitFigures/SourceDistros4pFigures_p122a```
```./fitFigures/SourceDistros4pFigures_p124b```
```./fitFigures/SourceDistros4pFigures_p125a```
```./fitFigures/SourceDistros4pFigures_p127c```
```./fitFigures/SourceDistros4pFigures_p128c```
```./fitFigures/SourceDistros4pFigures_p129a```
```./fitFigures/SourceDistros4pFigures_p131a```

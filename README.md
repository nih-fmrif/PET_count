[![DOI](https://zenodo.org/badge/146315452.svg)](https://zenodo.org/badge/latestdoi/146315452)

# PET_count

This repository contains the code and data used to estimate the amount of brain PET data that might be available in the world at the end of 2019. We used a search for the terms "brain" and "PET" on [ClinicalTrials.gov](https://clinicaltrials.gov/) and [PubMED](https://www.ncbi.nlm.nih.gov/pubmed) on August 23rd 2018. ClinicialTrials data defined the number of brain PET datasetcs collected in the US and PubMed data was used to calculate the ratio of the number of US brain PET studies to the number of brain PET studies conducted in the rest of the world. This is a rough calculation, and its accuracy depends on the following assumptions:
* US brain PET studies are accurately reported on ClinicalTrials.gov
* PubMed accurately indexes non-US publications
* The number of PET studes conducted is proportional to the number of publications
* The ratio of the number of PET studies conducted to the number of pulications is the same in the US and in the rest of the world
* The median number of subjects in a PET study is the same in the US and the rest of the world
* The primary datasets being shared will be relatively modern datasets collected within the last 5 years
* One subjects worth of brain PET corresponds to 300 MB or 0.0003 TB of data in nifti format

These assumptions are almost assuredly inaccurate, but the estimate we get should still be correct to an order of magnitude or so. We find that 7.13 TB of data was collected between 2013 and 2017 (the last whole year). The yearly rate of collection over this time was 1.43 TB. Thus, we expect that 9.98 TB of brain PET data might be available at the end of 2019.

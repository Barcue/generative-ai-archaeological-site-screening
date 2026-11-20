# Generative AI for Archaeological Site Screening

Code and training imagery associated with the manuscript:

> **Automatic Discovery of Archaeological Sites in Remote Sensing Imagery Using Generative Artificial Intelligence**  
> Qiang Ban, Cheng Su, and Lu Jiang

## Status

**Manuscript under review.** This repository is the public project home for the associated code, training imagery, and reproduction materials. Source code and dataset documentation will be released after the paper is published.

## Project overview

This project investigates sample-free screening of potential archaeological sites in remote sensing imagery using generative background reconstruction. The workflow combines:

- landform-specific generative background reconstruction;
- multiscale analysis at 1, 2, and 4 m spatial resolutions;
- local-window normalized GLCM contrast differences;
- multiscale score integration and candidate-region ranking for expert review.

The method is intended to prioritize candidate areas for archaeological interpretation and field verification, rather than to replace expert judgement or field survey.

## Repository structure

```text
code/     Source code and reproduction scripts (to be released)
data/     Training imagery, metadata, and dataset documentation (to be released)
docs/     Technical documentation and release notes
```

## Planned release

After publication, this repository is intended to include:

- preprocessing and patch-generation scripts;
- landform-specific image reconstruction code and configuration files;
- GLCM difference quantification and multiscale score integration;
- candidate ranking and evaluation scripts;
- training and validation imagery that can be publicly redistributed;
- metadata, checksums, and reproduction instructions.

Model checkpoints will be released where permitted by file size and third-party licensing constraints.

## Data and licensing

The training data are derived from high-resolution optical satellite imagery. All project-generated annotations, metadata, and redistribution-compatible imagery will be released with the code. Where the underlying imagery is subject to third-party licensing, the repository will provide acquisition or extraction instructions instead of redistributing restricted source files. Users are responsible for complying with the relevant imagery-provider terms.

## Citation

A full citation and BibTeX entry will be added after publication.

## Questions

Please use the repository issue tracker for questions about the code or data release.

## Contact

For questions, please open an issue in this repository.

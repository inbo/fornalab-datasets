# ForNaLab occurrence datasets

## Rationale

This repository contains the functionality to standardize several datasets of the [Forest & Nature Lab (ForNaLab)](https://www.ugent.be/bw/environment/en/research/fornalab/fornalab_welcome.htm) to [Darwin Core Occurrence](https://www.gbif.org/dataset-classes) datasets that can be harvested by [GBIF](http://www.gbif.org). These datasets are published in the framework of the project [Forest Microclimate Assessment (FORMICA)](https://formica.ugent.be/).

## Datasets

Title (and GitHub directory) | IPT | GBIF
--- | --- | ---
NA | NA | NA

## Repo structure

The structure for each dataset in [datasets](datasets) is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── data
│   ├── raw                  : Source data, input for mapping script
│   ├── interim              : Derived data for verification GENERATED
│   └── processed            : Darwin Core output of mapping script GENERATED
│
├── src
│   └── dwc_mapping.Rmd      : Darwin Core mapping script
│
└── specs
    └── dwc_occurrences.yaml : Whip specifications for validation
```

## Contributors

[List of contributors](https://github.com/inbo/mica-occurrences/graphs/contributors)

## License

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.

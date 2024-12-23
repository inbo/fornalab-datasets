# ForNaLab datasets

## Rationale

This repository contains the functionality to standardize several datasets of the [Forest & Nature Lab (ForNaLab)](https://www.ugent.be/bw/environment/en/research/fornalab) to [Darwin Core Occurrence](https://www.gbif.org/dataset-classes) datasets that can be harvested by [GBIF](http://www.gbif.org). These datasets are published in the framework of the project [Forest Microclimate Assessment (FORMICA)](https://formica.ugent.be/).

## Datasets

Title (and GitHub directory) | IPT | GBIF
--- | --- | ---
[FORMICA_VEG](https://github.com/inbo/fornalab-datasets/tree/master/datasets/fornalab-formica-wp1-vegetation) | [IPT](https://ipt.inbo.be/manage/resource.do?r=formica_veg) | [GBIF](https://www.gbif.org/dataset/93fb6063-1eb7-463b-abbb-95d828147d19)

## Repo structure

The structure for each dataset in [datasets](datasets) is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── data
│   ├── raw                  : Source data, input for mapping script
│   └── processed            : Darwin Core output of mapping script GENERATED
│
└── src
    └── dwc_mapping.Rmd      : Darwin Core mapping script

```

## Contributors

[List of contributors](https://github.com/inbo/fornalab-datasets/graphs/contributors)

## License

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.

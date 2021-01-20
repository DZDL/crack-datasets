# Crack Datasets: Segmentation & Labelling

Datasets of cracks for deep learning. A standarized way to create a public dataset of fish (imaegs -> labelling -> dataset exports). If you want to add more images create an issue.

## Models trained by the datasets (weights and demo available)


- Crackv1: CRACK9001 (INSER MODEL HERE) - Not ready

# Datasets 

- All datasets available on: (INSER GD LINK) Link to Google Drive ✔️

## Datasets Exports Standardized

Thanks to Roboflow, we can export for different formats: 

- Powered by [CVAT](https://cvat.org/) (All images original size): **JSON** (`COCO`, `Datumaro`), **XML** (`CVAT Image`, `CVAT Video`, `LabelMe`, `PASCAL VOC`), **TXT** (`MOT`, `YOLO`), **JPG,PNG** (`ImageNet`, `Segmentation Mask`), **Others** (`Tensorflow TFRecord`).

Choose just one zip file for one model, select the zip file accord to your model or download all the exports on [release section](https://github.com/DZPeru/fish-datasets/releases)

| Date       | Images      | Classes | Download dataset & Code (TR70/VL20/TS10) |
| ---------- | ----------- | ------- | ---------------------------------------- |
| 2021-01-19 | - (Orig)    | -       | [CRACK9001](#) ✔️                         |


### Downloading and using dataset

Example code to use only with Roboflow [notebooks](https://models.roboflow.com/object-detection) to use the repo and locate correctly.

```
# Instead of doing:
!curl -L "ROBOFLOW LINK" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip
# Use:
!gdown --id "ID OF THE GOOGLE DRIVE ZIP" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip
```

## Resources [Last Update 2020-12-23]

Keywords to find these datasets: fish, trout

### List of datasets found

- 2021-01-19 [Mendeley - Concrete Crack Images for Classification](https://data.mendeley.com/datasets/5y9wdsg2zt/1)

# Contributing

There's a guide to help creating this dataset standardized and exported to a multiple standards. [Click here](./CONTRIBUTING.md)

# License

This repository is under [MIT LICENSE](./LICENSE.md).
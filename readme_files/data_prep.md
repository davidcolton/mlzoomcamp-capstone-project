# Data Preparation

## Dataset Description

This dataset contains images of different kitchenware

The following files are provided

* `train.csv`: the training set (Image IDs and classes)
* `test.csv`: the test set (Just image IDs)
* `sample_submission.csv`: a sample submission file in the correct format
* `images/`: the images in the JPEG format

The dataset was released under the CC0 license: you can use it for any purposes, including commercial.

The images folder provided does not separate the data into a training dataset and a testing dataset. Nor does it separate the training data into the different classes.

Rather than write the code to categorise and separate out the images data, a [Notebook](https://www.kaggle.com/code/davidcolton/kitchenware-dataset-generator/edit) was provide by [clamytoe](https://www.kaggle.com/clamytoe).

See the [data preparation notebook](../notebooks/data_prep.ipynb) for detail of its execution locally.

---

## Results

Following execution of the data preparation notebook we now have the files in the following folder structure:

```bsh
../data/working/images
├── test
└── train
    ├── cup
    ├── fork
    ├── glass
    ├── knife
    ├── plate
    └── spoon
```

With the following image counts:

```bsh
Files in ../data/working/images/test, 3808
Files in ../data/working/images/train/fork, 557
Files in ../data/working/images/train/cup, 1135
Files in ../data/working/images/train/plate, 1227
Files in ../data/working/images/train/glass, 742
Files in ../data/working/images/train/spoon, 989
Files in ../data/working/images/train/knife, 909
Total files: 9367
```
# DL Sprint 2 notebooks
## Training steps:
### Fold Creation :
Train data is splitted into 4 folds. Change `fold` parameter in `CFG` class to create 4 differant folds.
[Fold Creation](fold-creation.ipynb)

### Augmentation :
To create 4 augmented folds, change `fold` parameter in `CFG` class to create 4 folds
[Augmented Fold Creation](augmented-fold-creation.ipynb)

### Full Model Train:
We used [yolov8-960px-badlad-full.ipynb](yolov8-960px-badlad-full.ipynb) for training full model

### Training with augmented data:
We used [yolov8-960px-augmentation-badlad-full.ipynb](yolov8-960px-augmentation-badlad-full.ipynb) to train 4 models. In each model, 1 fold and 1 augmented fold is used in validation and other 3 folds used for training.

## Model Weights
Model weights are stored in [kaggle](https://www.kaggle.com/datasets/asibrahman/dl-sprint-2)
`full` directory contains weight of full model
`aug-fold-{0,1,2,3}` contains 4 models with augmented data

## Inference Notebook
Link : [https://www.kaggle.com/code/asibrahman/rx-7600-dl-sprint-2-inference](https://www.kaggle.com/code/asibrahman/rx-7600-dl-sprint-2-inference)



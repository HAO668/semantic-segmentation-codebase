# semantic-segmentation-codebase
Here is a pytorch codebase for semantic segmentation experiments.


## Installation
- Download the repository.
```
git clone https://github.com/Hao668/semantic-segmentation-codebase.git
```
- Install python dependencies.
```
pip install -r requirements.txt
```
- Create softlink to your dataset. Make sure that the dataset can be accessed by `$your_dataset_path/VOCdevkit/VOC2012...`
```
ln -s $your_dataset_path data
```

## Experiments
Our experiments are placed in `.experiment/` and here are some implementations:
- DeepLabv1 retrain on [DAEN](https://github.com/Hao668/SEAM) pseudo labels. [link](https://github.com/Hao668/semantic-segmentation-codebase/tree/main/daenv1-pseudovoc)


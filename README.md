# Automated Trash Detection Utilizing Computer Vision and Machine Learning
Trash Detector is a Mask R-CNN model that identifies various kinds of trash in a given image.

# How It Works
The model takes in an image as input and draws a segmentation boundary around a piece of trash that belongs to one of the categories that it is trained on.

## Categories of Detectable Trash
At the moment, the model is able to identify trash that has been listed in the TACO dataset. 
The super categories of the trash and their annotations in the dataset are as follows:
![TACO Dataset Stats](https://user-images.githubusercontent.com/102265422/223889114-362d0e52-0dc1-4fd9-be03-3767a2b1b635.png)

# Publications
## Paper Detailing the Dataset and the Tools Used to Support it
https://arxiv.org/abs/2003.06975 

## Citation for Use of the Dataset
```
@article{taco2020,
    title={TACO: Trash Annotations in Context for Litter Detection},
    author={Pedro F Proença and Pedro Simões},
    journal={arXiv preprint arXiv:2003.06975},
    year={2020}
}
```

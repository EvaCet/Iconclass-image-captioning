# Iconclass-image-captioning

The repository contains the data and pretrained model for the task of iconographic image captioning of artwork images.

# Data

The main data source for this project is the IconClass AI test set published here: https://labs.brill.com/ictestset/
The authors of the "Iconclass AI Test Set" provide a set of images together with a json file which includes a list images and corresponding iconclass codes, as well as an Iconclass Python package to perform analysis and extract information from the assigned classification codes. 

The data repo in this repository included the iconclass_descriptions.csv file which contains the list of images from the IconClass AI test set and their coresponding original and processed text descriptions. The processed text descriptions are used as inputs for training and testing the image captioning model (dataset_iconclass_valid.json and dataset_iconclass_76k5k5k.json). 


# Fine-tuning the image captioning model

The weights of the model fine-tuned on the Iconclass Caption dataset are availabe here: https://drive.google.com/file/d/1GJLjqyPhGsa4wcowhy94QnarOjx5vOhp/view?usp=sharing

The model and the fine-tuning settings are implemented based on the Vision Language Pre-training (VLP) model described here: https://github.com/LuoweiZhou/VLP






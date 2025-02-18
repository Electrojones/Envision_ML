# Envision_ML: Environmental monitoring based on computer vision by deep neural networks
![photo_2024-03-14_13-03-58](https://github.com/Electrojones/Envision_ML/assets/26306297/23864041-d7c5-4389-84f9-f2e373e846d8)
**Envision_ML** is a project to investigate the use of deep learning computer vision models to recognize the habitat/ecosystem/biotope type based on pictures.
## Model + Software
It was built using **keras** with a **tensorflow** backend. The current version utilizes **transfer learning** by implementing MobileNetV3 as a pretrained model.
In its first basic version achives **>90%** accuracy, but it only predicts four classes (beech forests, spruce forests, cornfields and streams) and will be expanded in the future.
The current models can be found in [this folder](models). 
## Dataset
The dataset was built by myself based on images that were scraped from online plattforms. Currently, I cannot publish it due to copyright reasons.
## Further development
In practice, the models could be used for large scale monitoring of habitats based on pictures taken by visitors (possibly taken from social media apps) or for an educational app that teaches people about the ecosystem they are exploring.

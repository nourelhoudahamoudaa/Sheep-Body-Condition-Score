# Sheep-Body-Condition-Score
This dataset is designed for Sheep Body Condition Score (BCS) prediction. It contains 5,848 images extracted from videos recorded in controlled conditions at the Higher School of Agriculture in Kef, Tunisia. Images capture sheep from side and rear views, which are essential for assessing body shape and fat distribution.

This dataset was designed to enable the development and evaluation of explainable deep learning models for Sheep Body Condition Score (BCS) prediction.
It serves as the core resource for our proposed methodology. For an in-depth description of the dataset construction, annotation strategy, and experimental framework, please refer to our published paper.

<img width="1256" height="333" alt="image" src="https://github.com/user-attachments/assets/045e77a9-6830-43b9-95fa-df109f500dd0" />

## Abstract
Body Condition Scoring (BCS) is essential for evaluating livestock health, nutrition, and reproduction. For sheep, especially those with long wool, manual scoring requires a level of expertise that many farmers do not possess. Despite its importance, to date, no automated approach has been proposed in the existing literature. In this context, we propose an innovative approach that automatically predicts the BCS of sheep from images, followed by an explainable AI (XAI). The pipeline follows a three-step process: (1) data collection, which was conducted under real-world farming conditions; (2) sheep detection using the Florence-2 object detection model and BCS classification via a Vision Transformer (ViT) trained on 5,848 images (11,000 images after the augmentation), and (3) visual explanation using multiple XAI methods. Our method achieved 72% accuracy using exact BCS class matches and 95% when allowing adjacent classes. This tolerance reflects the variability typically observed among expert scores.

## DOI : 
For full details, see our paper: https://doi.org/10.1007/978-3-032-05060-1_4

## Reference :
@inproceedings{hammouda2025predicting, 

  title={Predicting Sheep Body Condition Scores via Explainable Deep Learning Model}, 
  
  author={Hammouda, Nourelhouda and Mahfoudh, Mariem and Grati, Rima and Boukadi, Khouloud},
  
  booktitle={International Conference on Computer Analysis of Images and Patterns},
  
  pages={37--48},
  
  year={2025},
  
  organization={Springer}
}


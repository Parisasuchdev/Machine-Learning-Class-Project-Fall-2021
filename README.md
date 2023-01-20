# CS254A Final Project

Through this project, we aim to implement an Image Classification model that identifies if a person is wearing a mask correctly or not. It is important to identify this classification problem as it lays the foundation for further research that can be conducted by various research groups using this model. For example, a research team may be interested in finding out the impact of masks on preventing spread and transmission virus. It also can be used in organizations where wearing masks is compulsory and can be used on the entrance protocol such as the screening process or employee sign-in station, which can prevent non-mask-wearers or improper mask-wearers from entering the building. 

We were able to find a 500GB labelled image dataset ([kaggle](https://www.kaggle.com/datasets/tapakah68/medical-masks-part1)), which encompassed images that had labeled image size, photo type, person's age, gender, and user ID (further discussed in Section 2). This project constitutes only a subset of this huge dataset (170GB). Looking at this dataset and the problem statement, we identified that it is multiclass classification model as it is being trained based on four classes:

Class 1 - “The mask is worn correctly, covering the nose and mouth.”

Class 2- “The mask covers the mouth, but does not cover the nose.”

Class 3 - “The mask is on, but does not cover the nose or mouth.”

Class 4: - “There is no mask on the face.”

# Instructions
Clone the project and open and run final-project.ipynb after downloading and extracting the zip below.

## Dataset
Download data-150x150.zip [here](https://drive.google.com/drive/u/0/folders/1rn1G4S36BqzP2FIoQuiycusdiU2tpI6n) and extract it to the cloned project folder.

## Shrink to 50 x 50
If only using data.zip above, you can skip this step.
1. Install [ImageMagick](https://imagemagick.org/index.php).
2. Run ```convert -resize 150x150\! input.jpg output.jpg```.

# Final Report & Presentation
- [project-final-report](https://drive.google.com/drive/u/0/folders/1rn1G4S36BqzP2FIoQuiycusdiU2tpI6n)
- [project-final-presentation](https://drive.google.com/drive/u/0/folders/1rn1G4S36BqzP2FIoQuiycusdiU2tpI6n)

This project was created with the collaboration of: Benjamin Alpert, Parisa Suchdev, Shaurya Swami, Zunyi Liao

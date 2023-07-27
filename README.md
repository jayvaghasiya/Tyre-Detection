# Model Training (Yolo-nas):

# Output

<p align="center">
  <img src="output/tyre.gif" alt="output">
</p>

# Steps :

	1.Data gathering
	
	2.Data Labeling With Autodistill
	
	3.Model Training (yolo-nas)
	
	4.Run the infrence on video
	
	
1. Data gathering and labling is in dataset-generation folder.

2. Model training (yolo-nas)

	* run the command : python train.py
	
	Note: You might need to change the path of the dataset as per your need.
	
	* After training the model file will be stored in checkpoint directory.
	
3. Run the infrence:

	* run the command : python infrence.py
	
	Note: you might need to change the path to the model and video.
	

# Model Evaluation:

<img src="https://github.com/jayvaghasiya/Tyre-Detection/blob/main/Tyre-evaluation/F1_Score.jpg" alt="output" height=350 width=350>
<img src="https://github.com/jayvaghasiya/Tyre-Detection/blob/main/Tyre-evaluation/Precision_Score.jpg" alt="output" height=350 width=350>
<img src="https://github.com/jayvaghasiya/Tyre-Detection/blob/main/Tyre-evaluation/Recall_Score.jpg" alt="output" height=350 width=350>
<img src="https://github.com/jayvaghasiya/Tyre-Detection/blob/main/Tyre-evaluation/mAP_Score.jpg" alt="output" height=350 width=350>


# Football_Data_analysis
Football Data analysis stystem
## Describtion:
computer vision and deep learning to create a football analysis system. This project utilizes YOlO a state of the art object detector to detect the players, referees and footballs. It also utilizes trackers to track those object across frames. We also train our own object detector to enhance the output of the state-of-the-art models.  Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

## Datasets:
kaggle Dataset: [https://www.kaggle.com/competitions/d...](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data?select=clips)
Video link used because Kaggle removed the videos from the kaggle dataset above: [https://drive.google.com/file/d/1t6ag...](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view)
Robowflow Football Dataset: https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/1

## Dependencies:
To run this project, you need to have the following requirements installed:

Python 3.x
ultralytics
supervision
OpenCV
NumPy
Matplotlib
Pandas

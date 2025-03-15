# Football_Data_analysis
Football Data analysis stystem
## Describtion:
computer vision and deep learning to create a football analysis system. This project utilizes YOlO a state of the art object detector to detect the players, referees and footballs. It also utilizes trackers to track those object across frames. We also train our own object detector to enhance the output of the state-of-the-art models.  Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

## Datasets:
kaggle Dataset: [https://www.kaggle.com/competitions/d...](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data?select=clips)
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
![1733495667824](https://github.com/user-attachments/assets/6f02b63c-5797-45e9-a3e5-cda58264f8e3)
![1733495688353](https://github.com/user-attachments/assets/53d14e7a-1888-44b1-b12a-e5b5614ae476)

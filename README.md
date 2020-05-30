# Extracting-Traffic-Data-using-Computer-Vision-Techniques


The aim of this project was to make a Computer vision model capable of assessing detecting vehicular density given an image frame which could be used to adjust the traffic signal durations. The problem statement for the project boils down to detecting vehicles in a given frame.

The morphological approach was unable to beat the fast RCNN method even with limited training(around 1000 iteration) in terms of the number of false negatives. The accuracy was more in the deep learning approach as compared to the morphological approach. Increasing the the number of training iterations also significantly improved the performance.

We achieved visually good results especially in the morphological approach.The Deep learning approach was very accurate in terms of the correct detections. If trained for a longer time the model would have reduced the False Negatives.There were many issues we faced and observed. Some of them included the fact that the image quality in the dataset was very low, The model we developed was not robust to densely placed vehicles and could not distinguish between a car which was far or a nearby pedestrian in the morphological approach. 

# imu_to_terrain_classification
ECE 542: Neural Networks Project

One avenue of prosthesis control that still needs to be improved on is its capability to adjust to changing terrain. Able-bodied people can easily adjust with the use of sight or touch.  However, with prosthetics, the controller is separate from the human, meaning that the amputee cannot real-time adjust for a rapid change in terrain.  This project, in conjunction with a class and few professors, Dr. Edgar Lobaton and Dr. Helen Huang, looks to classify terrain based on IMU Data.	The four different terrains analyzed here were flat ground, going up a set of stairs, going down a set of stairs, and grass (states 0, 1, 2, and 3, respectively).

Data collection was done as indicated in their article and the IMU data as well as terrain was provided to us. A Deep Convolutional Neural Network was developed as our final model with the architecture shown below. The dropout layers were added between the 2D convolutional and max pooling layers to prevent overfitting. This model achieved an accuracy of 80.9% on our validation data and a Validation F1 Score of 0.922191.

You can download the full report, datasets, and code below.

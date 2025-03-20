# Project-Ref-for-HKET
Project reference
Project Name: Video to Vector
Function: To able to calculate the similarity between two videos
Skill Used: Python

There are two parts in this small project. As described in the function, This project is to calculate the similarity between two videos by extracting features of images from the videos and using embedding function to generate a video vector that can represent those features of the images and compare to other video vectors.

Although this project is not using dataset including videos, dataset called Caltech101 including different images is used to simulate images extracted from the videos. Those images will be splited into groups as videos. The first part is to extract features from images of Caltech101 dataset . If you run all the codes, you should able to see predicted class of images in the last.

The second part is to use the embedding function to generate a video vector that can represent those features of the images so that it can compare to other video vectors by using consine similarity. The project result is not good as you can see the similarity is not obvious enough to say that two specfic videos are similar, but it can be improved.

# Action Recognition using Convolutional Neural Networks
Trained Convolutional Neural Networks in PyTorch for classification images and videos of human actions.  

# Dataset
Used UCF101 data `http://crcv.ucf.edu/data/UCF101.php` but took only 10 classes of 101 classes.
Each clip has 3 frames and each frame is 64 ∗ 64 pixels. The label of clips are in `hw6_data.mat`. `trLb` are labels for training clips and `valLb` are labelsfor validation clips. 

Trained CNN to classify the action in each image. Then, CNN is trained using 3D convolution to classify each clip as a video instead of image.



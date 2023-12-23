# Malaria-Detection-Using-Deep-Learning

- Blood_Smear_GNN_Final_Varun.ipynb : contains code for drawing the bounding boxes using K-Means Clustering method. I also constructed a graph with the bounding box inputs of each image and used a GNN.
- WBC/RBC weights.ipynb: Using the bounding boxes information, I have constructed a graph using WBC/RBC ratio information. 
- PointGNNCode_3D.ipynb : In this, I tried to load the velodyne and LiDAR dataset that was used in the Point GNN research paper. This colab was utilised to understand the different code blocks mentioned in their repository.
- Point_GNN_2D.ipynb: I have tried to construct a point graph using the pixel level information present in the malaria blood smear(currently working on this).
- Vision_GNN_Experiment.ipynb: I have experimented with dividing the input images into different patches using the Patchify library, and tried with the construction of a graph
- Vision_GNN_Final.ipynb: Contains the code for the neural network design along with the training loop

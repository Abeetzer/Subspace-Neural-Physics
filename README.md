# Subspace-Neural-Physics
This is my implementation of Daniel Holden's work on Neural Networks that can simulate physics in 3D for video games 

# How to get started:
using Maya or any simulation software, you should be able to extract the vertex positions of the mesh using a python script while its moving through time in frames per second. I set the FPS to 60 and did around 20,000 frames total. once I collected all of the frames, I flattened them into a one one dimensional array using a method called Principle Component Analysis(PCA) . All of my code from pre-processing to training is included in the .ipynb file and can run on google Colab. 



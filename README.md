# Poisonous Plant Identifier

 Identifies common poisonous plants in the given input.

![add image descrition here](direct image link here)

## The Algorithm

The algorithm was given a few thousand pictures of common poisonous plants in order to attemp to identify them. 80% of the pictures have been used to train the network while the rest is used to test and evaluate the training pictures. It can only identify three plants, specifically the Atlantic Poison Oak, the Eastern Poison Ivy and the Poison Sumac. This algorithm runs on a 4 GB Jetson Nano with the a pre-trained model that was modified to identify these plants.

## Running this project

2. Make sure to include any required libraries that need to be installed for your project to run.

1. Make sure you have Visual Studio Code installed
2. Open VS Code and click the bottom-left icon in the corner
3. Select Connect to Host and add a new SSH host
4. Type ssh nvidia@(insert I.P adress). The I.P adress is the one for your Jetson Nano

[View a video explanation here](video link)

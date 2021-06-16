Step 1: Download the images from https://public.roboflow.com/object-detection/hard-hat-workers and store it in the folder raw_yolo_keras in two folders, train and test

Step 2: Run the PreProcess.ipynb notebook, this will read the images in train and create two folders inside train , no_helmet and yes_helmet. THe same notebook will also read the images in test and create two folders inside test, no_helmet and yes_helmet, each containing respective images.

Step 3: Execute the ModelTrain.ipynb notebook. This sill create the model and save it in the models folder. Create the models folder at the top level in case it is not there.

Step 4: Run the Person_HardHatDetection.ipynb to check the efficacy of the model. The images downloaded from the internet are stored in the end_end_test folder. This code reads the images from that folder and gives the output.

Note: face_recognition model needs dlib to be installed, the instructions can be found at https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf
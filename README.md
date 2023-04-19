# Sketch_to_Face
Hey! Here's my repo that generated face images from hand-drawn sketches. Feel free to dive in
<br>
I have shared my code, The dataset can be downloaded from Chinese HongKong university website, it is called the CUFSF dataset, it has 188 real face images and its corresponding hand drawn sketches. <br>
I would encourage you to download more images of this type with different ethinicity and face structure that would give it variety and differences which could help model learn more vivid and varied patterns to generate good human faces, Integrate this idea and if you put it on GIT notify and tag me, I would love to see the predictions.
<br>
About the dataset, initially they are (200,250,3) which can be resized to (256,256,3) , we do not have enough data and so we gotta augment them side by side, so we don't lose track of the respective sketches. <br>
Next, we define the downsample for encoder where we'll use conv layer to capture and extract features and upsample for decoder layers which will use conv transpose layer which will bring back the image spatial dimension, we will implement Batch Normalization and drop out to try and boost our accuracy. 
<br>
I had previously tried this for 300 epochs, which could trace the hair and a little bit of skin, so I tried increasing epochs upto 700 which did trace a bit more than previous one.<br>
Hence it's important to get more data, have variety, perform trial and error on architecture, increase the number of epochs. <br> performing these steps can kick up your accuracy. <br>

I WANTED TO UPLOAD MY ENTIRE FOLDER, WITH DATASETS, WELL, ITS TOO HUGE.</BR>
HAVE FUN BUILDING THIS GUYS!

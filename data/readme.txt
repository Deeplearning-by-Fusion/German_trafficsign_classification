This folder contains the dataset used in this project.

I used German Traffic Sign Recognition Benchmarks dataset, which consists of morethan 50,000 images of 43 labels.

Data can be downloaded from [here](https://drive.google.com/drive/folders/1Sk3-4-oLbZxrNjlO9CdqzMuJ-zbljXOV?usp=sharing)

The data is avialbale in pickle format, it is a dictionary with 4 key-value pairs
  1. 'features' - is a 4D array containing raw pixel data of the images (n_examples, width, height, channels)
  2. 'labels' - 1D array containing classID of the image
  3. 'sizes' - list containg tuples(width,height)
  4. 'coords' - list containg tuples(x1,y1,x2,y2) representing coordinates of the bounding box around the sign in the image.

### **Introduction**
In this project I intend to produce a classification model based on data I have labeled  and its ultimate goal is to be applied on hyperspectral images:

My dataset contains $\approx$**10000** samples where each sample (=row) contains values ​​of 204 different pixel wavelengths in hyperspectral images of a vertical green wall. 
The wall contains six different species and from each image I collected hundreds of pixels that I labeled according to the plant species.
I actually have 204 features (= columns) and what I want to predict using them is the plant species (labels).

After creating a classification model at a sufficient level, I can run the model on all the images I have and predict for each pixel which species it represents.

### **Project stages**

1. Read the several files of data and merge them into one file.

2. Preprocessing and Visualization

3. Build the models and evalute

4. Apply the model on new images

5. Reduce the number of bands and try to classify the species by RGB+NIR bands. 

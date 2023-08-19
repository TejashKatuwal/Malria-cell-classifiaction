# Downloading the Dataset
Use the following codes to download the dataset from the drive as shown in the figure.
![dataset_download](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/e63ad254-db2f-4bb4-8440-f5b6d9a979d1)

# Unzip the files
The downloaded file is in zip format so unzip the dataset using the following lines of codes.
![unzip](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/dae827f7-481c-4038-9540-6db9e5e42dda)

# TRAINING
# Spliting the data
Before training the dataset we must split the data into two groups (training set and validation set). We split the dataset randomly, usually 80% of data is 
used as training set and 20% as validation set.
![splitting the data](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/2d2a10d1-dd8d-45d5-a686-e3115bfa4f19)


# Augmentation
Augmentation is the process of shifting the metrics of data like rotating, cropping to enhance the number of training data and as a result of that the accuracy.
Here the following code is doing the augmentation process.
![augmentation](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/d268e488-e3ed-45c7-b124-7da803d8c69b)

# CNN 
Now setting up the convolution layer. For binary classification i.e where we have only two labels to classify we use binary crossentropy as shown in the code.
![CNN](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/ba793a10-2f54-4f64-910f-87e453523f28)

# Epochs
Here we ran only 10 epochs because of fairly smaller dataset. If you have a larger dataset atleast go for 100 epochs.
![Epochs](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/1bc0f15b-7525-4d01-a501-28e2b0755323)

# Plotting
Finally we plot the loss graph and accuracy graph as shown in the figure.
  # Loss Plot
  ![loss plot](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/b8f6e656-3b47-4965-b1ee-72570804aaf3)

  # Accuracy Plot
  ![accuracy plot](https://github.com/TejashKatuwal/Malria-cell-classifiaction/assets/118622724/e8ba09c4-7e1c-4eb4-8321-6d605782c30a)


  



# Real-vs-Fake-Face-Detection

Dataset - https://www.kaggle.com/hamzaboulahia/hardfakevsrealfaces

## Context
The motivation behind the creation of this dataset is to have a challenging Test set for the task of classifying fake and real human faces. Most of the available datasets on Kaggle are "Uniform" and doesn't present a good variance of face features, particularly for the "Fake" class. Moreover, the fake faces collected in this dataset are generated using the StyleGAN2, which present a harder challenge to classify them correctly even for the human eye. The real human faces in this dataset are gathered so that we have a fair representation of different features(Age, Sex, Makeup, Ethnicity, etc…) that may be encountered in a production setup.

Total number of images: 1288
Number of "Fake" faces: 700
Number of "Real" faces: 589

The data.csv contains the images Id and the corresponding label.
## Real images
Below are some of the real images from the data set
</br>

![Screenshot 2022-03-09 121507](https://user-images.githubusercontent.com/52671445/157387107-5e515830-dd2f-4ec6-ae1d-b8a386227d13.jpg)
</br>
## Fake images
Below are some of the fake images from the data set
</br>
We can clearly observe these images are not easy to classify using the naked eye
</br>
</br>
![Screenshot 2022-03-09 121252](https://user-images.githubusercontent.com/52671445/157386908-4c9bb4d4-76dc-4b74-bd1b-24dd99aa6510.jpg)
</br>
## Training curves for 100 epochs
</br>
![Screenshot 2022-03-09 121338](https://user-images.githubusercontent.com/52671445/157386912-baac65bc-02b3-4d37-b138-08657110efa3.jpg)
</br>
## Model predictions visualized
</br>
</br>
![Screenshot 2022-03-09 121323](https://user-images.githubusercontent.com/52671445/157387856-5fcad9f3-f24a-483d-b410-ecd5751a6348.jpg)


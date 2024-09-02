# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## General Information
- This assignment uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.
- We are using simple CNN models using keras to form a sequential of layers and trained a model accordingly



## Conclusions
- On the First Iteration of model training Model is overfitting because model has higher accuracies on training data but failing on test data
- On the Second Iteration of model training we added Dropout layer with 0.5 rate but Model is still overfitting because model has higher accuracies on training data but failing on test data
- On the Third Iteration of model training we added Data Augmentationto balence the data but Model is performing well!
- Conclusion 4 from the analysis




## Technologies Used
- Keras
- Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@joseph.rapaka] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
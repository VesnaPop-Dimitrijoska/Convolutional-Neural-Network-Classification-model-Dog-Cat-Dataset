# Project Title:
Convolutional Neural Network Dogs vs Cats Classification. 
#
---
# Project Description:
Experimenting with a couple of different Convolutional Neural Network architectures for binary classification of cats and dogs.  
#
---
# Table of Contents:

  1. Data Analysis
  2. Data Augmentation
  3. Model Training
  4. Model Hyperparameter Optimization
  5. Model Prediction
  6. Model Evaluation
  7. Results Analysis
  8. Conclusion
#
---
# Dataset:
Database contains 37500 pictures of cats and dogs. 25000 pictures have notation, and test set of 12500 pictures was witout notation.

---
# RESULTS
####
![image](https://github.com/VesnaPop-Dimitrijoska/Convolutional-Neural-Network-Classification-model-Dog-Cat-Dataset/assets/144008804/0b7c2074-e85a-45fd-b475-0bff2d9f329a)


## Conclusion

The model was significanlty improved by using Data augmentation technique which is increasing the amount of data available for training by generating new training examples from existing ones and applying some transformations.

I tested multiple architectures and one of the best performance was achived with the model shown here.

Тhanks to the Train-Validation-Test split, I was able to evaluate the model, because test data set was without notation. 

By picking 25 random images from the test set, it can be observed that 24 of them were accurately predicted.

![image](https://github.com/VesnaPop-Dimitrijoska/Convolutional-Neural-Network-Classification-model-Dog-Cat-Dataset/assets/144008804/1c09bac0-6852-4202-baaa-20fab9e411aa)


---
#
# License
MIT License
#



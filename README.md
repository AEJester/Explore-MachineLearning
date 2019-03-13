# Machine Learning and its Applications
A repository for code that I have developed to coincide with the Explore #2 Task for MobileCSP

---
## Introduction
Machine Learning can be implemented and intertwined inside of all aspects of society today. It can be seen in facial recognition in police work, it can be seen to analyze patterns in data for large corporations, and it can even be seen in your phone to help process tasks easier. Data is fed into the algorithm and subsequently processed in the neural network layers defined before the compilation of the model. It is then able to find patterns and apply them to the other images. It works on a basis of rewards and punishment. If the pattern gives them an incorrect output, it takes the new image, and analyzes it for other patterns. It does this until it has a pattern that can apply to each type and classification of image. For the handwritten digit dataset, it will get a pattern for each number (0-9). The same is true for clothing items, but with different labels.

## Applications
#### Handwritten Digits
An algorithm such as [this](https://github.com/AEJester/Explore-MachineLearning/blob/master/digit_recognizer.py) can be proven very viable in a practical real-world scenarios such as when one may find themselves having to transcribe numbers into a spreadsheet. It would be extremely beneficial for enabling a user to use their mouse or a drawing pad and a specialized application to help transcribe numbers faster than you could originally do so with a keyboard and fingers. It uses the [MNIST dataset](http://yann.lecun.com/exdb/mnist/) that consists of 70,000 (60,000 training, 10,000 testing)  28x28 pixel images to feed into the model.

This model trains to a ~97% accuracy rating after 10 epochs. Upon testing the model, it can achieve the exact same rating of ~97%.

#### Clothing Items
An algorithm such as [this](https://github.com/AEJester/Explore-MachineLearning/blob/master/clothing_recognizer.py) has even more practical uses in the real world. To provide one example, one could implement this into an online store to automatically classify clothing items as you add them to said website or app. It uses the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset to analyze them again 70,000 images (60,000 training, 10,000 testing) to find patterns. 

This model trains to a ~90% accuracy rating after 10 epochs. Upon testing the model, It achieves a rating of ~88%.

## Conclusion
Machine Learning and Neural Networks can be very useful everyhere, as I have demonstrated by the above. Although these are very simple, it gives a clear understanding of how they can be used in today's society.

Citation information:

Published on: March 13th, 2019

Author: Ryan Monaghan Jr.

Article title: Machine Learning and its Applications

Website title: Machine Learning in society

URL: https://github.com/AEJester/Explore-MachineLearning

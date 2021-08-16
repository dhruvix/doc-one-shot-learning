# System for Identity document image classification and template creation using Siamese networks

Classifying images of documents is an important business task and doing it manually is very cumbersome and time-consuming. Training accurate machine learning models to do this requires large amounts of data that might sometimes not be available. We have developed a system that automatically classifies images of identity documents with a high degree of accuracy even after being trained on a small dataset, using the concept of one-shot learning and Siamese networks. The system also creates and stores templates for all the different classes of identity documents to use for future comparisons. Additionally, it can accommodate new classes dynamically, thereby removing the necessity of having to retrain the entire model whenever a new class is introduced.

### System architecture 
<img src="/images/system architecture.png">

### Siamese Networks diagram
<img src="/images/Siamese networks.jpg">

### Sample output
We took two images, belonging to a known class (passport) and an unknown class, gave them to our system and plotted the output vectors we obtained. The 4 vectors on the left are the outputs for the known class's  image and the 4 vectors on the right are the outputs for the unknown class's image.

<img align="center" src="/images/download.png">

<img src="/images/ku-avg.JPG">

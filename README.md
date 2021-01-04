# orAIza
Paddy Disease Detection App 



# Basic Overview
<img align="center" src='https://github.com/m2i101/OrAIza/blob/master/img/paddy.jpeg'>

More than a billion people live in smallholder farmer households worldwide, and many of these farmers struggle with avoidable pest damage that can wipe out up to 50% of annual paddy crop yield. Abundant use of chemicals such as bactericides, fungicides, and nematicides to control plant diseases has been causing adverse effects in the agro-ecosystem. Currently, there is a need for effective early disease detection techniques to control plant diseases for food security and the sustainability of the agro-ecosystem. In this project, as farmers and agriculture program workers take regular photos of pest disease traps, AI models on their phones classify and detect the pest diseases. The data will be used to provide millions of farmers with timely, localized advice to reduce pesticide usage and improve the yield.This app can help quickly identify paddy diseases and provide treatment information, taking us one step closer to better economic and food security.

# About The Project
An android application is developed using a deep learning model with the transfer learning technique. Around 4500 images of plant leaves have been analyzed, which have a spread of 4 class labels assigned to them. Each class label is a paddy pest disease such as Brownspot, Hispa, Leaf Blast. These are considered as some of the major paddy diseases. An attempt is made to predict the disease given just the image of the plant leaf. A deep learning-based CNN architecture is proposed to detect and classify paddy diseases. The advancement and novelty of the developed model lie in its simplicity; healthy leaves are in line with other classes, enabling the model to distinguish between diseased leaves and healthy ones or from the environment by using CNN. The popular architecture, namely Inception V3 is a widely-used image recognition model that has been shown to attain greater than 78.1% accuracy on the ImageNet dataset. 
The model is then retrained by freezing some of its layers by fine tuning.This approach is called transfer learning. The tensorflow model is then quantized to tensorflow lite model and then deployed on to a Mobile device through Android Studio application.

# Workflow of project
accessibility text

 


This project was created under the Deloitte TechnoUtsav3.0 TechE contest.


# Authors

Manikanta Varaganti - Initial work - orAIza

Aakanksha Thota - Initial work - orAIza

Sai Santhosh Belide - Initial work - orAIza

# Sign-Language-Recognition

![image](https://user-images.githubusercontent.com/78852322/118490785-ec479600-b73b-11eb-802f-565486d71f72.png)

## What is Sign Language?
Here Sign Language refers to the standardised American Sign Language. It is a complete, natural language that has the same linguistic properties as spoken languages, with grammar that differs from English. ASL is expressed by movements of the hands and face. It is the primary language of many North Americans who are deaf and hard of hearing, and is used by many hearing people as well.

## Motivation
Hand gesture is one of the methods used in sign language for non-verbal communication. It is most commonly used by deaf & dumb people who have hearing or speech problems to communicate among themselves or with normal people. Various sign language models have been developed by many makers around the world but they are neither flexible nor cost-effective for the end users. Hence, we introduced a model that is able to automatically recognize sign language to help deaf and dumb people to communicate more effectively with each other or normal people.

## Objective
In this project, a CNN model which classifies the different signs in American Sign Language is built without the use of pre-trained models. Basically, using a basic CNN architecture to understand the working behind the convolutional neural networks. This model takes 28x28 image as input and predicts the sign. 

## Dataset
American Sign Language (ASL) is a complete, natural language that has the same linguistic properties as spoken languages, with grammar that differs from English. ASL is expressed by movements of the hands and face. It is the primary language of many North Americans who are deaf and hard of hearing, and is used by many hearing people as well. The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1, pixel2…. pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. 

Link: https://www.kaggle.com/datamunge/sign-language-mnist

![image](https://user-images.githubusercontent.com/78852322/118491258-6e37bf00-b73c-11eb-8679-ee2862a5e463.png)

The python notebook has all the details to understand the basic use of CNN for image recognition and the visualization of intermediate layers which illustrates how it processes the data to produce accurate results.

Kindly read my medium article regarding this repo: https://medium.com/@rajannoel/visual-question-answering-c5c46f97dc72

# What is this repo about: 
Imagine checking out a shoe in a store and say, you need answers to specific questions such as, “Is this an original brand ?” or “Do these shoes last long?”.
Now, imagine having an application which can answer all such questions.

Visual question answering systems attempt to correctly answer questions in natural language regarding an image input. Visual Question Answering (VQA) is a recent problem in computer vision and natural language processing that has garnered a large amount of interest.

# How to use this repo:
Visual Question Answering using transfer learning and co-attention models

- How to use the final_model.h5 file for visual question answering?
Use the "VQA_Final_Model_Evaluations_Predictions.ipynb" file. Load the final_model.h5 file to the same folder as the python notebook. Also load the image/images in the same folder. Now you can enter your question/questions and image paths and execute the functions for model prediction/evaluation as needed.

- VQA_EDA.ipynb covers all the Exploratory Data Analysis we have done for this problem statement

- VQA_Modelling.zip file can be downloaded and unzipped to access the VQA_Modelling.ipynb file. This file details the featurizations, model training etc that we have done for a wide range of models including transfer learning models and co-attention model.

# Business Problem:
In VQA Dataset from www.visualqa.org, the computer system needs to address different problems, such as, binary classification problems (Are they all adult elephants?), counting problems (How many elephants are in the picture?), or an open-ended question (What part of the elephants are touching?)

# Introduction:
Historically, building a system that can answer natural language questions about any image has been considered a very ambitious goal. It requires combining visual and language understanding. A model that solves this task demonstrates a more general understanding of images: it must be able to answer completely different questions about an image, oftentimes even addressing different sections of the image. While I will use some pretrained models, I have also innovatively built and trained a co-attention model using Xception model based image features.

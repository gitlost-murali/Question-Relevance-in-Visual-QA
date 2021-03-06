# Question-Relevance-in-VQA
Repository for ongoing core project "Determining Question Relevance in the context of VQA".

Questions:

http://visualqa.org/data/mscoco/vqa/v2_Questions_Train_mscoco.zip

http://visualqa.org/data/mscoco/vqa/v2_Questions_Val_mscoco.zip

http://visualqa.org/data/mscoco/vqa/v2_Questions_Test_mscoco.zip

Answers:

http://visualqa.org/data/mscoco/vqa/v2_Annotations_Train_mscoco.zip

http://visualqa.org/data/mscoco/vqa/v2_Annotations_Val_mscoco.zip

VQG Image Captioning file generates natural questions about the image.

**Clustering_questions/** folder contains codes for extracting question and answer types from question-answer instances. And to create a dataset to train a model which predicts the type of question. This additional information can be used to figure out existential and counting questions, as these questions are anyway relevant to the image.

# Generating natural questions from image examples ("VQG_Captioning/")

View them <a href='https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/'> here</a>. I feel that the model with 3.1248 loss has reasonable questions generated. Now take a look at the model with 3.0077 loss below,

![alt_text](https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/loss_3.0077_47acc/5.PNG)
![alt_text](https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/loss_3.0077_47acc/6.PNG)
![alt_text](https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/loss_3.0077_47acc/7.PNG)
![alt_text](https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/loss_3.0077_47acc/8.PNG)
![alt_text](https://github.com/Murali81/Question-Relevance-in-Visual-QA/blob/master/VQG_Captioning/tested_samples/loss_3.0077_47acc/9.PNG)

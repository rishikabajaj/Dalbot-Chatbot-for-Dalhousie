# ChatBot- ML6505 - Group 17

Repository for ML project group 17

Our bot is trained using training data in which it takes input in terms of tags and classifies responses to return one of the responses as the output. Our chatbot will use a simple feed forward neural net with 2 hidden layers. We will create our model which is a feed forward neural net with 2 hidden layers.  Our model would get our bag of words as an input, then we have one fully connected layer which would have different patterns as the input size, then 2 hidden layers and the output size must be the number of different classes. Finally, we apply the Softmax function and get probabilities for each class.

## Final Submission
Our final project submission includes two project files- Cosine_Similarity_Chatbot.ipynb & ML_Project_-_Chatbot.ipynb, 2 data files - chatbotData.json & test_intents.json and a data.pth file which is our saved model. 

ML_Project_-_Chatbot.ipynb file has the implementation of Chatbot using feed forward neural network whereas we have used cosine similarity to implement the chatbot application in the Cosine_Similarity_Chatbot.ipynb file. The data files chatbotData.json & test_intents.json has data in json format for train and validation respectively which we have used to generate synthetic dataset in our project.

To run the project, simply download and run the notebooks and the data files in Jupyter notebook.

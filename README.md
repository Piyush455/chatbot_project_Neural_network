# chatbot_project_Neural_network

# Smart Chatbot Using NLTK and Keras
|Written by Rupam Goyal ,Piyush Malhotra, Aboli

In this Neural Network Project, we build a chatbot using deep learning methods. The chatbot will be trained in a database that contains categories (objectives), patterns and responses. We use a special recurrent neural network (LSTM) to distinguish the domain of a user’s message and provide a random response to a response list.
In this project we build a retrieval chatbot using NLTK, Keras, Python, etc.
# 1) What is Chatbot?
A chatbot is a smart piece of software that can communicate and perform human-like actions. Chatbots are widely used in customer communication, marketing on social networking sites and sending instant messages to the client. There are two basic types of discussion models depending on how they are constructed; Retrieval based and Generative based models. \n
# a. Retrieval based Chatbots
Recovery dialogue uses pre-defined input patterns and responses. It then uses a certain type of selection method to select the correct answer. It is widely used in the industry to create goal-oriented conversations where we can customize the tone and flow of chatbot to drive our customers with a positive feeling.
# b. Chatbots based on Generative 
These models are not based on other previously defined responses.
They are based on seq 2 seq neural networks. It is the same concept as machine translation. In machine translation, we translate source code from one language to another language but here, we will convert input to output. Requires a large amount of data and is based on deep neural network.
# 2) Dataset Used
The dataset we use is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the answers we want to get back to the user.

# 3) Prerequisites
Before reading the post, some concepts of Keras, good knowledge of Python, and Natural language processing (NLTK).Also the reader must be familiar with the basic Python syntax, data structures, Keras Library, working on Google Colab etc.
# 4) Model generation
For this project let us see the file structure and the type of files created:
Intents.json — The data file which has predefined patterns and responses.
train_chatbot.py — In this Python file, we wrote a script to build the model and train our chatbot.
Words.pkl — This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
Classes.pkl — The classes pickle file contains the list of categories.
Chatbot_model.h5 — This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py — This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.
For this project we have used Five steps to create a chatbot:

# Natural-Language-Processing

Natural language processing (NLP) is the ability of a computer program to understand human language as it is spoken and written -- referred to as natural language. It is a component of artificial intelligence (AI).Natural language processing (NLP) refers to the branch of computer science—and more specifically, the branch of Artificial Intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can. NLP combines computational linguistics—rule-based modeling of human language—with statistical, machine learning, and deep learning models NLP drives computer programs that translate text from one language to another, respond to spoken commands, and summarize large volumes of text rapidly—even in real time. There’s a good chance you’ve interacted with NLP in the form of voice-operated GPS systems, digital assistants, speech-to-text dictation software, customer service chatbots, Machine Translation i.e. Google Translator, Information retrieval, Summarization, Sentiment Analysis, Social Media Analysis, Mining large data and other consumer conveniences. But NLP also plays a growing role in enterprise solutions that help streamline business operations, increase employee productivity, and simplify mission-critical business processes





![image](https://user-images.githubusercontent.com/101402562/189334883-b58a1b06-96cd-47db-8683-99ce765849e4.png)



## Recurrent Neural Network (RNN)



![image](https://user-images.githubusercontent.com/101402562/189335057-dc1d4b3b-0ee9-4725-b8e1-2b50fdc246c9.png)



Recurrent Neural Network (RNN) are a type of Neural Network where the output from previous step are fed as input to the current step. In traditional neural networks, all the inputs and outputs are independent of each other, but in cases like when it is required to predict the next word of a sentence, the previous words are required and hence there is a need to remember the previous words. Thus, RNN came into existence, which solved this issue with the help of a Hidden Layer. The main and most important feature of RNN is Hidden state, which remembers some information about a sequence. RNN have a “memory” which remembers all information about what has been calculated. It uses the same parameters for each input as it performs the same task on all the inputs or hidden layers to produce the output. This reduces the complexity of parameters, unlike other neural networks.

## Long Short-Term Memory (LSTM)

![image](https://user-images.githubusercontent.com/101402562/189335192-b95c6e8a-3067-477b-8ac5-cb5f93b1a8f0.png)


Long Short-Term Memory (LSTM) is a kind of recurrent neural network. In RNN output from the last step is fed as input in the current step. LSTM was designed by Hochreiter & Schmidhuber. It tackled the problem of long-term dependencies of RNN in which the RNN cannot predict the word stored in the long-term memory but can give more accurate predictions from the recent information. As the gap length increases RNN does not give an efficient performance. LSTM can by default retain the information for a long period of time. It is used for processing, predicting, and classifying on the basis of time-series data.

# Deep-Learnings


### What is Deep Learning?

Deep Learning is a machine learning technique that constructs artificial neural networks to mimic the structure and function of the human brain. In practice, deep learning, also known as deep structured learning or hierarchical learning, uses a large number hidden layers -typically more than 6 but often much higher - of nonlinear processing to extract features from data and transform the data into different levels of abstraction (representations). 

As an example, assume the input data is a matrix of pixels. The first layer typically abstracts the pixels and recognizes the edges of features in the image. The next layer might build simple  features  from the edges such as leaves and branches. The next layer could then recognize a tree and so on. The data passing from one layer to the next is considered a transformation, turning the output of one layer into the input for the next. Each layer corresponds with a different level of abstraction and the machine can learn which features of the data to place in which layer/level on its own. Deep learning is differentiated from traditional “shallow learning” because it learns much deeper levels of hierarchical abstraction and representations.


### Why is Deep Learning Important?

This learning technique is a groundbreaking tool for processing large quantities of data, since the performance of the machine improves as it analyzes more data.  As the amount of data increases, the machine becomes more adept at recognizing even hidden patterns among the data. Because the machine is also learning from the processed data, it is able to perform feature extraction and abstraction automatically from the raw data with little to no human input.

### Practical Uses of Deep Learning

Automatic Speech Recognition – All major commercial speech recognition systems (think your smart phone assistant) use a deep learning technique with recurrent neural networks currently being the most popular.
Computer Vision – Images are used to train the machine to recognize features and now the machines are demonstrating “superhuman” accuracy for image recognition.
Natural Language Processing – Modern deep learning techniques have led to improvements in translation and language modeling. Google Translate uses deep learning techniques to translate based on the semantics of an entire sentence instead of just memorizing phrase-to-phrase translations.



# Automatic Speech Recognition

### What is Automatic Speech Recognition?
Speech Recognition is a subfield of computational linguistics that is concerned with recognition and translation of spoken language into text by computers, sometimes referring to the process as "speech to text." The systems are the combination of influence from linguistics, computer science, and electrical engineering. The term "speech recognition" itself refers to the more broad process of translating spoken word into text, however subfields such as voice recognition and speaker identification are specialized to identify both the spoken content ad the identity of the speaker.

### How does Automatic Speech Recognition work?
Speech Recognition systems are split into two main categories; speaker dependent and speaker independent. Speaker dependent systems are structured such that they require training, sometimes referred to as "enrollment." This works by having a speaker reading text, or a series of isolated vocabulary, into the system. Then, the system will process the vocal recordings and associate them with the text library. Some speech recognition systems do not rely on vocal training and are known as speaker independent systems.


![6804dee0-c510-4731-8a29-55de17b09d19](https://user-images.githubusercontent.com/57901189/91671869-950c8180-eb2a-11ea-9953-a77dfc0dd49e.png)

### Machine Learning and Speech Recognition
Neural Networks can be used to approach the task of automatic speech recognition with decent performance. The networks initially began with a limited skillset, in which they often were used in classifying short-time units such as isolated words and phonemes. However, over time, the neural networks' increase in complexity, as represented in LSTM networks, has led to increased performance.

Another form of machine learning model used is called an Attention Based Model (ASR). These systems attempt an end-to-end approach to speech recognition. For example, Carnegie Mellon University created a model dubbed the "Listen, Attend and Spell" (LAS). The model listens to the audio signal, then pays attention to different parts of the signal, before then spelling out the signal via transcript one letter at a time. Attention based models are able to process information that more traditional models cannot, such as pronunciation. Since the initial inception of the LAS model, additions have been supplemented to increase the abilities of the LAS model. For example, Google's DeepMind extended LAS to become a "Watch, Listen, Attend and Spell" model in which the network is able to read and decode lip reading, often surpassing human-level performance. 

### What is a Recurrent Neural Network?

A Recurrent Neural Network is a type of neural network that contains loops, allowing information to be stored within the network. In short, Recurrent Neural Networks use their reasoning from previous experiences to inform the upcoming events. Recurrent models are valuable in their ability to sequence vectors, which opens up the API to performing more complicated tasks. 


![9ce02363-a7d7-49a7-a9a4-0e02687e7356](https://user-images.githubusercontent.com/57901189/91778586-3d861880-ebf3-11ea-998d-53ab7f74a51b.jpg)


### How do Recurrent Neural Networks work?

Recurrent Neural Networks can be thought of as a series of networks linked together. They often have a chain-like architecture, making them applicable for tasks such as speech recognition, language translation, etc. An RNN can be designed to operate across sequences of vectors in the input, output, or both. For example, a sequenced input may take a sentence as an input and output a positive or negative sentiment value. Alternatively, a sequenced output may take an image as an input, and produce a sentence as an output.


![354d3cf7-ef89-41ba-b158-d6e2a9772728](https://user-images.githubusercontent.com/57901189/91778594-437bf980-ebf3-11ea-95e6-1b14abc8270b.png)


Let's imagine training a RNN to the word "happy," given the letters "h, a, p, y." The RNN will be trained on four separate examples, each corresponding to the likelihood that letters will fall into an intended sequence. For example, the network will be trained to understand the probability that the letter "a" should follow in the context of "h." Similarly, the letter "p" should appear after sequences of "ha." Again, a probability will be calculated for the letter "p" following the sequence "hap." The process will continue until probabilities are calculated to determine the likelihood of letters falling into the intended sequence. So, as the network receives each input, it will determine the probability of the subsequent letter based on the probability of the previous letter or sequence. Over time, the network can be updated to more accurately produce results.


### Recurrent Neural Network Applications

A common example of Recurrent Neural Networks is machine translation. For example, a neural network may take an input sentence in Spanish and translate it into a sentence in English. The network determines the likelihood of each word in the output sentence based upon the word itself, and the previous output sequence.


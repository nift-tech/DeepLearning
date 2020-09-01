# Automatic Speech Recognition

### What is Automatic Speech Recognition?
Speech Recognition is a subfield of computational linguistics that is concerned with recognition and translation of spoken language into text by computers, sometimes referring to the process as "speech to text." The systems are the combination of influence from linguistics, computer science, and electrical engineering. The term "speech recognition" itself refers to the more broad process of translating spoken word into text, however subfields such as voice recognition and speaker identification are specialized to identify both the spoken content ad the identity of the speaker.

### How does Automatic Speech Recognition work?
Speech Recognition systems are split into two main categories; speaker dependent and speaker independent. Speaker dependent systems are structured such that they require training, sometimes referred to as "enrollment." This works by having a speaker reading text, or a series of isolated vocabulary, into the system. Then, the system will process the vocal recordings and associate them with the text library. Some speech recognition systems do not rely on vocal training and are known as speaker independent systems.


![6804dee0-c510-4731-8a29-55de17b09d19](https://user-images.githubusercontent.com/57901189/91671869-950c8180-eb2a-11ea-9953-a77dfc0dd49e.png)

### Machine Learning and Speech Recognition
Neural Networks can be used to approach the task of automatic speech recognition with decent performance. The networks initially began with a limited skillset, in which they often were used in classifying short-time units such as isolated words and phonemes. However, over time, the neural networks' increase in complexity, as represented in LSTM networks, has led to increased performance.

Another form of machine learning model used is called an Attention Based Model (ASR). These systems attempt an end-to-end approach to speech recognition. For example, Carnegie Mellon University created a model dubbed the "Listen, Attend and Spell" (LAS). The model listens to the audio signal, then pays attention to different parts of the signal, before then spelling out the signal via transcript one letter at a time. Attention based models are able to process information that more traditional models cannot, such as pronunciation. Since the initial inception of the LAS model, additions have been supplemented to increase the abilities of the LAS model. For example, Google's DeepMind extended LAS to become a "Watch, Listen, Attend and Spell" model in which the network is able to read and decode lip reading, often surpassing human-level performance. 


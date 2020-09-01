# What is a Recurrent Neural Network?

A Recurrent Neural Network is a type of neural network that contains loops, allowing information to be stored within the network. In short, Recurrent Neural Networks use their reasoning from previous experiences to inform the upcoming events. Recurrent models are valuable in their ability to sequence vectors, which opens up the API to performing more complicated tasks. 


![9ce02363-a7d7-49a7-a9a4-0e02687e7356](https://user-images.githubusercontent.com/57901189/91778586-3d861880-ebf3-11ea-998d-53ab7f74a51b.jpg)


### How do Recurrent Neural Networks work?

Recurrent Neural Networks can be thought of as a series of networks linked together. They often have a chain-like architecture, making them applicable for tasks such as speech recognition, language translation, etc. An RNN can be designed to operate across sequences of vectors in the input, output, or both. For example, a sequenced input may take a sentence as an input and output a positive or negative sentiment value. Alternatively, a sequenced output may take an image as an input, and produce a sentence as an output.


![354d3cf7-ef89-41ba-b158-d6e2a9772728](https://user-images.githubusercontent.com/57901189/91778594-437bf980-ebf3-11ea-95e6-1b14abc8270b.png)


Let's imagine training a RNN to the word "happy," given the letters "h, a, p, y." The RNN will be trained on four separate examples, each corresponding to the likelihood that letters will fall into an intended sequence. For example, the network will be trained to understand the probability that the letter "a" should follow in the context of "h." Similarly, the letter "p" should appear after sequences of "ha." Again, a probability will be calculated for the letter "p" following the sequence "hap." The process will continue until probabilities are calculated to determine the likelihood of letters falling into the intended sequence. So, as the network receives each input, it will determine the probability of the subsequent letter based on the probability of the previous letter or sequence. Over time, the network can be updated to more accurately produce results.


### Recurrent Neural Network Applications

A common example of Recurrent Neural Networks is machine translation. For example, a neural network may take an input sentence in Spanish and translate it into a sentence in English. The network determines the likelihood of each word in the output sentence based upon the word itself, and the previous output sequence.




# What is a Neural Network?


An artificial neural network learning algorithm, or neural network, or just neural net, is a computational learning system that uses a network of functions to understand and translate a data input of one form into a desired output, usually in another form. The concept of the artificial neural network was inspired by human biology and the way neurons of the human brain function together to understand inputs from human senses. 

Neural networks are just one of many tools and approaches used in machine learning algorithms. The neural network itself may be used as a piece in many different machine learning algorithms to process complex data inputs into a space that computers can understand. 

Neural networks are being applied to many real-life problems today, including speech and image recognition, spam email filtering, finance, and medical diagnosis, to name a few. 


### How Does a Neural Network Work?
Machine learning algorithms that use neural networks generally do not need to be programmed with specific rules that define what to expect from the input. The neural net learning algorithm instead learns from processing many labeled examples (i.e. data with with "answers") that are supplied during training and using this answer key to learn what characteristics of the input are needed to construct the correct output. Once a sufficient number of examples have been processed, the neural network can begin to process new, unseen inputs and successfully return accurate results. The more examples and variety of inputs the program sees, the more accurate the results typically become because the program learns with experience.  

This concept can best be understood with an example. Imagine the "simple" problem of trying to determine whether or not an image contains a cat. While this is rather easy for a human to figure out, it is much more difficult to train a computer to identify a cat in an image using classical methods. Considering the diverse possibilities of how a cat may look in a picture, writing code to account for every scenario is almost impossible. But using machine learning, and more specifically neural networks, the program can use a generalized approach to understanding the content in an image. Using several layers of functions to decompose the image into data points and information that a computer can use, the neural network can start to identify trends that exist across the many, many examples that it processes and classify images by their similarities. 


<img width="320" alt="b920b4b3-7347-4712-b1bd-068775ec4562" src="https://user-images.githubusercontent.com/57901189/91778849-19770700-ebf4-11ea-84f1-70593949f387.png">

   ###### (image is taken from a Google Tech Talk by Jeff Dean at Campus Seoul on March 7, 2016)



After processing many training examples of cat images, the algorithm has a model of what elements, and their respective relationships, in an image are important to consider when deciding whether a cat is present in the picture or not. When evaluating a new image, the neural net compares the data points about the new image to its model, which is based off of all previous evaluations. It then uses some simple statistics to decides whether the image contains a cat or not based on how closely it matches the model.

In this example, the layers of functions between the input and the output are what make up the neural network. In practice, the neural network is slightly more complicated than the image above shows. The following image captures the interaction between layers slightly better, but keep in mind that there are many variations of the relationships between nodes, or artificial neurons:

![6ab1bb72-ad28-480e-bb1c-4dd419843762](https://user-images.githubusercontent.com/57901189/91778842-167c1680-ebf4-11ea-8885-73e0d54a34a7.png)


### Applications of Neural Networks
Neural networks can be applied to a broad range of problems and can assess many different types of input, including images, videos, files, databases, and more. They also do not require explicit programming to interpret the content of those inputs.

Because of the generalized approach to problem solving that neural networks offer, there is virtually no limit to the areas that this technique can be applied. Some common applications of neural networks today, include image/pattern recognition, self driving vehicle trajectory prediction, facial recognition, data mining, email spam filtering, medical diagnosis, and cancer research. There are many more ways that neural nets are used today, and adoption is increasing rapidly. 


# inverse_cooking
This model allows you to know how a dish came to life. The ingredients, the process, everything that was reqd. to make it from an image of the dish itself.
If you are already an ML learner or even a beginner in this field, you might have thought of how this model was built.
Well the first thing that comes to mind is image recognition of the food and then predicting the dishes on the model trained on a large dataset. 

Congratulations,
if you've thought along these lines you have made a good invesment of your time in this field. But you are half right. Though indeed we did an image prediction on the images, we instead of an entire inage were more focused on the ingredient pipeline..
# OVERVIEW
Food is something without which life cannot survive. We need food to help us going through our lives. It is a nature’s gift to all the lifeforms present on the earth. As we know cooking is not just a task anymore. The society has built a career over it and people are flowing into that stream of jobs to build their lives. Especially in the country of India where it’s diversified and extravagant cultures have given birth to a number of dishes and tastes for the palette of each and every human being. And coming forward to this age of technology and digitized media, the society now lives in the digital world much more openly than in the real one. Facebook, Instagram and Pinterest have all been the pillars of highlighting a person’s life that normally wouldn’t have been visible to others or even their own selves in the first place. As such a person’s eating style, his cooking pattern, his taste culture was only limited to the person himself. In the older days, when food was only cooked in people’s homes, now a days, with the advancement of one’s lifestyle leading to them having no time to cook look for eating outside as per their requirements. And so, now more than ever, it has become an imperative need for one to know the detailing of the cooked food they eat. However, it is difficult if not impossible to know the exact makings of the food one ingests and so this makes it all the more evident that a person is in need of a system that will identify the makings of a dish right to the grains.	


The models that were previously built on food recognition was based on a retrieval system that took out the ingredient embeddings from the image. This resulted in poor results as most of the initial ingredients prepared before cooking are completely unrecognizable in the end. The resulting change in the texture and colour of the dish also made it impossible to produce accurate results. Also, the prediction relied heavily on the variety and diversity of the dataset and how accurately the cross-embedding were built. In the end, the recipe classification produced poor results since accurate ingredients presented as sets were unable to match properly or lacked a corresponding image object for it to correspond with.


Therefore, with the help of this model one is able to procure the recipe and name of the dish depicted in the image. In this model, we have produced a method for extracting the details of the dish using two modalities: the ingredients and the image of the food itself. Using these two modalities together, this model is able to achieve the higher threshold of accuracy in comparison to the previously built models.
# Materials and Methods:-

# Feedforward Neural Network
A feedforward neural network is a part of the ANN (Artificial Neural Network) family. It’s a simple structured neural network that has only unidirectional flow of information originating from the input node to the target nodes via the hidden layers. This neural network has no feedback loops and is a single-layer perceptron consisting of a single layered output node. The inputs have associated weights that are used to modify the values accordingly.


# Recurrent Neural Network
 An RNN also belongs to a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behaviour. Unlike feedforward neural networks, RNNs can use their internal state (memory) to process sequences of inputs. This makes them applicable to tasks such as unsegmented, connected handwriting recognition or speech recognition

# LSTM
Long short-term memory is an artificial neural network that finds its main usage in the field of deep learning. They differ from the feedforward neural networks. LSTM supports feedback connections which almost makes it work like a Turing Machine. LSTM can not only handle images efficiently but also other multimedia files (audio, video, etc.).  LSTM is applicable in both speech and image recognition modules having varied capabilities.

# What is Anaconda Navigator?

 
Anaconda Navigator is a graphical interface UI (GUI) incorporated into Anaconda® corporation that enables you to dispatch applications and effectively supervise conda packages, situations and channels without utilizing direction line directions. Pilot can look for bundles on Anaconda Cloud or in a nearby Anaconda Repository. It is accessible for Windows, macOS, and Linux. 
So as to run, numerous logical packages rely upon explicit adaptations of different packages. Developers frequently utilize various forms of numerous packages, and utilize various conditions to isolate these various adaptations. The direction line program conda is both a package manager and a domain administrator, to help programmers guarantee that every edition of each package has every one of the conditions it requires and works accurately. 
#METHODS:
Due to the failure of previous models in the field of accuracy of ingredient prediction, these food prediction models were not making much progress even with the advancement of high-level algorithms and accuracy in predictive modelling.

  Instead of predicting the food preparing process without an intermediary in between to process the minute details, this model makes use of a pipeline containing the necessary parameters for the analysis and prediction of the ingredients and the recipe. As depicted in the figure above, instead of thinking of all ingredients present together as a set, this model actually considers them as a list. After all, one can presume that the ingredients are ordered and always put into the dish sequentially according to the recipe. Hence, to include that facet into our approach this project used both the list and set form of ingredients and trained the model over both parameters.
 


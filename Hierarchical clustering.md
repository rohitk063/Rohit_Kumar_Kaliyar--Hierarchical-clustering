# Hierarchical Clustering

In data mining and statistics, hierarchical clustering (likewise called various leveled bunch investigation or HCA) is a technique for cluster analysis which tries to fabricate a chain of hierarchy of clusters.Hierarchical  clustering can be arranged into two; agglomerative (bottom-up) and divisive (top-down) clustering which are clarified with the names AGNES, and DIANA.Hierarchical clustering builds a cluster hierarchy, or in other words, a tree of clusters.Hierarchical clustering outputs is structured and more informative than flat clustering.Hierarchical clustering does not require knowing the pre-specified number of clusters. To understand better first we have to understand about clustering and same is mentioned below:-
## Clustering
Clustering is a division of information into gatherings of groups  of  similar  objects. Speaking to the data by less bunches fundamentally loses certain fine subtle elements, however accomplishes disentanglement. It demonstrates information by its groups. Information displaying places grouping in a verifiable point of view established in science, measurements, and numerical analysis. From a machine learning point of view clusters  compare to concealed patterns, the look for clusters is unsupervised learning, and the subsequent framework speaks to an information idea. From a reasonable point of view clustering assumes an extraordinary part in data mining applications, for example, logical information retrieval , data recovery and content mining, spatial database applications, Web mining, CRM,marketing, medicinal diagnostics, computational science, and numerous others.
* [rohit paper](https://scholar.google.co.in/scholar?hl=en&as_sdt=0%2C5&q=graph+databases+a+survey+by+rohit&oq=graph+databases+) - The web framework used
## Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Evolution of the approach with related work](#evolution)
- [Algorithm with mathematical notations and diagrams](#algorithm)
- [Example problem with the solution](#examples)
  - [Librairies and Implementations](#librairies-and-implementations)
- [Applications](#applications)
  - [Gradient Descent Algorithms and optimization](#gradient-descent-algorithms-and-optimization)
- [Discussion](#discussion)
  - [Recurrent Neural Networks](#recurrent-neural-networks)
  - [Convolutional Neural Networks](#convolutional-neural-networks)
- [Landmark research papers in the topic](#landmark)
- [Resources such as book, code, relevant softwares, libraries, other tutorials,links to video lectures etc](#resources)
- [References](#references)

<a name="trends" />

## Abstract

## Introduction

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## History/evolution of the approach with related work

## Algorithm with mathematical notations and diagrams

## Example problem with the solution
## Applications
## Discussion
## Landmark research papers in the topic
## Resources
### Books

- [How to Create a Mind](https://www.amazon.com/How-Create-Mind-Thought-Revealed/dp/B009VSFXZ4) - The audio version is nice to listen to while commuting. This book is motivating about reverse-engineering the mind and thinking on how to code AI.
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html) - This book covers many of the core concepts behind neural networks and deep learning. 
- [Deep Learning - An MIT Press book](http://www.deeplearningbook.org/) - Yet halfway through the book, it contains satisfying math content on how to think about actual deep learning.
- [Some other books I have read](https://books.google.ca/books?hl=en&as_coll=4&num=10&uid=103409002069648430166&source=gbs_slider_cls_metadata_4_mylibrary_title) - Some books listed here are less related to deep learning but are still somehow relevant to this list.
### Code

- [Hierarchical Clustering - MATLAB & Simulink](https://in.mathworks.com/help/stats/hierarchical-clustering-12.html?s_tid=gn_loc_drop) - Hierarchical clustering groups data into a multilevel cluster tree or dendrogram. If your data is hierarchical, this technique can help you choose the level of clustering that is most appropriate for your application.
- [Agglomerative hierarchical cluster tree](http://in.mathworks.com/help/stats/linkage.html) - This MATLAB function returns a matrix Z that encodes a tree of hierarchical clusters of the rows of the real matrix X...
- [Deep Learning - An MIT Press book](http://www.deeplearningbook.org/) - Yet halfway through the book, it contains satisfying math content on how to think about actual deep learning.
- [Some other books I have read](https://books.google.ca/books?hl=en&as_coll=4&num=10&uid=103409002069648430166&source=gbs_slider_cls_metadata_4_mylibrary_title) - Some books listed here are less related to deep learning but are still somehow relevant to this list.
## References
- [Hierarchical clustering schemes](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) - Abstract Techniques for partitioning objects into optimally homogeneous groups on the basis of empirical measures.
- [Bidirectional Recurrent Neural Networks](http://www.di.ufpe.br/~fnj/RNA/bibliografia/BRNN.pdf) - Better classifications with RNNs with bidirectional scanning on the time axis.
- [Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078v3.pdf) - Two networks in one combined into a seq2seq (sequence to sequence) Encoder-Decoder architecture. RNN Encoder–Decoder with 1000 hidden units. Adadelta optimizer.
- [Sequence to Sequence Learning with Neural Networks](http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf) - 4 stacked LSTM cells of 1000 hidden size with reversed input sentences, and with beam search, on the WMT’14 English to French dataset.
- [Exploring the Limits of Language Modeling](https://arxiv.org/pdf/1602.02410.pdf) - Nice recursive models using word-level LSTMs on top of a character-level CNN using an overkill amount of GPU power.
- [Exploring the Depths of Recurrent Neural Networks with Stochastic Residual Learning](https://cs224d.stanford.edu/reports/PradhanLongpre.pdf) - Basically, residual connections can be better than stacked RNNs in the presented case of sentiment analysis.
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf) - Attention mechanism for LSTMs! Mostly, figures and formulas and their explanations revealed to be useful to me. I gave a talk on that paper [here](https://www.youtube.com/watch?v=QuvRWevJMZ4).
- [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/pdf/1502.03044.pdf) - LSTMs' attention mechanisms on CNNs feature maps does wonders.
- [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf) - Exploring different approaches to attention mechanisms.
- [Neural Turing Machines](https://arxiv.org/pdf/1410.5401v2.pdf) - Outstanding for letting a neural network learn an algorithm with seemingly good generalization over long time dependencies. Sequences recall problem.
- [Teaching Machines to Read and Comprehend](https://arxiv.org/pdf/1506.03340v3.pdf) - A very interesting and creative work about textual question answering, what a breakthrough, there is something to do with that.
- [Pixel Recurrent Neural Networks](https://arxiv.org/pdf/1601.06759.pdf) - Nice for photoshop-like "content aware fill" to fill missing patches in images.
- [Adaptive Computation Time for Recurrent Neural Networks](https://arxiv.org/pdf/1603.08983v4.pdf) - Let RNNs decide how long do they compute. I would love to see how well would it combines to Neural Turing Machines. Interesting interactive visualizations on the subject can be found [here](http://distill.pub/2016/augmented-rnns/).
- [Hybrid computing using a neural network with dynamic external memory](http://www.nature.com/articles/nature20101.epdf?author_access_token=ImTXBI8aWbYxYQ51Plys8NRgN0jAjWel9jnR3ZoTv0MggmpDmwljGswxVdeocYSurJ3hxupzWuRNeGvvXnoO8o4jTJcnAyhGuZzXJ1GEaD-Z7E6X_a9R-xqJ9TfJWBqz) - Improvements on differentiable memory based on NTMs: now it is the Differentiable Neural Computer (DNC).
- [Google’s Neural Machine Translation System: Bridging the Gap between Human and Machine Translation](https://arxiv.org/pdf/1609.08144.pdf) - In 2016: stacked residual LSTMs with attention mechanisms on encoder/decoder are the best for NMT (Neural Machine Translation).
- [Neural Machine Translation and Sequence-to-sequence Models: A Tutorial](https://arxiv.org/pdf/1703.01619.pdf) - Interesting overview of the subject of NMT, I mostly read part 8 about RNNs with attention as a refresher.
- [Massive Exploration of Neural Machine Translation Architectures](https://arxiv.org/pdf/1703.03906.pdf) - That yields intuition about the boundaries of what works for doing NMT within a framed seq2seq problem formulation.

## Books

- [How to Create a Mind](https://www.amazon.com/How-Create-Mind-Thought-Revealed/dp/B009VSFXZ4) - The audio version is nice to listen to while commuting. This book is motivating about reverse-engineering the mind and thinking on how to code AI.
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html) - This book covers many of the core concepts behind neural networks and deep learning. 
- [Deep Learning - An MIT Press book](http://www.deeplearningbook.org/) - Yet halfway through the book, it contains satisfying math content on how to think about actual deep learning.
- [Some other books I have read](https://books.google.ca/books?hl=en&as_coll=4&num=10&uid=103409002069648430166&source=gbs_slider_cls_metadata_4_mylibrary_title) - Some books listed here are less related to deep learning but are still somehow relevant to this list.
```
Give examples
```


What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc


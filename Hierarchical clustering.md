# Hierarchical Clustering

In data mining and statistics, hierarchical clustering (likewise called various leveled bunch investigation or HCA) is a technique for cluster analysis which tries to fabricate a chain of hierarchy of clusters.
## Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Evolution of the approach with related work](#evolution)
- [Algorithm with mathematical notations and diagrams](#algorithms)
- [Example problem with the solution](#examples)
  - [Librairies and Implementations](#librairies-and-implementations)
- [Applications](#applications)
  - [Gradient Descent Algorithms and optimization](#gradient-descent-algorithms-and-optimization)
- [Discussion](#discussion)
  - [Recurrent Neural Networks](#recurrent-neural-networks)
- [Landmark research papers in the topic](#landmark-research-papers)
- [Resources such as book, code, relevant softwares, libraries, other tutorials,links to video lectures etc](#resources)
- [References](#references)

<a name="trends" />

## Abstract
Hierarchical clustering constructs a cluster hierarchy in the form of a tree like structure or, a tree of clusters,which is known as a dendrogram . Each cluster node contains child clusters; kin clusters partition the points secured by their normal parent. Such an approach permits investigating data on various levels of granularity. Hierarchical clustering strategies are classified into agglomerative (botto-up) and divisive [Jain& Dubes 1988;Kaufman& Rousseeuw 1990]. If we describe agglomerative clustering that starts with with one-point clusters and recursively blends at least two most fitting clusters . If we talk about divisive clustering which  starts with one cluster of all information focuses and recursively split the most fitting cluster.
So classification procedure of Hierarchical clustering is described in this topic.

## Introduction
Hierarchical clustering can be organized into two; agglomerative  and disruptive (top-down) clustering which are illuminated with the names AGNES, and DIANA.Hierarchical clustering manufactures a bunch chain of hierarchy, or as it were, a tree of clusters.Hierarchical clustering yields is organized and more educational than level or level clustering.Hierarchical clustering does not require knowing the per-determined number of clusters. The hierarchical  clustering  is a normally utilized text  clustering  method, which can create hierarchical  nested classes. It clusters  comparable occurrences in a group  by utilizing likenesses of them. This requires the utilization of a similarity (distance) measure which is by and large Euclidean measure when all is said in done, and cosine closeness for documents . Therefore,a similarity (distance) matrix framework of occurrences must be made before running the technique. To understand better first we have to understand about clustering and same is mentioned below:-

### Clustering
Clustering is a division of information or data into gatherings of groups  of  similar  objects or distinct objects. Speaking to the data by less bunches fundamentally loses certain fine subtle elements, however accomplishes disentanglement. It demonstrates information by its groups. Information displaying places grouping in a verified mode or verifiable point of view established in science, measurements, and numerical analysis. if we hink from a machine learning point of view, clusters  compare to concealed patterns, the look for clusters is unsupervised learning, and the related framework speaks to an information idea about the same. From a reasonable point of view clustering assumes an extraordinary part in data mining applications, for example, logical information retrieval , data recovery and data mining, spatial database applications, Web mining, CRM,marketing, medicinal diagnostics, computational science, and numerous others.

Clustering  is the current active subject of dynamic research in a few fields, for example, measurements, pattern   recognition, and also in the field of machine learning. This study concentrates on bunching in data mining.  Data mining adds to grouping the entanglements of large datasets with a lot of traits of various sorts. This forces one of a kind computational prerequisites on relevant clustering algorithms. An assortment of calculations have as of recently developed now that meet these basic important things and were effectively connected to genuine data mining issues. They are subject of the review.

## Evolution

## Algorithms

## Examples
## Applications
- [Biology](https://nlp.stanford.edu/IR-book/pdf/17hier.pdf) - taxonomy of living things: kingdom, phylum, class, order, family, genus and species
- [Information retrieval](ramet.elte.hu/~podani/5-Hierarchical%20clustering.pdf) - document clustering
- [Land use](https://homepages.inf.ed.ac.uk/rbf/BOOKS/JAIN/Clustering_Jain_Dubes.pdf) - Identification of areas of similar land use in an earth observation database.
- [Marketing](https://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf) -Help marketers discover distinct groups in their customer bases, and then use this knowledge to develop targeted    marketing programs
- [City planning](https://nlp.stanford.edu/IR-book/pdf/17hier.pdf) - Identifying groups of houses according to their house type, value, and geographical location.
- [Earth-quake studies](ramet.elte.hu/~podani/5-Hierarchical%20clustering.pdf) - Observed earth quake epicenters should be clustered along continent faults
- [Climate](https://homepages.inf.ed.ac.uk/rbf/BOOKS/JAIN/Clustering_Jain_Dubes.pdf) - understanding earth climate, find patterns of atmospheric and ocean.
- [Economic Science](https://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf) -market resarch
## Discussion
## Landmark research papers
- [Hierarchical clustering schemes](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) - Johnson, Stephen C. "Hierarchical clustering schemes." Psychometrika 32, no. 3 (1967): 241-254.
- [Chameleon: Hierarchical clustering using dynamic modeling](http://ieeexplore.ieee.org/abstract/document/781637/). Chameleon: Hierarchical clustering using dynamic modeling. Computer, 32(8), 68-75.
- [ A comparison of document clustering techniques](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) Steinbach, Michael, George Karypis, and Vipin Kumar. "A comparison of document clustering techniques." KDD workshop on text mining. Vol. 400. No. 1. 2000.
- [ A universal density profile from hierarchical clustering](iopscience.iop.org/article/10.1086/304888/meta)Navarro, Julio F., Carlos S. Frenk, and Simon DM White. "A universal density profile from hierarchical clustering." The Astrophysical Journal 490.2 (1997): 493.
- [ A survey of recent advances in hierarchical clustering algorithms](https://academic.oup.com/comjnl/article/26/4/354/377434)Murtagh, Fionn. "A survey of recent advances in hierarchical clustering algorithms." The Computer Journal 26.4 (1983): 354-359.

## Resources
### Books

- [Hierarchical clustering - Stanford NLP Group](https://nlp.stanford.edu/IR-book/pdf/17hier.pdf) - This chapter first introduces agglomerative hierarchical clustering (Section 17.1) ... erences to soft hierarchical clustering.
- [Hierarchical clustering](ramet.elte.hu/~podani/5-Hierarchical%20clustering.pdf) - In this book, we are not concerned with such arrangements any lon- ger, and emphasis .... The process of hierarchical clustering can follow two basic strategies
- [Algorithms For Clustering Data](https://homepages.inf.ed.ac.uk/rbf/BOOKS/JAIN/Clustering_Jain_Dubes.pdf) - structure either as a grouping of individuals or as a hierarchy of groups. The ... The book emphasizes informal algorithms for clustering data, and interpreting .
- [Cluster Analysis: Basic Concepts and Algorithms]https://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf) -agglomerative hierarchical clustering, and DBSCAN. The final section ... In addition, the bibliographic notes provide references to relevant books and papers that.
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

- [Hierarchical clustering schemes](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) - Johnson, Stephen C. "Hierarchical clustering schemes." Psychometrika 32, no. 3 (1967): 241-254.
- [Chameleon: Hierarchical clustering using dynamic modeling](http://ieeexplore.ieee.org/abstract/document/781637/). Chameleon: Hierarchical clustering using dynamic modeling. Computer, 32(8), 68-75.
- [ A comparison of document clustering techniques](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) Steinbach, Michael, George Karypis, and Vipin Kumar. "A comparison of document clustering techniques." KDD workshop on text mining. Vol. 400. No. 1. 2000.
- [ A universal density profile from hierarchical clustering](iopscience.iop.org/article/10.1086/304888/meta)Navarro, Julio F., Carlos S. Frenk, and Simon DM White. "A universal density profile from hierarchical clustering." The Astrophysical Journal 490.2 (1997): 493.
- [ A survey of recent advances in hierarchical clustering algorithms](https://academic.oup.com/comjnl/article/26/4/354/377434)Murtagh, Fionn. "A survey of recent advances in hierarchical clustering algorithms." The Computer Journal 26.4 (1983): 354-359.
- Hierarchical Clustering by Songül Albayrak (Yıldız Technical University).
- Data Mining: Concepts and Techniques by Jiawei Han, Micheline Kamber, and Jian Pei
- Clustering by Kamal Nigam (http://www-csli.stanford.edu/~hinrich/information-retrieval-book.html)
- Cluster Analysis by MktRes-MARK
- Clustering by Jing Gao  and SUNY Buffalo 
- Hierarchical Clustering by Ke Chen


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


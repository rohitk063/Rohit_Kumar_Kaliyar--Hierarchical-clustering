# Hierarchical Clustering

In data mining and statistics, hierarchical clustering (likewise called various leveled bunch investigation or HCA) is a technique for cluster analysis which tries to fabricate a chain of hierarchy of clusters.
## Contents
- [Abstract](#abstract)
- [Introduction](#introduction)
  - [Clustering](#clustering)
- [Evolution of the approach with related work](#evolution)
- [Algorithm with mathematical notations and diagrams](#algorithms)
- [Example problem with the solution](#examples)
- [Applications](#applications)
- [Discussion](#discussion)
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
 The recent discoveries of an excess of faint blue galactic counts (Lilly et al. 1995; Ellis et al. 1996) and a substantial population of star-forming galaxies at redshift z &sime; 3–3.5 (Steidel et al. 1996) may be taken as evidence of hierarchical structure formation (Kauffmann & White 1993; Lacey & Cole 1993; Navarro, Frenk, & White 1996). However, the predicted abundance of galaxies at higher redshifts depends on, at the very least, models of stellar population synthesis and the initial mass function (IMF). Besides these abundances, a more direct and independent detection of hierarchical evolution is necessary to form a convincing argument for this scenario as well as to discriminate between different models of structure formation.
 
   Scenarios of hierarchical matter clustering are defined in terms of rules that determine how dark halos evolve from scale to scale. Measuring correlations of structures at different scales is a direct and sensitive way to test the hypothesis of hierarchical clustering. We propose to detect this hierarchical structure by studying correlations between coefficients of a wavelet decomposition of the density field ρ(x). We suggest relevant measures to quantify such scale-scale correlations and to discriminate between different scenarios. Scale-scale correlation measures have been shown to effectively reveal hierarchical characteristics of energy transfer in turbulence and multiparticle physics (Yamada & Ohkitani 1991; Greiner, Lipa, & Carruthers 1995).

## Algorithms
Hierarchical clustering algorithm is of two types:

 i) Agglomerative Hierarchical clustering algorithm or AGNES (agglomerative nesting) and

 ii) Divisive Hierarchical clustering algorithm or DIANA (divisive analysis).

Both this algorithm are exactly reverse of each other. So we will be covering Agglomerative Hierarchical clustering algorithm in detail.
Agglomerative Hierarchical clustering -This algorithm  works by  grouping  the data one by one on the basis of the  nearest distance measure of all the pairwise distance between the data point. Again distance between the data point is recalculated but which distance to consider when the groups has been formed? For this there are many available methods. Some of them are:

 1) single-nearest distance or single linkage.

 2) complete-farthest distance or complete linkage.

 3) average-average distance or average linkage.

 4) centroid distance.

 5) ward's method - sum of squared euclidean distance is minimized.

This way we go on grouping the data until one cluster is formed. Now on the basis of dendogram graph we can calculate how many number of clusters should be actually present.
Algorithmic steps for Agglomerative Hierarchical clustering

Let  X = {x1, x2, x3, ..., xn} be the set of data points.

1) Begin with the disjoint clustering having level L(0) = 0 and sequence number m = 0.

2) Find the least distance pair of clusters in the current clustering, say pair (r), (s), according to d[(r),(s)] = min d[(i),(j)]   where the minimum is over all pairs of clusters in the current clustering.

3) Increment the sequence number: m = m +1.Merge clusters (r) and (s) into a single cluster to form the next clustering   m. Set the level of this clustering to L(m) = d[(r),(s)].
4) Update the distance matrix, D, by deleting the rows and columns corresponding to clusters (r) and (s) and adding a row and column corresponding to the newly formed cluster. The distance between the new cluster, denoted (r,s) and old cluster(k) is defined in this way: d[(k), (r,s)] = min (d[(k),(r)], d[(k),(s)]).
5) If all the data points are in one cluster then stop, else repeat from step 2).

Divisive Hierarchical clustering - It is just the reverse of Agglomerative Hierarchical approach.
### Various linkage algorithms
  1. In single-linkage clustering (also called the connectedness or minimum method), we consider the distance between one cluster and another cluster to be equal to the shortest distance from any member of one cluster to any member of the other cluster. If the data consist of similarities, we consider the similarity between one cluster and another cluster to be equal to the greatest similarity from any member of one cluster to any member of the other cluster.
 
  2. In complete-linkage clustering (also called the diameter or maximum method), we consider the distance between one cluster and another cluster to be equal to the greatest distance from any member of one cluster to any member of the other cluster.
 
  3. In average-linkage clustering, we consider the distance between one cluster and another cluster to be equal to the average distance from any member of one cluster to any member of the other cluster.
 
A variation on average-link clustering is the UCLUS method of R. D'Andrade (1978) which uses the median distance, which is much more outlier-proof than the average distance.
#### Single-Linkage Clustering: Algorithm
Let’s now take a deeper look at how Johnson’s algorithm works in the case of single-linkage clustering.
The algorithm is an agglomerative scheme that erases rows and columns in the proximity matrix as old clusters are merged into new ones.

The N*N proximity matrix is D = [d(i,j)]. The clusterings are assigned sequence numbers 0,1,......, (n-1) and L(k) is the level of the kth clustering. A cluster with sequence number m is denoted (m) and the proximity between clusters (r) and (s) is denoted d [(r),(s)]. 
The algorithm is composed of the following steps:

    Begin with the disjoint clustering having level L(0) = 0 and sequence number m = 0.
    Find the least dissimilar pair of clusters in the current clustering, say pair (r), (s), according to

    d[(r),(s)] = min d[(i),(j)]

    where the minimum is over all pairs of clusters in the current clustering.
    Increment the sequence number : m = m +1. Merge clusters (r) and (s) into a single cluster to form the next clustering m. Set the level of this clustering to

    L(m) = d[(r),(s)]
    Update the proximity matrix, D, by deleting the rows and columns corresponding to clusters (r) and (s) and adding a row and column corresponding to the newly formed cluster. The proximity between the new cluster, denoted (r,s) and old cluster (k) is defined in this way:

    d[(k), (r,s)] = min d[(k),(r)], d[(k),(s)]
    If all objects are in one cluster, stop. Else, go to step 2.
#### Complete Linkage
In complete linkage hierarchical clustering, the distance between two clusters is defined as the longest distance between two points in each cluster. For example, the distance between clusters “r” and “s” to the left is equal to the length of the arrow between their two furthest points.
#### Average Linkage
In average linkage hierarchical clustering, the distance between two clusters is defined as the average distance between each point in one cluster to every point in the other cluster. For example, the distance between clusters “r” and “s” to the left is equal to the average length each arrow between connecting the points of one cluster to the other.
#### Wards method
Ward's minimum variance criterion minimizes the total within-cluster variance. To implement this method, at each step find the pair of clusters that leads to minimum increase in total within-cluster variance after merging. This increase is a weighted squared distance between cluster centers. At the initial step, all clusters are singletons (clusters containing a single point). To apply a recursive algorithm under this objective function, the initial distance between individual objects must be (proportional to) squared Euclidean distance.

The initial cluster distances in Ward's minimum variance method are therefore defined to be the squared Euclidean distance between points:

    d i j = d ( { X i } , { X j } ) = ∥ X i − X j ∥ 2 



## Examples
- [GitHub - gyaikhom/agglomerative-hierarchical-clustering: Implements](https://github.com/gyaikhom/agglomerative-hierarchical-clustering) - In this example, we are running the hierarchical agglomerative clustering on the items in the input file example.txt . We are asking the program to generate 3 disjointed clusters using the single-linkage distance metric
- [GitHub - lbehnke/hierarchical-clustering-java: Implementation](https://github.com/lbehnke/hierarchical-clustering-java) - Implementation of an agglomerative hierarchical clustering algorithm in Java. Different linkage approaches are supported.
- [SciPy Hierarchical Clustering and Dendrogram Tutorial](https://joernhees.de/blog/2015/.../scipy-hierarchical-clustering-and-dendrogram-tutori...) - This is a tutorial on how to use scipy's hierarchical clustering. ... X samples (n x m array), aka data points or "singleton clusters"; n number of ...... This entry was posted in Coding and tagged clustering, code, dendrogram...
- [Hierarchical Clustering Python Implementation - GitHub](https://github.com/ZwEin27/Hierarchical-Clustering) -Hierarchical Clustering Python Implementation. ... For example, to produce two clusters, the algorithm can simply return the last two clusters that were merged ...
- [Data Science: Performing Hierarchical Clustering with Python](www.dummies.com/programming/.../data-science-performing-hierarchical-clustering-) - Scikit-learn implementation of agglomerative clustering does not offer the possibility of ... fine with only a few cases, whereas you can expect to work on many examples.
- [Python Math: Calculate clusters using Hierarchical Clustering method](https://www.w3resource.com/python-exercises/math/python-math-exercise-75.php) - a Python program to calculate clusters using Hierarchical Clustering method

## Applications
- [Biology](https://en.wikipedia.org/wiki/Biology) - taxonomy of living things: kingdom, phylum, class, order, family, genus and species
- [Information retrieval](https://en.wikipedia.org/wiki/Information_retrieval) - document clustering
- [Land use](https://en.wikipedia.org/wiki/Land_use) - Identification of areas of similar land use in an earth observation database.
- [Marketing](https://en.wikipedia.org/wiki/Marketing) -Help marketers discover distinct groups in their customer bases, and then use this knowledge to develop targeted    marketing programs
- [City planning](https://en.wikipedia.org/wiki/Urban_planning) - Identifying groups of houses according to their house type, value, and geographical location.
- [Earth-quake studies](https://www.eqc.govt.nz/research-categories/earthquake-studies) - Observed earth quake epicenters should be clustered along continent faults
- [Climate](https://en.wikipedia.org/wiki/Climate) - understanding earth climate, find patterns of atmospheric and ocean.
- [Economic Science](https://en.wikipedia.org/wiki/Economics) -market resarch
## Discussion
-•Useful if the underlying application has a taxonomy.

-•Agglomerative hierarchical clustering algorithms are expensive in terms of their computational and storage requirements.

-•Merges are final and cannot be undone at a later time, preventing global optimization and causing trouble for noisy, high

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
- [Cluster Analysis: Basic Concepts and Algorithms](https://www-users.cs.umn.edu/~kumar/dmbook/ch8.pdf) -agglomerative hierarchical clustering, and DBSCAN. The final section ... In addition, the bibliographic notes provide references to relevant books and papers that.
### Code

- [Hierarchical Clustering - MATLAB & Simulink](https://in.mathworks.com/help/stats/hierarchical-clustering-12.html?s_tid=gn_loc_drop) - Hierarchical clustering groups data into a multilevel cluster tree or dendrogram. If your data is hierarchical, this technique can help you choose the level of clustering that is most appropriate for your application.
- [Agglomerative hierarchical cluster tree](http://in.mathworks.com/help/stats/linkage.html) - This MATLAB function returns a matrix Z that encodes a tree of hierarchical clusters of the rows of the real matrix X...
- [SciPy Hierarchical Clustering and Dendrogram Tutorial](https://joernhees.de/blog/2015/.../scipy-hierarchical-clustering-and-dendrogram-tutori...) - This is a tutorial on how to use scipy's hierarchical clustering. ... X samples (n x m array), aka data points or "singleton clusters"; n number of ...... This entry was posted in Coding and tagged clustering, code, dendrogram...
- [Hierarchical Clustering Python Implementation - GitHub](https://github.com/ZwEin27/Hierarchical-Clustering) -Hierarchical Clustering Python Implementation. ... For example, to produce two clusters, the algorithm can simply return the last two clusters that were merged ...
### Softwares

[File:Iris dendrogram.png|thumb|Hierarchical clustering [dendrogram]] of the [Iris flower data set|Iris dataset] (using [R (programming language)|R]). [https://cran.r-project.org/web/packages/dendextend/vignettes/Cluster_Analysis.html Source]

[File:Orange-data-mining-hierarchical-clustering.png|thumb|Hierarchical clustering and interactive dendrogram visualization in [Orange (software)|Orange data mining suite]

* [http://bonsai.hgc.jp/~mdehoon/software/cluster/ Cluster 3.0] provides a [Graphical User Interface] to access to different clustering routines and is available for Windows, Mac OS X, Linux, Unix.
* [ELKI] includes multiple hierarchical clustering algorithms, various linkage strategies and also includes the efficient SLINK,<ref name="SLINK" /> CLINK<ref name="CLINK" /> and Anderberg algorithms, flexible cluster extraction from dendrograms and various other [[cluster analysis] algorithms.
* [GNU Octave|Octave], the [GNU] analog to [MATLAB] implements hierarchical clustering in [http://octave.sourceforge.net/statistics/function/linkage.html linkage function]
* [Orange (software)|Orange], a data mining software suite, includes [https://docs.orange.biolab.si/3/visual-programming/widgets/unsupervised/hierarchicalclustering.html hierarchical clustering] with interactive dendrogram visualisation.
* [R (programming language)|R] has several functions for hierarchical clustering: see [https://cran.r-project.org/web/views/Cluster.html CRAN Task View: Cluster Analysis & Finite Mixture Models] for more information.
* [SCaViS] computing environment in Java that implements this algorithm.
* [scikit-learn] implements a hierarchical clustering in Python.
* [Weka (machine learning)|Weka] includes hierarchical cluster analysis.
## References
- [Hierarchical clustering schemes](https://link.springer.com/article/10.1007%2FBF02289588?LI=true) - Abstract Techniques for partitioning objects into optimally homogeneous groups on the basis of empirical measures.
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




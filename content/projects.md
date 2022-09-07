# Projects

---

## NewNest

![NewNest_2](/nn_1.png)
![NewNest_1](/nn_2.png)

### Description 

NewNest is a current full stack web project employing a Django backend with a PostgreSQL dababase and React JS
frontend. The website aims to be a platform to review long term rental houses, fixing the disparity in knowledge
between landlords and renters. Users can add reviews of rental houses they have lived in and freely view
previous reviews of other properties that they are interested in renting. 

### Tools

1) React JS
2) Django (Python)
3) PostgreSQL 

---

## H01 Human Connectomics Research 

![h01](/h01.png)

### Description 

Project aimed to 
find cortical layerings for brain cells using an unbiased algorithmic approach. I Used RANSAC regression, 
SVM models and other machine learning techniques to solve this problem. The boundaries found can be seen in the diagram above. 
The results were included in an academic paper that I coauthored [(link)](https://www.biorxiv.org/content/10.1101/2021.05.29.446289v2) 
. The paper currently has over 80 citations. 

In a related project, I used a combination of Python and C++ to analyse motifs and multi-node structures present
in brain tissue using the Kavosh algorithm.

### Tools 

1) Python - (lots of Sklearn)
2) C++

[Github (Cortical Layerings)](https://github.com/LukeBailey181/h01)

[Github (Motifs)](https://github.com/LukeBailey181/motifs)

---

## Identity Insight 

{{< youtube k-ZsSXN_0Mo >}}

### Description

A full-stack iOS app development with a Swift front end and Node JS backend. Backend AWS EC2 instance ran Python face recognition
software that would identify faces in a crowd. A proof of concept design for use by sight impaired people. I was a
partner in two person team.

### Tools 

1) Swift
2) Node JS
3) Python 

[Github](https://github.com/LukeBailey181/IdentityInsight)

---

## Algorithm Projects

I have worked on three projects that concern low level algorithms work during my time at university. 


[1) Finding Minimum Spanning Tree](https://github.com/LukeBailey181/minimum-spanning-trees)

The problem of determining minimum spanning trees within a graph is a long studied issue. Many algorithms have arisen 
to address the minimum spanning tree problem in a more optimal fashion, all 
with respective benefits and trade-offs. In this project, a friend and I examined one such algorithm's behaviour on 
randomized graph inputs of increasing scale. To do so, we implemented Prim's 
Algorithm and randomly generated graphs in various dimensions of euclidean space. We conducted
the coding project entirely in C and wrote all high-level data structures from scratch.
We found the average total weight of the MST for the different graph sizes and dimensions. 


[2) Strassen Cutoff](https://github.com/LukeBailey181/strassen-cutoff)

Improving the running time of matrix multiplication is a popular and widely studied topic in theoretical computer science. 
The first and most familiar algorithm to do so is Strassen's algorithm, which defines a lengthy set of operations that ultimately 
reduce the recursion of a divide and conquer multiplication implementation from eight calls down to seven. Although this has a 
significant impact on the asymptotic runtime bound , the algorithm is often dismissed as impractical for any reasonable matrix dimensions 
due to its actual slower runtime for smaller matrix sizes. In this project we explored what the optimal cut-off value was to change
from Stassen's algorithm to naive matrix multiplication in the recursive divide and conquer stack. The resulting algorithm 
was able to outperform naive and straight Strassen's matrix multiplication.

[3) Number Partition](https://github.com/LukeBailey181/number-partition)

The [number partition problem](https://en.wikipedia.org/wiki/Partition_problem) is an NP-complete problem that involves partitioning 
a set of numbers into two subsets who's sums are equal. In this project we explored heuristic and 
random approaches to find approximate solutions to the problem in polynomial as opposed to exponential time. We 
tested the empirical performance and speed of these algorithms with an implementation of each in Python.
Techniques included hill climbing, simulated annealing, and a dynamic programming solution to the problem.

### Tools

1) C
2) Python 

  
  

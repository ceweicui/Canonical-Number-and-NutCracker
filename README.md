# Canonical-Number-and-NutCracker


## This repository is for the paper "Canonical Number and NutCracker: Heuristic Algorithms for the Graph Isomorphism Problem using Free Energy"(https://arxiv.org/abs/1605.07220)

At first, we only release the data sets and results for the experiment in the above paper.

Later, we may release the source code of our algorithms.

DataSet:
The first dataset, which is under the folder "puredata", includes
all 10 vertices connected graphs.
It is created by
Brendan McKay. See (http://users.cecs.anu.edu.au/~bdm/data/graphs.html)

The second dataset, which is under the folder "srg", includes all strongly
regular graph with the number of vertices <= 64. The original dataset is maintained by E. Spence. See (http://www.maths.gla.ac.uk/~es/srgraphs.php).


##### Jar files:
In the jars folder, you can find two jar files GIp8.jar and GIp9.jar.
They are same programs with different precision because in our experiment,
some datasets need precision 8 digits while others need 9 digits.

How to run it?
```shell
java -jar GIp8.jar inputFileFolder filename outputFileFolder initialIndex
```

For example,
```shell
java -jar GIp8.jar srg 16-6-2-2.srg.csv output 1
```

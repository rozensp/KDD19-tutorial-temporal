# KDD 2019 tutorial

## Instructors

- [Aristides Gionis](https://users.ics.aalto.fi/gionis/), Aalto University
- Polina Rozenshtein, Nordea Data Science Lab

## Motivation

Networks (or graphs) are used to represent and analyze large datasets of objects and their
relations. Typical examples of graph applications come from social networks, traffic networks,
electric power grids, road systems, the Internet, chemical and biological systems, and more.
Naturally, real-world networks have a temporal component: for instance, interactions between
objects have a timestamp and a duration. In this tutorial we present models and algorithms
for mining temporal networks, i.e., network data with temporal information. We overview
different models used to represent temporal networks. We highlight the main differences
between static and temporal networks, and discuss the challenges arising from introducing the
temporal dimension in the network representation. We present recent papers addressing
the most well-studied problems in the setting of temporal networks, including computation
of centrality measures, motif detection and counting, community detection and monitoring,
event and anomaly detection, analysis of epidemic processes and influence spreading, network
summarization, and structure prediction. Finally, we discuss some of the current challenges
and open problems in the area, and we highlight directions for future work.

## Tutorial slides

## Links to relevant papers:

<!---
We recommend making the title more "exciting" in order to attract a greater audience. 

Please consider making the tutorial more inclusive (including dynamic and streaming graphs, and work on higher-order motifs by Austin Benson and others). Also, including some more ground-breaking applications will likely attract more interest. You may also want to discuss temporal embeddings.
-->

### Key surveys, definitions, and applications
- A. Casteigts, P. Flocchini, W. Quattrociocchi, and N. Santoro. [Time-varying graphs and dynamic networks](https://hal.archives-ouvertes.fr/hal-00847001/document). International Journal of Parallel, Emergent and Distributed Systems, 2012.
- P. Holme. [Modern temporal network theory: a colloquium](https://arxiv.org/pdf/1508.01303.pdf). The European Physical Journal, 2015.
- P. Holme and J. Saramäki. [Temporal networks](https://arxiv.org/pdf/1108.1780.pdf). Physics reports, 2012.
- M. Latapy, T. Viard, and C. Magnien. [Stream graphs and link streams for the modeling of interactions over
time. Social Network Analysis and Mining](https://arxiv.org/pdf/1710.04073.pdf), 2018.
- O. Michail. [An introduction to temporal graphs: An algorithmic perspective](https://arxiv.org/pdf/1503.00278.pdf). Internet Mathematics, 2016.

### Models of temporal networks
- C. Aggarwal and K. Subbian. [Evolutionary network analysis: A survey](http://charuaggarwal.net/CSUR-2013-0157.pdf). ACM Computing Surveys (CSUR), 2014.
- C. C. Aggarwal and H. Wang. [Graph data management and mining: A survey of algorithms and applications](https://www.researchgate.net/profile/Charu_Aggarwal/publication/226186048_Graph_Data_Management_and_Mining_A_Survey_of_Algorithms_and_Applications/links/0deec52415b17b7029000000/Graph-Data-Management-and-Mining-A-Survey-of-Algorithms-and-Applications.pdf).
In Managing and mining graph data, 2010.
- R. Kumar, J. Novak, and A. Tomkins. [Structure and evolution of online social networks](http://staff.icar.cnr.it/manco/Teaching/sn/seminari/KNT06.pdf). In Link mining:
models, algorithms, and applications, 2010.
- S. A. Hill and D. Braha. [Dynamic model of time-dependent complex networks](https://arxiv.org/pdf/0901.4407.pdf). Physical Review, 2010.
- H.-H. Jo, R. K. Pan, and K. Kaski. [Emergence of bursts and communities in evolving weighted networks](https://s3.amazonaws.com/academia.edu.documents/43180878/Emergence_of_Bursts_and_Communities_in_E20160228-25035-h5xlh2.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1556391483&Signature=KY4ls%2FyKUa4gBIz1MkA9T%2BL%2B2e0%3D&response-content-disposition=inline%3B%20filename%3DEmergence_of_Bursts_and_Communities_in_E.pdf). PloS
one, 2011.
- A.-L. Barabási et al. [Network science](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.722.9529&rep=rep1&type=pdf). Cambridge university press, 2016.
- P. Holme. [Epidemiologically optimal static networks from temporal network data](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.813.7544&rep=rep1&type=pdf). PLoS computational biology, 2013.

### Network measures: characterization and computation
- H.-P. Hsieh and C.-T. Li. [Mining temporal subgraph patterns in heterogeneous information networks](https://ieeexplore.ieee.org/document/5591222). In 2010
IEEE Second International Conference on Social Computing, 2010.
- B. Wackersreuther, P. Wackersreuther, A. Oswald, C. Böhm, and K. M. Borgwardt. [Frequent subgraph
discovery in dynamic networks](http://www.dbs.ifi.lmu.de/Publikationen/Boehm/KDD-MLG_10.pdf). In Proceedings of the Eighth Workshop on Mining and Learning with Graphs, 2010.
- M. Berlingerio, F. Bonchi, B. Bringmann, and A. Gionis. [Mining graph evolution rules](https://core.ac.uk/download/pdf/34450269.pdf). In joint European
conference on machine learning and knowledge discovery in databases, 2009.
- A. Impedovo, C. Loglisci, and M. Ceci. [Temporal pattern mining from evolving networks](https://pdfs.semanticscholar.org/cedd/f3e4ad8787739d118976c38c3c155ab37d96.pdf). arXiv preprint, 2017.

### Algorithmic approaches
- R. Kumar, T. Calders, A. Gionis, and N. Tatti. [Maintaining sliding-window neighborhood profiles in
interaction networks](). In Joint European Conference on Machine Learning and Knowledge Discovery in
Databases, 2015.
- A. McGregor. [Graph stream algorithms: a survey](http://rohit13k.github.io/doc/swn.pdf). ACM SIGMOD Record, 2014.
- O. Michail. [An introduction to temporal graphs: An algorithmic perspective](http://students.ceid.upatras.gr/~michailo/Documents/Papers/Journals/im16.pdf). Internet Mathematics, 2016.

### Data Mining problems
- G. Rossetti and R. Cazabet. Community discovery in dynamic networks: a survey. ACM Computing Surveys
(CSUR), 2018.
- P. Rozenshtein, N. Tatti, and A. Gionis. Finding dynamic dense subgraphs. ACM Transactions on Knowledge
Discovery from Data (TKDD), 2017.
- L. Akoglu, H. Tong, and D. Koutra. Graph based anomaly detection and description: a survey. Data mining
and knowledge discovery, 2015.
- M. Cordeiro and J. Gama. Online social networks event detection: a survey. In Solving Large Scale Learning
Tasks. Challenges and Algorithms, 2016.
- A. Goswami and A. Kumar. A survey of event detection techniques in online social networks. Social Network
Analysis and Mining, 2016.
- A. Nurwidyantoro and E. Winarko. Event detection in social media: A survey. In International Conference on
ICT for Smart Society, 2013.
- P. Rozenshtein, A. Anagnostopoulos, A. Gionis, and N. Tatti. Event detection in activity networks. In
Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining, 2014.
- H. Xiao, P. Rozenshtein, and A. Gionis. Discovering topically-and temporally-coherent events in interaction
networks. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases, 2016.
- S. Lee, L. E. Rocha, F. Liljeros, and P. Holme. Exploiting temporal network structures of human interaction to
effectively immunize populations. PloS one, 2012.
- A. Nurwidyantoro and E. Winarko. Event detection in social media: A survey. In International Conference on
ICT for Smart Society, 2013.
- P. Rozenshtein, A. Gionis, B. A. Prakash, and J. Vreeken. Reconstructing an epidemic over time. In
Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2016.
- H. Xiao, P. Rozenshtein, N. Tatti, and A. Gionis. Reconstructing a cascade from temporal observations. In
Proceedings of the 2018 SIAM International Conference on Data Mining, 2018.
- Y. Liu, T. Safavi, A. Dighe, and D. Koutra. Graph summarization methods and applications: A survey. ACM
Computing Surveys (CSUR), 2018.
- P. Rozenshtein, N. Tatti, and A. Gionis. The network-untangling problem: From interactions to activity
timelines. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases, 2017.
- P. Rozenshtein, F. Bonchi, A. Gionis, M. Sozio, and N. Tatti. Finding events in temporal networks:
Segmentation meets densest-subgraph discovery. In 2018 IEEE International Conference on Data Mining
(ICDM), 2018.
- Y. Dhote, N. Mishra, and S. Sharma. Survey and analysis of temporal link prediction in online social networks.
In 2013 International Conference on Advances in Computing, Communications and Informatics (ICACCI), 2013.
- L. Zhu, D. Guo, J. Yin, G. Ver Steeg, and A. Galstyan. Scalable temporal latent space inference for link
prediction in dynamic social networks. IEEE Transactions on Knowledge and Data Engineering, 2016.


<!---
You can use the [editor on GitHub](https://github.com/rozensp/KDD19-tutorial-temporal/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rozensp/KDD19-tutorial-temporal/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

-->

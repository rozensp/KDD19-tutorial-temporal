# KDD 2019 tutorial

## Instructors

- [Aristides Gionis](https://users.ics.aalto.fi/gionis/), Aalto University
- Polina Rozenshtein, Nordea Data Science Lab

## Motivation

Networks (or graphs) are used to represent and analyze large datasets of objects and their
relations. Typical examples of graph applications come from social networks, traffic networks,
electric power grids, road systems, the Internet, chemical and biological systems, and more.
Naturally, real-world networks have a temporal component: for instance, interactions between
objects have a timestamp and a duration. In this tutorial we will present models and algorithms
for mining temporal networks, i.e., network data with temporal information. We will overview
different models used to represent temporal networks. We will highlight the main differences
between static and temporal networks, and discuss the challenges arising from introducing the
temporal dimension in the network representation. We will present recent papers addressing
the most well-studied problems in the setting of temporal networks, including computation
of centrality measures, motif detection and counting, community detection and monitoring,
event and anomaly detection, analysis of epidemic processes and influence spreading, network
summarization, and structure prediction. Finally, we will discuss some of the current challenges
and open problems in the area, and we will highlight directions for future work.

## Tutorial slides

## Links to relevant papers:

<!---
We recommend making the title more "exciting" in order to attract a greater audience. 

Please consider making the tutorial more inclusive (including dynamic and streaming graphs, and work on higher-order motifs by Austin Benson and others). Also, including some more ground-breaking applications will likely attract more interest. You may also want to discuss temporal embeddings.
-->

### Key surveys, definitions, and applications
- A. Casteigts, P. Flocchini, W. Quattrociocchi, and N. Santoro. Time-varying graphs and dynamic networks. International Journal of Parallel, Emergent and Distributed Systems, 27(5):387–408, 2012.
- P. Holme. Modern temporal network theory: a colloquium. The European Physical Journal B, 88(9):234, 2015.
- P. Holme and J. Saramäki. Temporal networks. Physics reports, 519(3):97–125, 2012.
- M. Latapy, T. Viard, and C. Magnien. Stream graphs and link streams for the modeling of interactions over
time. Social Network Analysis and Mining, 8(1):61, 2018.
- O. Michail. An introduction to temporal graphs: An algorithmic perspective. Internet Mathematics, 12(4):
239–280, 2016.
### Models of temporal networks
- C. Aggarwal and K. Subbian. Evolutionary network analysis: A survey. ACM Computing Surveys (CSUR), 47
(1):10, 2014.
- C. C. Aggarwal and H. Wang. Graph data management and mining: A survey of algorithms and applications.
In Managing and mining graph data, pages 13–68. Springer, 2010.
- R. Kumar, J. Novak, and A. Tomkins. Structure and evolution of online social networks. In Link mining:
models, algorithms, and applications, pages 337–357. Springer, 2010.
- P. Holme and J. Saramäki. Temporal networks. Physics reports, 519(3):97–125, 2012.
- O. Michail. An introduction to temporal graphs: An algorithmic perspective. Internet Mathematics, 12(4):
239–280, 2016.
- S. A. Hill and D. Braha. Dynamic model of time-dependent complex networks. Physical Review E, 82(4):
046105, 2010.
- H.-H. Jo, R. K. Pan, and K. Kaski. Emergence of bursts and communities in evolving weighted networks. PloS
one, 6(8):e22687, 2011.
- A.-L. Barabási et al. Network science. Cambridge university press, 2016.
- P. Holme. Epidemiologically optimal static networks from temporal network data. PLoS computational biology,
9(7):e1003142, 2013.

### Network measures: characterization and computation
- P. Holme and J. Saramäki. Temporal networks. Physics reports, 519(3):97–125, 2012.
- M. Latapy, T. Viard, and C. Magnien. Stream graphs and link streams for the modeling of interactions over
time. Social Network Analysis and Mining, 8(1):61, 2018.
- H.-P. Hsieh and C.-T. Li. Mining temporal subgraph patterns in heterogeneous information networks. In 2010
IEEE Second International Conference on Social Computing, pages 282–287. IEEE, 2010.
- B. Wackersreuther, P. Wackersreuther, A. Oswald, C. Böhm, and K. M. Borgwardt. Frequent subgraph
discovery in dynamic networks. In Proceedings of the Eighth Workshop on Mining and Learning with Graphs,
pages 155–162. ACM, 2010.
- M. Berlingerio, F. Bonchi, B. Bringmann, and A. Gionis. Mining graph evolution rules. In joint European
conference on machine learning and knowledge discovery in databases, pages 115–130. Springer, 2009.
- A. Impedovo, C. Loglisci, and M. Ceci. Temporal pattern mining from evolving networks. arXiv preprint
arXiv:1709.06772, 2017.

### Algorithmic approaches
- R. Kumar, T. Calders, A. Gionis, and N. Tatti. Maintaining sliding-window neighborhood profiles in
interaction networks. In Joint European Conference on Machine Learning and Knowledge Discovery in
Databases, pages 719–735, 2015.
- A. McGregor. Graph stream algorithms: a survey. ACM SIGMOD Record, 43(1):9–20, 2014.
- O. Michail. An introduction to temporal graphs: An algorithmic perspective. Internet Mathematics, 12(4):
239–280, 2016.

### Data Mining problems
- G. Rossetti and R. Cazabet. Community discovery in dynamic networks: a survey. ACM Computing Surveys
(CSUR), 51(2):35, 2018.
- P. Rozenshtein, N. Tatti, and A. Gionis. Finding dynamic dense subgraphs. ACM Transactions on Knowledge
Discovery from Data (TKDD), 11(3):27, 2017.
- L. Akoglu, H. Tong, and D. Koutra. Graph based anomaly detection and description: a survey. Data mining
and knowledge discovery, 29(3):626–688, 2015.
- M. Cordeiro and J. Gama. Online social networks event detection: a survey. In Solving Large Scale Learning
Tasks. Challenges and Algorithms, pages 1–41. Springer, 2016.
- A. Goswami and A. Kumar. A survey of event detection techniques in online social networks. Social Network
Analysis and Mining, 6(1):107, 2016.
- A. Nurwidyantoro and E. Winarko. Event detection in social media: A survey. In International Conference on
ICT for Smart Society, pages 1–5. IEEE, 2013.
- P. Rozenshtein, A. Anagnostopoulos, A. Gionis, and N. Tatti. Event detection in activity networks. In
Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining,
pages 1176–1185. ACM, 2014.
- H. Xiao, P. Rozenshtein, and A. Gionis. Discovering topically-and temporally-coherent events in interaction
networks. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases, pages
690–705. Springer, 2016.
- S. Lee, L. E. Rocha, F. Liljeros, and P. Holme. Exploiting temporal network structures of human interaction to
effectively immunize populations. PloS one, 7(5):e36439, 2012.
- A. Nurwidyantoro and E. Winarko. Event detection in social media: A survey. In International Conference on
ICT for Smart Society, pages 1–5. IEEE, 2013.
- P. Rozenshtein, A. Gionis, B. A. Prakash, and J. Vreeken. Reconstructing an epidemic over time. In
Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining,
pages 1835–1844. ACM, 2016.
- H. Xiao, P. Rozenshtein, N. Tatti, and A. Gionis. Reconstructing a cascade from temporal observations. In
Proceedings of the 2018 SIAM International Conference on Data Mining, pages 666–674. SIAM, 2018.
- Y. Liu, T. Safavi, A. Dighe, and D. Koutra. Graph summarization methods and applications: A survey. ACM
Computing Surveys (CSUR), 51(3):62, 2018.
- P. Rozenshtein, N. Tatti, and A. Gionis. The network-untangling problem: From interactions to activity
timelines. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases, pages
701–716. Springer, 2017.
- P. Rozenshtein, F. Bonchi, A. Gionis, M. Sozio, and N. Tatti. Finding events in temporal networks:
Segmentation meets densest-subgraph discovery. In 2018 IEEE International Conference on Data Mining
(ICDM), pages 397–406. IEEE, 2018.
- Y. Dhote, N. Mishra, and S. Sharma. Survey and analysis of temporal link prediction in online social networks.
In 2013 International Conference on Advances in Computing, Communications and Informatics (ICACCI),
pages 1178–1183. IEEE, 2013.
- L. Zhu, D. Guo, J. Yin, G. Ver Steeg, and A. Galstyan. Scalable temporal latent space inference for link
prediction in dynamic social networks. IEEE Transactions on Knowledge and Data Engineering, 28(10):
2765–2777, 2016.


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

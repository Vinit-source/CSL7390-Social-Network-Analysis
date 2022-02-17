# CSL7390-Social-Network-Analysis
Analytics on large social networks

This repository contains assignment work from CSL7390-Social-Network-Analysis course. 

* [Structural Measures](https://github.com/Vinit-source/CSL7390-Social-Network-Analysis/blob/main/Structural_Measures.ipynb): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Vinit-source/CSL7390-Social-Network-Analysis/blob/main/StructuralMeasures/Structural_Measures.ipynb)    
  Analysis of [Zachary's Karate Club](https://www.google.com/search?q=zachary%27s+karate+club&oq=zakary%27s+&aqs=chrome.1.69i57j0i13l7j0i13i457j46i13i175i199.5584j0j7&sourceid=chrome&ie=UTF-8) dataset and [ego-Facebook](http://snap.stanford.edu/data/ego-Facebook.html) dataset.
    * Node Count, Edge Count, Average Degree
    * Degree Distribution
    * Triangles
    * Diameter
    * Connected Components
    * Clustering Coefficient
    * Betweenness centrality (from scratch)
    * Closeness centrality (from scratch)
    * K-cores (basic algorithm)
    * Cliques (resource limits exceeded*)
* [Network Models](https://github.com/Vinit-source/CSL7390-Social-Network-Analysis/tree/main/NetworkModels/code): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)    
    * Generation of random graph using custom function.
    * Evaluation with benchmarks - networkx algorithms.
    * Generation of scale-free graph.
    * Structural Analysis of both the graphs for similar number of nodes and edges.
* [Influence Maximization](): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)    
    * Greedy algorithm over Independent Cascade model
    * Greedy algorithm over Linear Threshold model
    * Effectiveness of Greedy algorithm
* [Dynamic Influence Maximization](https://github.com/Vinit-source/CSL7390-Social-Network-Analysis/blob/main/group_project_IM_on_dynamic_graphs_survey/SNA_Project.ipynb): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Vinit-source/CSL7390-Social-Network-Analysis/blob/main/group_project_IM_on_dynamic_graphs_survey/SNA_Project.ipynb)    
Studied different algorithms on dynamic influence maximization and found Sieve Streaming to be the most efficient algorithm providing similar accuracy as Greedy. Experiments were performed in the sliding window streaming model.
    * Greedy algorithm [[Paper](https://dl.acm.org/doi/abs/10.1145/956750.956769)]
    * Influential Checkpoints [[Paper](https://arxiv.org/abs/1702.01586)]
    * Sieve Streaming [[Paper](https://dl.acm.org/doi/abs/10.1145/2623330.2623637)]
    * Random ([Reservoir Sampling](https://www.geeksforgeeks.org/reservoir-sampling/)) 

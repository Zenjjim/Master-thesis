# Exploring the Efficiency of Zero-Cost Proxies in NAS for Human Action Recognition

## Abstract
Neural Architecture Search (NAS) and Graph Convolutional Networks (GCNs) are two fields within machine learning that have undergone major development in recent years. Finding a GCN architecture which yields optimal results can be time-consuming and resource-intensive. Zero-cost proxies, which are designed only to require a single minibatch of training data to score a neural network, have been introduced to make this process more efficient. The core focus of this thesis is to investigate the application and performance of zero-cost proxies for evaluating GCNs within the context of Human Action Recognition (HAR) tasks as a first step towards using them in a NAS algorithm. Furthermore, given the need for further research, the study aims to bridge this gap by evaluating different zero-cost proxies on GCN architectures. To the best of our knowledge, the study is the first to explore how zero-cost proxies perform on GCNs. 

Through a series of analyses and experiments, the study demonstrates that integrating zero-cost proxies can significantly enhance the efficiency of NAS algorithms. The results reveal that the top-performing zero-cost proxies display a Spearman Rank Correlation ($\rho$) of approximately $0.8$, indicating a strong to very strong correlation. However, no substantial improvement in correlation is detected when analysing architectures as they are trained for several epochs, implying that the zero-cost proxies might be most efficient at the initialisation of the neural network. Attempts to combine zero-cost proxies through vote and weighted arithmetic mean are showing promise, but they are not resulting in significant improvement compared to the individual application of each zero-cost proxy. 

## Authors

[![](https://avatars.githubusercontent.com/u/23628986?size=50)](https://github.com/Zenjjim)
[![](https://avatars.githubusercontent.com/u/49594236?size=50)](https://github.com/maxschau)

![NTNU_logo](https://github.com/Zenjjim/Master-thesis/assets/23628986/ff41d8f3-41da-461b-bf91-0e1f919768fb)


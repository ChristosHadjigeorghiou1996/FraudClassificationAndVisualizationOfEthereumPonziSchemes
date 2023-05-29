# FraudClassificationAndVisualizationOfEthereumPonziSchemes

Classifying and Visualizing Cryptoponzies - this project consists of 2 python notebooks:
* classificationAndVisualization.ipynb: This holds the code for the smart contract Ponzi/non-Ponzi classifier and for the visualization of all the Ponzi contracts in the dataset, along with their creators
* temporalVisualization.ipynb: this contains the visualization of the transactions related to a single contract, in the form of a temporal network graph

The dataset of smart contracts used can be found under the the _Ponzi_contracts_ folder, in the `Ponzi_contracts.csv` file.

The `fullDataset.graphml` file can be imported into Cytoscape and similar network visualization softwares.

The code in `contractVisualization.html` and `wallet_info.html` were merged in a single html file which was the published under the link: http://cryptoponzi.herokuapp.com/


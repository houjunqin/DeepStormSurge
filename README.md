
<p align="center">
<img src="./assets/images/DSS.jpg" alt="Deep Storm Surge —— A repository of spatiotemporal deep learning models designed to serve as efficient surrogates for ADCIRC in forecasting and hindcasting storm surges" width=50% height=50%>
</>


<h1 align="center"> Deep Storm Surge</h1>
<h6 align="center"> A repository of spatiotemporal deep learning models designed to serve as efficient surrogates for ADCIRC in forecasting and hindcasting storm surges</h6>

The goal of this project is to accelerate computationally intensive and time-consuming numerical methods by integrating spatiotemporal deep learning techniques. This forms a hybrid framework: a numerical model such as ADCIRC is used to generate training data, which are then leveraged by a deep learning model for forecasting or hindcasting. 
Predicting storm surge water levels requires handling data that differs significantly from typical spatiotemporal benchmarks. This project addresses three primary complexities:

Extreme Scale: Networks ranging from hundreds of thousands to millions of nodes.

Temporal Constraints: Short-duration events, generally limited to two-week windows.

Feature Density: Over 10 integrated static and time-series features per node.

Most off-the-shelf models cannot scale to these requirements. By utilizing dynamic graph partitioning and optimized model architectures, this repository provides an effective framework for large-scale surge forecasting and hindcasting.
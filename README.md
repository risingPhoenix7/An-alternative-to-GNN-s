# An-alternative-to-GNN-s
Implementation of , we show that for many standard transductive node classification benchmarks, we can exceed or match the performance of state-of-the-art GNNs by combining shallow models that ignore the graph structure with two simple post-processing steps that exploit correlation in the label structure: (i) an “error correlation” that spreads residual errors in training data to correct errors in test data and (ii) a “prediction correlation” that smooths the predictions on the test data.

# An Alternative to GNNs for Graph Data

## Introduction
This project implements the novel approach described in the paper ["An Alternative to GNNs for Graph Data"](https://shorturl.at/jlBC3). It demonstrates how combining shallow models with two post-processing steps can effectively handle graph data for transductive node classification benchmarks.

## Abstract of the Paper
We show that for many standard transductive node classification benchmarks, we can exceed or match the performance of state-of-the-art GNNs by combining shallow models that ignore the graph structure with two simple post-processing steps that exploit correlation in the label structure: (i) an “error correlation” that spreads residual errors in training data to correct errors in test data and (ii) a “prediction correlation” that smooths the predictions on the test data.

# Datasets : Citeseer, Cora, US_County 2016 election

## Results:
![image](https://github.com/risingPhoenix7/An-alternative-to-GNN-s/assets/96655704/59727690-0df1-4a9e-af68-b4f0d0db754d)

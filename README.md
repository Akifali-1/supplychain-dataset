# Supply Chain Demand Forecasting Dataset (AF-GAT-LSTM)

This repository contains a graph-structured version of the **Store Item Demand Forecasting** dataset originally available on Kaggle:

https://www.kaggle.com/competitions/demand-forecasting-kernels-only

We reformatted the data for spatio-temporal graph forecasting tasks, enabling use with GAT-LSTM and other graph-based deep learning models.

## Contents

- `dataset/nodes.csv` — Node-level metadata (store-item pairs with attributes)
- `dataset/edges.csv` — Fully-connected graph edges connecting all nodes
- `dataset/sales.csv` — Time-series sales per node (daily demand) in pivot matrix format

## Statistics

- **Nodes:** 500 (10 stores × 50 items)
- **Edges:** 124,750 (fully-connected graph)
- **Time Steps:** 1,826 days
- **Unique Stores:** 10
- **Unique Items:** 50

## Citation

If you use this dataset, please cite:

> M. Akif Ali Parvez *et al.*, "Adaptive Fusion GAT-LSTM for Supply Chain Demand Forecasting," 2025.

## License

Released under the MIT License.

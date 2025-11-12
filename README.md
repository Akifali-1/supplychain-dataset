\# Supply Chain Demand Forecasting Dataset (AF-GAT-LSTM)



This repository contains a graph-structured version of the \*\*Store Item Demand Forecasting\*\* dataset originally available on Kaggle:

https://www.kaggle.com/competitions/demand-forecasting-kernels-only



We reformatted the data for spatio-temporal graph forecasting tasks, enabling use with GAT-LSTM and other graph-based deep learning models.



\## Contents

\- `data/nodes.csv` — Node-level metadata (SKUs with attributes)

\- `data/edges.csv` — Graph edges constructed from demand correlation and co-occurrence

\- `data/sales.csv` — Time-series sales per SKU (daily demand)



\## Statistics

\- \*\*Nodes:\*\* 501  

\- \*\*Edges:\*\* 29,000  

\- \*\*Time Steps:\*\* 1,827 days  

\- \*\*Store:\*\* Single-store subset (filtered from Kaggle source)



\## Citation

If you use this dataset, please cite:



> M. Akif Ali Parvez \*et al.\*, "Adaptive Fusion GAT-LSTM for Supply Chain Demand Forecasting," 2025.



\## License

Released under the MIT License.




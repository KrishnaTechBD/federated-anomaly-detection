# Methodology

## Problem Formulation
We formulate the central task for **Federated Intrusion Detection for IoT with Non-IID Partitioning** through the governing equation below.

$$w^{(t+1)}_{\mathrm{global}} = \sum_{k=1}^{K}\frac{n_k}{n}w_k^{(t)} + \mathcal{N}(0,\sigma^2 I)$$

## Variable Definitions
| Symbol | Definition | Value |
|---|---|---|
| w^{(t+1)}_{\mathrm{global}} | Updated global model weights | Derived |
| K | Number of clients | 10 |
| n_k | Samples at client k | Derived |
| n | Total samples across federation | Derived |
| \sigma^2 | Noise variance for privacy perturbation | Derived |

## Evaluation Logic
The repository is framed around benchmark-aware comparison, reproducible parameterization, and professor-friendly reporting.

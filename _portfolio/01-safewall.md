---
title: "SafeWall"
excerpt: "XGBoost-based HPC runtime prediction system that adds buffered walltime estimates to reduce premature job termination."
collection: portfolio
permalink: /projects/safewall/
github_url: "https://github.com/SPEAR-UIC/JSSPP26-SafeWall"
---

SafeWall is a runtime prediction project for HPC batch jobs. It trains an XGBoost regressor on historical workload traces and applies configurable buffer strategies so predicted walltime limits are less likely to terminate jobs early while still avoiding unnecessary over-allocation.

The current public repository includes the SafeWall notebook, Theta workload data, and documentation describing feature engineering, buffer families, and evaluation tradeoffs for high-performance computing workloads.

GitHub repository: [SPEAR-UIC/JSSPP26-SafeWall](https://github.com/SPEAR-UIC/JSSPP26-SafeWall)

---

## Codes  

This repository provides key scripts and modules that enable the practical application of the proposed multi-fidelity data meta-learning framework. The codebase covers the following aspects:  

### 1. Loss Function with Mask Constraints  
- **Description**: Implements customized loss functions that selectively ignore invalid or missing target values.  
- **Purpose**: Ensures that training focuses only on meaningful outputs (e.g., excluding zero or undefined responses), thereby improving model robustness and convergence.  

### 2. Incremental Model Updating with Expanding Datasets  
- **Description**: Supports **incremental learning** where the model can be updated as new datasets (low-fidelity, high-fidelity, or monitoring data) become available.  
- **Features**:  
  - Fine-tuning strategies for adapting to new fidelity levels.  
  - Mechanisms to mitigate catastrophic forgetting.  
- **Purpose**: Enables continuous model improvement without retraining from scratch, which is essential for long-term deployment.  

### 3. City-Scale Model Application  
- **Description**: Tools and pipelines for applying the trained models to **urban-scale building inventories**.  
- **Functions**:  
  - Batch processing of thousands of buildings.  
  - Integration with building metadata and seismic hazard scenarios.  
- **Purpose**: Demonstrates scalability of the proposed method for large-scale resilience assessment and rapid seismic response prediction across city clusters.  

---

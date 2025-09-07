---

## Dataset Details  

The repository contains three categories of datasets with varying levels of fidelity. These datasets are designed to support training, benchmarking, and validation of the proposed multi-fidelity data meta-learning framework.  

### 1. Low-Fidelity Dataset  
- **Description**: Numerical simulation data generated from simplified **2D Multi-Degree-of-Freedom (MDOF) models**.  
- **Scale**:  
  - **67 structural models** representing typical high-rise shear wall building configurations.  
  - **200 earthquake ground motion records** applied to each model.  
- **Output**: Floor-level seismic response parameters (e.g., peak floor accelerations, inter-story drift ratios).  
- **Purpose**: Provides large-scale but relatively coarse data to pre-train baseline models and establish initial predictive performance.  

### 2. High-Fidelity Dataset  
- **Description**: Seismic response data from **component-level finite element (FE) models**, capturing detailed structural behavior.  
- **Scale**:  
  - **20 high-rise shear wall buildings**, modeled with refined component-level details.  
  - Each building subjected to **20 ground motions**.  
- **Output**: Detailed response measures, including local deformation patterns and floor-level engineering demand parameters.  
- **Purpose**: Used to fine-tune models for higher accuracy and to bridge the fidelity gap between simplified simulations and real structures.  

### 3. Field Monitoring Dataset  
- **Description**: Real-world structural response data obtained from **instrumented high-rise shear wall buildings**.  
- **Source**: Collected through strong-motion monitoring systems.  
- **Content**: Includes acceleration time histories, peak response metrics, and structural parameters when available.  
- **Purpose**: Provides real-world validation for models trained on simulation data, ensuring generalizability and robustness.  

---


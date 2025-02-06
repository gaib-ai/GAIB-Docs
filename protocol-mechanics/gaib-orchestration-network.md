# GAIB Orchestration Network

## **System Components and Architecture**

In order to minimize trust assumptions in the financial infrastructure that GAIB is building for AI compute, GAIB introduces the Orchestration Network. Through network democratization, data collection from GAIB's cloud & data center partners, robust data validation, and secure data management, GAIB hands the power of supervising the underlying assets of a new financial primitive back to the community. The updated architecture consists of the following components:

#### High-Level Components

1. **GAIB Inspector:** Installed on GPU clusters for hardware monitoring and data reporting.
2. **Supervisor Node:** Supervises GPU clusters by validating raw data submitted by GAIB Inspectors.
3. **Ground Truth Service:** Serves as a log of the consensus between supervised nodes to maintain and manage validated ground truth data.&#x20;

<figure><img src="../.gitbook/assets/Orchestration Network.svg" alt=""><figcaption><p>Orchestration Network Architecture</p></figcaption></figure>

### **GAIB Inspector**

#### Role&#x20;

The GAIB Inspector is a lightweight, installable binary designed to collect hardware performance metrics in real-time and report them to Supervisor Nodes, which will be subsequently stored in the ground truth service.

#### Functionality:

1. Hardware Integration:

* Utilizes NVIDIA Management Library (NVML) for GPU performance monitoring.
* Abstracts hardware-specific details to ensure compatibility across GPU models.

2. Data Inspection:

* Collects metrics, including GPU utilization (%), memory usage (VRAM), power consumption, location, etc.
* Configurable sampling intervals to balance system overhead and granularity.

3. Data Transmission:

* Reports raw metrics to the Google Bigtable ground truth service.
* Sends data to Supervisor Nodes for validation.&#x20;

### **Supervisor Node**

#### Role

Supervisor Node collects data from GPU inspectors, validates data, and tries to reach a consensus.

#### Functionality:

1. Data Supervision:

* Retrieves raw data from GAIB Inspectors.
* Authenticate data using cryptography signatures.

2. Consensus Mechanism:

* Uses PoA (Proof-of-Authority) model to validate data and reach consensus.

## **Ground Truth Service**

#### Role

Google Bigtable serves as the repository to log all GPU performance data, acting as the reference of truth for validation and financialization, similar to archive nodes in a lot of blockchain systems.&#x20;

#### Functionality: Data Management

* Stores raw data received from GAIB Inspectors.
* Maintains supervisory flags set by Supervisor Nodes.

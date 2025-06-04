# SiriusBI - A Comprehensive LLM-powered Solution for Data Analytics in Business Intelligence

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> ​**Note**: This repository serves as the technical companion for our VLDB 2025 paper. Code implementation will be released pending corporate approval. 

## 🚀 Key Innovations
- ​**Practical ChatBI System**  
  A unified system integrating four core functionalities — knowledge management, multi-round dialogue with querying, SQL generation, and data insight.
- ​**New Dialogue Analysis Mechanism**  
  MRD-Q consists of semantic completion, knowledge-guided clarification, and proactive querying processes to effectively address issues raised by ambiguous or incomplete queries in real-world scenarios.
- ​**Economic Domain Adaptation Strategy**  
  A dynamic strategy selection mechanism for SQL generation conditioned on data characteristics.

## 📊 NL2SQL Performance
### On Academic Benchmarks
| Dataset       | EX          |   
|---------------|-------------|
| BIRD          | 68.97%      | 
| MRD-BIRD      | 51.14%      | 
### On Industrial Datasets
| Dataset       | UEX         |   
|---------------|-------------|
| SRD-Industry  | 83.97%      | 
| MRD-Industry  | 62.50%      | 

## 📂 Dataset Access
1. ​**MRD-BIRD**  
   It is available under the directory `MRD-BIRD`.
2. **SRD/MRD-Industry**
   They are partially available after anonymized process under the directory `Industrial Datasets`.

## 🔧 System Architecture

![WorkFlow](SiriusBI_workflow.png)

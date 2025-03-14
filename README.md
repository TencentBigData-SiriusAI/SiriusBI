# SiriusBI - A Comprehensive LLM-powered Solution for Data Analytics in Business Intelligence

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> ​**Note**: This repository serves as the technical companion for our VLDB 2025 paper. Code implementation will be released pending corporate approval. 

[中文文档](README_CN.md) | [Paper (Preview)](https://arxiv.org/abs/2411.06102) | 

## 🚀 Key Innovations
- ​**MRD-Q (Multi-Resolution Domain Quantization)**  
  Dynamic knowledge quantization across table-level statistics to column-level constraints
- ​**Confidence-Driven SQL Generation**  
  Contains one-step SQL generation method based on automated data preparation and two-step SQL generation method based on Semantic Intermediate Representation (SIR).
- ​**Enterprise Knowledge Bootstrapping**  
  Automated knowledge graph construction for Snowflake/BigQuery/Spark

## 📊 Benchmark Results
### Performance on Industrial Benchmarks
| Dataset       | EX          |   
|---------------|-------------|
| BIRD          | 68.97%      | 
| MRD-BIRD      | 51.14%      | 

### Comparative Analysis
![Accuracy Comparison](docs/images/benchmark.png)

## 📂 Dataset Access
### Publicly Available Benchmarks
1. ​**SRD/MRD-Industry**  
   Cannot be disclosed due to data privacy reasons.

2. ​**MRD-BIRD Extension**  
   Available upon xxxx.

## 🔧 System Architecture

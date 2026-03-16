# LogiPredict Analytics — Distributed Data Science Pipeline for Shipment Delay Prediction
## Overview
LogiPredict Analytics is building a distributed, cloud‑based data science pipeline to analyze large‑scale logistics datasets and predict shipment delivery delays. By leveraging AWS services such as Amazon S3 and Amazon SageMaker, the project enables logistics teams to shift from reactive issue resolution to proactive delay mitigation.

This repository contains the code, notebooks, and documentation used to ingest, process, analyze, and model shipment data in a scalable cloud environment.

## Project Goals
* Build a distributed cloud‑based data pipeline for logistics data processing
* Analyze large shipment datasets to identify patterns related to delivery delays
* Train machine learning models to predict shipment delays early in the shipment lifecycle
* Provide actionable insights to improve shipment planning and operational efficiency

Demonstrate scalable data science workflows using AWS infrastructure

## Data Sources
Publicly available Kaggle datasets are used in this project:

* **Logistics and Supply Chain Dataset**  
https://www.kaggle.com/datasets/datasetengineer/logistics-and-supply-chain-dataset (kaggle.com in Bing)

* **Delivery Logistics Dataset (India Multi‑Partner)**  
https://www.kaggle.com/datasets/muhammadahmaddaar/delivery-logistics-dataset-india-multi-partner (kaggle.com in Bing)

* **Cross‑Border Trade and Customs Delay Dataset**  
https://www.kaggle.com/datasets/ziya07/cross-border-trade-and-customs-delay-dataset (kaggle.com in Bing)

Each dataset contains 10,000+ records, making them suitable for scalable cloud processing and machine learning.

## Cloud Architecture & Data Pipeline
**Data Storage**
All datasets are stored in Amazon S3. Due to AWS Learner Lab account isolation, each team member uses their own S3 bucket.
Example structure:
Code
s3://logipredict-data/raw/shipment_datasets/

## Pipeline Steps
Ingest raw Kaggle datasets
* Upload raw CSV files to Amazon S3
* Process and explore data using Amazon SageMaker Studio
* Train machine learning models to predict shipment delays
* Store processed datasets and model artifacts back into S3

## Team
**LogiPredict Analytics**
* Bereket Tarekegn
* Jason Avalos Morfin
* Jameel Saccoh

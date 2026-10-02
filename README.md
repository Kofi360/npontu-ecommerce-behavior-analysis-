# E-Commerce Customer Analytics & Churn Prediction

**Applicant Name:** Kofi Antwi Bosiako
**Target Role:** Intelligent Systems Services Engineer(NSS)
**Organization:** Npontu Technologies Ltd
**Date of Assignment:** September 29, 2026
**Assignment Title:** Analyzing Customer Behavior for E-commerce Insights

## Executive Summary
This repository contains the technical assessment submission for the Intelligent Systems Services Engineer position at Npontu Technologies Ltd.

The solution implements an end-to-end data pipeline demonstrating synthetic e-commerce event generation, data cleaning, advanced behavioral feature engineering, a real-time streaming architecture design, and an imbalanced predictive churn model.

## Key Project Highlights

• Synthetic Event Ingestion: Generates 20,000 realistic e-commerce session and transaction records while explicitly incorporating real-world data quality anomalies (~5% missing values, negative purchase values, duplicate records, and age boundaries).
• Exploratory Data Analysis & Cleaning: Performs deduplication, range validation, and missing value imputations.
• Feature Engineering: Aggregates point-in-time transactions into customer behavioral profiles, including RFM metrics (Recency, Frequency, Monetary), discount reliance indices, and cart conversion ratios.
• Big Data Architecture Design: Designs a scalable real-time streaming stack utilizing Apache Kafka for low-latency event streaming, Elasticsearch for document aggregation, and Grafana for monitoring dashboards, supported by a working Python streaming consumer simulation.
• Imbalanced Predictive Modeling: Benchmarks Logistic Regression against a Random Forest classifier using SMOTE oversampling within Stratified K-Fold Cross Validation loops to predict customer churn accurately.
• Business Actionability: Maps model churn predictors directly to Npontu's product ecosystem (e.g., triggering automated retention SMS/WhatsApp messages via the Deywuro VAS gateway and surfacing churn risk profiles in Kedebah CRM).

# Data Engineering YouTube Data Analysis

## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Architecture Diagram
<img src="architecture.jpeg">

## Project Steps
Data Ingestion – Implemented a mechanism to ingest data from various sources into a centralized system.

ETL System – Developed a robust ETL pipeline to transform raw data into a structured format suitable for analysis.

Data Lake – Utilized Amazon S3 to build a centralized data lake to store data from multiple sources securely and efficiently.

Scalability – Ensured the architecture is scalable to handle growing volumes of data using AWS services.

Cloud Infrastructure – Leveraged AWS cloud platform for data processing and storage, eliminating dependency on local infrastructure.

Reporting – Created interactive dashboards using Amazon QuickSight to generate insights and answer business questions effectively.

### Services Used: Amazon S3, AWS IAM, Amazon QuickSight, AWS Glue, AWS Lambda, AWS Athena.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new




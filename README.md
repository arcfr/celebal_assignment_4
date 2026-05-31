# Azure Data Factory Pipeline – Week 4 Assignment

## Overview
This assignment demonstrates a simple end-to-end data pipeline using Azure services to copy data from a source Blob Storage container to a destination container using Azure Data Factory.

## Architecture
Source CSV (Blob Storage) → Azure Data Factory → Destination Blob Storage

## Services Used(Central India Region)
- Azure Resource Group
- Azure Storage Account (Blob Storage)
- Azure Data Factory
- Linked Services
- Datasets
- Get Metadata Activity
- Copy Data Activity

## Steps Followed
- Created Resource Group and Storage Account
- Created two Blob containers: source and destination
- Uploaded CSV file to source container
- Created Azure Data Factory instance
- Configured Linked Service to Blob Storage
- Created source and destination datasets
- Built pipeline with Get Metadata and Copy Data activities
- Validated, published, and executed pipeline
- Verified output in destination container

## Output
- Pipeline executed successfully
- CSV file copied from source to destination container

By
Archit Sahay

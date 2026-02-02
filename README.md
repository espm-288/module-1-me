# ESPM 288 - Module 1: Working with Tabular Data Larger Than RAM

## Overview

This module teaches high-performance data handling techniques for working with datasets that exceed available memory. Using modern tools like `duckdbfs` and DuckDB, you'll learn to efficiently query and analyze large-scale tabular data without loading entire datasets into RAM.

## Learning Objectives

- Connect to remote cloud-based datasets (AWS S3) without downloading them locally
- Use lazy evaluation with `duckdbfs::open_dataset()` for efficient data access
- Apply `dplyr` verbs that translate to optimized SQL queries
- Filter and query large datasets before collecting results into memory
- Work with the EXIOBASE 3.8.1 global Multi-Regional Input-Output database

## Case Study

This module uses **EXIOBASE 3.8.1**, a comprehensive global database tracking:
- Economic transactions across 44 countries (1995-2022)
- Environmental impacts including carbon emissions, water usage, and land use
- Multi-Regional Input-Output (MRIO) relationships between industries and regions

The dataset is hosted on Source Cooperative and accessed directly from S3 storage, demonstrating modern cloud-native data workflows.

## Key Technologies

- **duckdbfs**: High-performance interface for working with remote datasets
- **DuckDB**: Fast analytical database engine optimized for OLAP queries
- **dplyr**: Data manipulation with lazy evaluation
- **Quarto**: Reproducible document generation

## Getting Started

Open [tabular-data.qmd](tabular-data.qmd) to begin working through the exercises.

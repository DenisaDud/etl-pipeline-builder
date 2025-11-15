# etl-pipeline-builder
# ETL Pipeline Builder (Go)

A lightweight and extensible ETL (Extract–Transform–Load) framework written in Go.  
The system allows data engineers to define pipelines, extract data from various sources, transform data with configurable rules, and load it into different destinations.

## Project Overview

This project aims to provide:

- Multiple data source connectors (files, APIs, databases)  
- Transformation operations (map, filter, aggregate)  
- Configurable pipelines using YAML  
- Scheduling & automation  
- Error handling and retries  
- Data validation rules  
- Monitoring and logging  

### Project Structure
cmd/etl/main.go # Entry point
internal/extractor # Extractors (future)
internal/transformer # Transformation logic
internal/loader # Loaders
internal/pipeline # Pipeline orchestrator
configs/ # YAML configs

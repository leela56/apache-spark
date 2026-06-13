# Apache Spark / PySpark Data Pipeline

Production-style PySpark batch processing pipeline with a full CI/CD setup (Jenkinsfile), pytest test suite, and structured configuration management.

## Key Features

- Batch data processing pipeline built with PySpark
- Pytest test suite for unit testing Spark transformations
- Jenkinsfile for automated CI/CD integration
- Pipenv-managed dependencies
- log4j logging configuration

## Stack

- PySpark / Apache Spark
- Python (Pipenv)
- pytest
- Jenkins (CI/CD)

## Project Structure

```
apache-spark/
├── conf/               # Spark and app configuration
├── lib/                # Core pipeline modules
├── test_data/          # Sample datasets for testing
├── sbdl_main.py        # Main pipeline entry point
├── sbdl_submit.sh      # Spark submit script
├── test_pytest_sbdl.py # Pytest test suite
├── Jenkinsfile         # CI/CD pipeline definition
└── Pipfile             # Dependencies
```

## Running Tests

```bash
pipenv install
pipenv run pytest test_pytest_sbdl.py
```

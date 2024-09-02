# Sample API - FastAPI Dockerization

This repository contains the Dockerized version of the Sample API, a FastAPI application.

## Getting Started

To run the application locally using Docker:

```bash
docker build -t sample-api .
docker run -p 8000:8000 sample-api


## GitHub Actions Workflow

This repository includes a GitHub Actions workflow that runs unit tests, builds the Docker image, and publishes it to the GitHub Container Registry.

### How to Trigger the Workflow
- The workflow is triggered automatically on any push to the `main` branch or any pull request targeting the `main` branch.
- To manually trigger the workflow, go to the "Actions" tab in this repository and click on "Run workflow".

### Instructions to Pull and Run the Docker Image
You can pull the Docker image from the GitHub Container Registry using the following command:

```bash
docker pull ghcr.io/moolaakhila97/sample-api:latest

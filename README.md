
# CI/CD Final Project

## Project Overview
This project demonstrates Continuous Integration and Continuous Delivery (CI/CD) using GitHub Actions, Tekton, and OpenShift.

## Technologies Used
- Python
- Git and GitHub
- GitHub Actions
- Flake8
- Nose testing framework
- Tekton Pipelines
- OpenShift
- Buildah

## CI Workflow
The GitHub Actions workflow automatically installs dependencies, performs code linting using Flake8, and runs unit tests using Nose when changes are pushed or pull requests are created for the main branch.

## OpenShift Pipeline
The Tekton pipeline automates source cleanup, Git cloning, linting, testing, container image building, and application deployment.

## Purpose
To demonstrate an automated CI/CD pipeline that improves code quality, testing, containerization, and application deployment.

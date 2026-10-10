# devops-deployment-pipeline

A multi-stage deployment pipeline using GitHub Actions.

## Project Overview

This repository adapts [activity-log](https://github.com/TheDanniCraft/activity-log), a GitHub Action that automatically updates a README with recent GitHub activity.

The purpose of this assignment is to implement a deployment pipeline with separate development, staging, and production environments.

## Deployment Pipeline

- **Build:** Build and test the application.
- **Dev:** Publish a development release.
- **Staging:** Validate the release before production.
- **Production:** Publish the production release after human approval.

## Technologies

- GitHub Actions
- GitHub Environments
- GitHub Releases
- Environment variables
- Deployment protection rules

## Upstream Project

Original project: https://github.com/TheDanniCraft/activity-log

See the original repository for the software's complete usage instructions and configuration options.

Automatic issue closure test
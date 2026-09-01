# gitops

## Overview

This repository is used for **Flux GitOps** to deploy Docker images on local Docker Desktop infrastructure.

## Purpose

This GitOps repository manages containerized applications using Flux, enabling:
- Automated deployment of Docker images to local Docker Desktop
- Version control and git-driven infrastructure management
- Continuous synchronization between git and your local Kubernetes cluster

## Getting Started

### Prerequisites

- Docker Desktop with Kubernetes enabled
- Flux CLI installed
- Git repository access

### Setup

1. Clone this repository
2. Bootstrap Flux in your Docker Desktop Kubernetes cluster
3. Flux will automatically reconcile the desired state from this repository

## Repository Structure

This repository contains Flux manifests and configurations for managing deployments on your local Docker Desktop infrastructure.

## Usage

Push changes to this repository to trigger automatic deployments to your local Docker Desktop cluster through Flux.

---

For more information about Flux, visit: https://fluxcd.io/

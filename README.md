# Inconsistent Docker Builds Due to `ubuntu:latest`

This repository demonstrates a common issue in Dockerfiles: using `ubuntu:latest` as the base image and neglecting to clean up after package installations. This can lead to inconsistent build results and larger image sizes.

The `Dockerfile` shows the problematic code.  The `DockerfileFixed` shows the corrected version.
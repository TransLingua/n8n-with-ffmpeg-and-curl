# Custom n8n Docker Image

This repository maintains a custom n8n Docker image with additional packages installed:

- ffmpeg
- curl

## Features

- Automatically stays up-to-date with the latest n8n releases
- Builds and pushes to Docker Hub daily if a new n8n version is available
- Maintains both versioned tags and a "latest" tag

## Usage

Pull the image from Docker Hub:

```bash
docker pull yourusername/n8n-custom:latest
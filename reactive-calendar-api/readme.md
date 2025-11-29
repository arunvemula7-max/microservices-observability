# Google Calendar API Integration

This repository provides a streamlined interface for interacting with the Google Calendar API, allowing for efficient event management and integration into automated workflows.

## Usage

To create a new event via the API, use the following POST request:

```bash
curl -X POST -H "Content-Type: application/json" -H "Accept: application/json" -H "Google-Calendar-API-User-Key: 12345" -d "{ \"item\":\"blah\" }" http://localhost:8070/api/v1/event
```

## Maintainer

**Arun Kumar Reddy Vemula**
AI/ML Engineer
Email: arunkumarreddy952@gmail.com

Arun is an AI/ML Engineer with over 5 years of experience building practical machine learning solutions for autonomous vehicles, fraud detection, and industrial IoT. He specializes in deploying real-time computer vision models, optimizing cloud inference costs through quantization, and managing scalable workflows using Kubernetes and CI/CD pipelines. Arun focuses on turning complex business problems into high-performance AI solutions that deliver measurable results.
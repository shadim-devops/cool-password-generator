# Cool Password Generator

Simple static HTML password generator.

## Tech stack
- HTML
- Docker
- Nginx

## Purpose

This project demonstrates basic Docker containerization of a static web application
using Nginx, including image build and container runtime configuration.

Application is available at: http://localhost:8080

## Run with Docker

```bash
docker build -t cool-password-generator . && docker run -p 8080:80 cool-password-generator

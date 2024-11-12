# DevOps Demo Repository

This repository demonstrates a CI/CD pipeline with GitHub Actions to automatically test, build, and push a Docker image to Docker Hub.

## Docker Image Screenshot

![Docker Hub Image Screenshot](images/project2.PNG)

## Project Structure
- **app/**: Application code
- **tests/**: Test scripts
- **Dockerfile**: Docker configuration
- **.github/workflows/**: CI/CD workflow

## CI/CD Workflow
- **Tests**: Runs pytest for unit testing.
- **Build and Push**: Builds the Docker image and pushes it to Docker Hub.

## How to Use
1. Pull the Docker image:
   ```bash
   docker pull lam79/devops_demo:latest
2. Run the container:
   docker run --rm lam79/devops_demo:latest

3. Commit the Changes**
- After editing the README file, commit and push the changes to GitHub:
  ```bash
  git add README.md images/project2.PNG
  git commit -m "Added Docker Hub screenshot to README"
  git push origin main

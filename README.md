# CI/CD with Jenkins & Docker

This project demonstrates a simple CI/CD pipeline using Jenkins, Docker, and Flask.

## Steps:
1. Clone the repository
2. Build Docker image: `docker build -t myapp .`
3. Run the container: `docker run -d -p 9090:9090 myapp`
4. Open `http://13.235.51.84/:9090` in browser

## Jenkins Pipeline:
- Clone Repo
- Build Docker Image
- Deploy to EC2

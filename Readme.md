# Dockerized Flask App with GitHub Actions  

This is a simple Flask application that is containerized using Docker and automatically pushed to Docker Hub using GitHub Actions.  

## Features  
- Flask application in a Docker container  
- GitHub Actions workflow for automated builds and pushes  
- Deployment-ready setup  

## Setup  

### 1. Clone the Repository  
```sh  
git clone https://github.com/iAmKabiru/flask-docker-github-action.git  
cd flask-docker-github-action  
```  

### 2. Build the Docker Image  
```sh  
docker build -t iamkabiru/flask-app .  
```  

### 3. Run the Container  
```sh  
docker run -p 5000:5000 iamkabiru/flask-app  
```  

### 4. GitHub Actions Workflow  
The GitHub Actions workflow automatically builds and pushes the Docker image to Docker Hub on every push to the `main` branch.  

## Contributing  
Feel free to submit issues or pull requests!  

## License  
[MIT License](LICENSE)  


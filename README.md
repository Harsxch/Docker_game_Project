# Docker_game_Project
🕹️ 2048 Game - Dockerized & Deployed on AWS Elastic Beanstalk 🚀
Welcome to the 2048 Game, a simple yet addictive sliding tile puzzle game, built and containerized with Docker and deployed seamlessly on AWS Elastic Beanstalk. This project demonstrates a full DevOps workflow from containerization to cloud deployment.

📌 Project Overview
🎮 Game: 2048 - A classic puzzle game where players slide numbered tiles to combine them and reach 2048.
🐳 Dockerized: The game is containerized using Docker for easy portability.
☁️ AWS Elastic Beanstalk: Automated deployment and scaling of the game on the cloud.
📡 Nginx Web Server: Serves the game for high availability and performance.
⚙️ CI/CD Ready: Can be integrated into a DevOps pipeline for automated deployment.
🛠️ Tech Stack
Containerization: Docker
Web Server: Nginx
Cloud Deployment: AWS Elastic Beanstalk
Infrastructure as Code: Dockerfile for automated builds
🚀 How It Works
Dockerized the game using a Dockerfile.
Built and tagged the Docker image.
Pushed the image to a container registry (optional: Docker Hub / AWS ECR).
Deployed the containerized application using AWS Elastic Beanstalk.
📜 Setup Instructions
Run Locally using Docker
sh
Copy
Edit
git clone https://github.com/Harsxch/2048-game.git
cd 2048-game
docker build -t 2048-game .
docker run -d -p 80:80 2048-game
Now, open http://localhost in your browser and play! 🎮

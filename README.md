📄 DigiResume

DigiResume is a modern, containerized digital portfolio and resume showcase. It serves as a central hub for my professional journey, featuring detailed project breakdowns, technical blogs, and interactive mini-apps.
🚀 Overview

This project isn't just a static resume; it's a demonstration of a full DevOps lifecycle. Built with a clean HTML/CSS frontend, it is fully containerized and ready for cloud-native deployment.

    Live Demo: sharanch.dev

    Core Focus: High availability, performance, and clean documentation.

🛠 Tech Stack

    Frontend: HTML5, CSS3, JavaScript

    Infrastructure: Docker, Kubernetes (EKS)

    Deployment: GitHub Pages (via CNAME) / Containerized Environments

    CI/CD: GitHub Actions

📂 Project Structure
Bash

├── assets/             # Images, PDFs, and static media
├── blogs/              # Technical write-ups and articles
├── miniapps/           # Interactive JavaScript utilities
├── projects/           # Detailed case studies of technical work
├── Dockerfile          # Container configuration
├── deployment.yaml     # Kubernetes manifest for orchestration
└── index.html          # Main entry point

🐳 Getting Started (Local Development)
Run with Docker

If you want to view the resume locally using the containerized setup:

    Build the image:
    Bash

    docker build -t digiresume .

    Run the container:
    Bash

    docker run -p 8080:80 digiresume

    Visit http://localhost:8080 in your browser.

Deploy to Kubernetes

The repository includes a deployment.yaml for scaling the resume in a K8s cluster:
Bash

kubectl apply -f deployment.yaml

✍️ Content Sections

    Blogs: I write about SRE practices, Linux internals, and automation.

    Projects: Showcasing work with AWS, Kubernetes, and Python automation.

    Mini-Apps: Small functional tools built to solve specific problems or practice coding logic.

👨‍💻 About Me

I am a Site Reliability Engineer passionate about building scalable infrastructure and automating "all the things." Beyond the terminal, I'm a movie enthusiast and a calisthenics practitioner.

    Experience: 4+ Years in DevOps/SRE

    Location: India 

    Tech Interests: K8s, Python, Local LLMs, and Linux.

Created and maintained by Sharan.
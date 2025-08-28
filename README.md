# 🚀 Docker-Projects  

This repository contains **Docker practice projects**.  
The applications inside were forked from open-source projects, but the main focus here is on:  

- Writing **Dockerfiles**  
- Building Docker **images**  
- Running applications in **containers**  
- Exposing ports and accessing apps via browser  
- Organizing multiple Dockerized projects in one repo  

Note: I did not develop the base applications. My focus was on creating Dockerfiles and containerizing them as part of my Docker practice. 

---

## 📂 Projects  

### 1️⃣ SnakeGame-2D  
- Simple 2D Snake Game built with **HTML, CSS, JavaScript**  
- Dockerized using **nginx:alpine** as the base image  
- Steps:  
  ```bash
  docker build -t snake-game-2d .
  docker run -d -p 8080:80 snake-game-2d

### 1️⃣ Calculator Project

- Simple Calculator web app built with **HTML, CSS, JavaScript**.  
- Dockerized using **nginx:alpine** as the base image.
- Steps:
  ```bash
  docker build -t calculator .
  docker run -d -p 8080:80 calculator

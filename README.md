# 🚀 Docker Projects

This repository contains multiple small projects that I am practicing with Docker.  
⚠️ **Note:** I did not develop these applications. They are **forked/cloned from open-source repositories** and containerized for learning Docker.

Each project is organized in its own folder.

---

## 📌 1. Snake Game 2D

A **classic Snake Game** built with JavaScript, containerized with Nginx in Docker.

### 🔧 How to Run
```bash
docker build -t snake-game .
```
```bash
docker run -d -p 8081:80 snake-game
```

---

## 📌 2. Calculator Web App

A **simple Calculator app** built with HTML, CSS, and JavaScript, served with Nginx in Docker.

### 🔧 How to Run
```bash
docker build -t calculator-app .
```
```bash
docker run -d -p 8082:80 calculator-app
```

---

## 📌 3. Django ToDo App

A simple **Django-based ToDo application**, containerized with Docker.

### 🔧 How to Run
```bash
docker build -t django-todo .
```
```bash
docker run -d -p 8000:8000 django-todo
```

---

## 📌 4. Java Quotes App

A **Java-based Quotes generator application**, containerized with Docker.

### 🔧 How to Run
```bash
docker build -t java-quotes-app .
```
```bash
docker run -d -p 8000:8000 java-quotes-app
```

---

## 📖 Notes
- These projects are for **practice and learning Docker**.  
- ⚠️ **I did not develop these apps.** They are forked/cloned to practice Dockerizing applications.  
- Each project runs in its **own container** and is independent.


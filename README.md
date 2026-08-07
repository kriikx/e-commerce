# Amazon Clone 🛒🐳

A frontend **Amazon Clone** built using **HTML and CSS**, and containerized using **Docker with Nginx**.

This project recreates the basic layout and visual design of an Amazon-style e-commerce website and is intended for frontend and Docker practice.

## 📁 Project Structure

```text
E-COMMERCE/
│
├── images/
├── .gitignore
├── Dockerfile
├── index.html
├── README.md
└── style.css
```

## 🚀 Features

- Amazon-inspired navigation bar
- Search bar UI
- Product sections and product cards
- Product images
- Category sections
- Responsive styling
- Footer section
- Dockerized using Nginx

## 🛠️ Technologies Used

- **HTML5** – Website structure
- **CSS3** – Styling and layout
- **Docker** – Containerization
- **Nginx** – Web server

> No JavaScript, frameworks, backend, or database are used.

## 🐳 Run with Docker

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd E-COMMERCE
```

### 2. Build the Docker image

```bash
docker build -t amazon-clone .
```

### 3. Run the container

```bash
docker run -d -p 8080:80 --name amazon-clone amazon-clone
```

### 4. Open the website

Open:

```text
http://localhost:8080
```

Your Amazon Clone is now running inside a Docker container.

## 🔍 Docker Commands

Check running containers:

```bash
docker ps
```

Stop the container:

```bash
docker stop amazon-clone
```

Start it again:

```bash
docker start amazon-clone
```

Remove the container:

```bash
docker rm -f amazon-clone
```

## 🐳 Dockerfile

```dockerfile
FROM nginx:alpine

COPY . /usr/share/nginx/html

EXPOSE 80
```

Nginx serves the HTML, CSS, and image files from the Docker container.

## 🔄 After Making Changes

If you modify `index.html`, `style.css`, or files inside `images/`, rebuild the image:

```bash
docker stop amazon-clone
docker rm amazon-clone
docker build -t amazon-clone .
docker run -d -p 8080:80 --name amazon-clone amazon-clone
```

## 🎯 Learning Objectives

This project was created to practice:

- HTML page structure
- CSS styling
- Flexbox and layout
- Creating product sections
- Organizing frontend project files
- Docker images and containers
- Serving a static website using Nginx

## 🔮 Future Improvements

- Add JavaScript functionality
- Add shopping cart functionality
- Add product search and filtering
- Add login/signup pages
- Add product details pages
- Add a backend and database
- Make the website fully responsive
- Deploy the Dockerized application

---

⭐ If you found this project useful, consider giving the repository a star!

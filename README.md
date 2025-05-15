# Dockerfile Practice Repository

Welcome to the **Dockerfile Practice** repository!  
This repository contains practice examples and exercises focused on learning how to write and use Dockerfiles effectively for containerizing applications.

---

## 🚀 What You'll Find Here

- Sample Dockerfiles demonstrating best practices  
- Step-by-step instructions for building Docker images  
- Running containers based on custom images  
- Using different base images for various applications  
- Multi-stage builds and optimization techniques  
- Basic Docker commands for image and container management  

---

## 📂 Repository Structure

```

Dockerfile/
├── Dockerfile               # Main Dockerfile example(s)
├── README.md                # This documentation file
└── sample-app/              # Example application to containerize
├── app.js
├── package.json
└── ...

````

---

## 🛠️ How to Use

1. **Clone the Repository**

```bash
git clone https://github.com/santhu643/Dockerfile.git
cd Dockerfile
````

2. **Build a Docker Image**

```bash
docker build -t my-app-image .
```

3. **Run a Docker Container**

```bash
docker run -d -p 3000:3000 my-app-image
```

4. **Verify the Application**

Open your browser and navigate to `http://localhost:3000` (or the port you exposed).

5. **Common Docker Commands**

* List running containers: `docker ps`
* Stop a container: `docker stop <container_id>`
* Remove an image: `docker rmi <image_id>`

---

## 🎯 Goals and Learning Outcomes

* Learn how to write efficient Dockerfiles for various apps
* Understand container lifecycle and management commands
* Explore best practices for image optimization
* Gain confidence in containerizing Node.js and other applications
* Prepare for real-world Docker usage in development and deployment

---

## 📬 Connect with Me
🔗 LinkedIn - https://www.linkedin.com/in/santhiya-prakash-87449425a/

💻 GitHub - https://github.com/santhu643

🧠 LeetCode - https://leetcode.com/u/santhiyaprakash/

---

## 📄 License

This repository is licensed under the MIT License.

---

**Happy Dockerizing! 🐳🚀**

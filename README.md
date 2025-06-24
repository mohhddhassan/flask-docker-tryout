````markdown
# Flask App Dockerized 🚀

This is a simple Flask web application containerized using Docker.  
It serves as a hands-on tryout to understand how Dockerfiles and images work.

---

## 🐳 What’s Inside?

- A basic Flask app (`app.py`)
- A `Dockerfile` to build the image
- A `requirements.txt` for dependencies

---

## 🔧 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/mohhddhassan/flask-docker-tryout.git
cd flask-docker-tryout
````

### 2. Build the Docker image

```bash
docker build -t flask-hello .
```

### 3. Run the container

```bash
docker run -p 5000:5000 flask-hello
```

Visit 👉 `http://localhost:5000` in your browser.

---

## 📂 File Structure

```
flask-docker-tryout/
├── app.py
├── requirements.txt
└── Dockerfile
```

---

## 🧠 What I Learned

* Writing a basic `Dockerfile`
* Using `docker build` to create images
* Running Flask apps inside Docker containers

---

## 📝 Notes

This is a beginner-level tryout — next step: Docker Compose + multi-container setup!

```


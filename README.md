# 🦍 Kong API Gateway Playground

Welcome to the **Kong API Gateway** testing repo!  
This is your **sandbox** for exploring and experimenting with all the cool features Kong has to offer. 🧪🚀

---

## 🔌 Focus Areas

This project is mainly focused on:

- 🔍 **Testing Kong plugins**
- ⚙️ **Configuring plugins** to enhance API behavior
- 🧱 **Learning declarative configuration** with YAML

Whether you're playing with **rate-limiting**, **authentication**, **logging**, or custom plugins — this is the place! 🎯

---

## 🧑‍💻 Kong Manager

**Kong Manager** is the slick web-based UI for managing Kong! 🎛️

- 📍 Access it at: [http://localhost:8002](http://localhost:8002)
- 🧭 View and manage **routes**, **services**, **plugins**, and more — visually!
- 🧘 Perfect for when you're tired of typing out `curl` commands 😄

---

## 🐳 Running with Docker

This setup uses **Docker Compose** to spin up Kong and its dependencies.

To run a specific compose file (like `kong.yaml`), use:

```bash
docker-compose -f kong.yaml up
```

To stop the containers, use:

```bash
docker-compose down
```
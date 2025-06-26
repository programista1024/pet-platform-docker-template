# 🐾 Pet Platform – Docker Academy Template

This repository is a **template project** designed for Docker education and modular application development. It is structured as a multi-stage roadmap, progressively introducing more complex services and technologies — from simple PHP and MySQL setups to Django, React, microservices, and Kubernetes.

---

## 🚀 Purpose

The goal of this project is to:

- Teach Docker and container-based architecture step by step
- Guide developers through realistic business scenarios
- Use domain-driven modularization and scalable architecture
- Support multiple technologies and stacks (PHP, Django, React, etc.)

---

## 🧠 Business Concept

This is a **model application** for a pet services platform, including:

- 🩺 Veterinary Services
- ✂️ Grooming Services
- 🏨 Pet Hotel
- 🚶 Walker Booking
- 🐶 Animal Shelter Search
- 👤 User Authentication
- 🎨 Unified Frontend
- 📩 Notification System (Email/SMS)
- 📈 Monitoring and Metrics
- ☸️ Kubernetes Deployment

Each component is implemented as an isolated service, progressively integrated.

---

## 🧭 Folder Structure (Stages)

| Stage | Folder                          | Description                              |
|-------|----------------------------------|------------------------------------------|
| 00    | `stage-00-php/`                 | Intro: Apache + PHP static project       |
| 01    | `stage-01-php-mysql/`           | PHP + MySQL stack (CMS-style backend)    |
| 02    | `stage-02-vet-panel-django/`    | Django: Veterinary panel backend         |
| 03    | `stage-03-grooming-cms/`        | WordPress or Moodle-based grooming site  |
| 04    | `stage-04-hotel-backend/`       | Pet hotel backend API                    |
| 05    | `stage-05-walker-service/`      | Pet walker scheduling microservice       |
| 06    | `stage-06-shelter-search/`      | Shelter geolocation and search           |
| 07    | `stage-07-user-auth/`           | Authentication & authorization module    |
| 08    | `stage-08-frontend-react/`      | Web frontend in React                    |
| 09    | `stage-09-email-service/`       | Email notification microservice          |
| 10    | `stage-10-monitoring/`          | Prometheus/Grafana, logging              |
| 11    | `stage-11-k8s-deploy/`          | Helm + Kubernetes deployment configs     |

---

## 📦 How to Use This Template

1. Click **"Use this template"** at the top of this page
2. Choose a name and visibility (public/private)
3. Clone your newly created repo:
   ```bash
   git clone https://github.com/your-name/your-repo.git
   cd your-repo

---

## 🛠 Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Docker Compose](https://docs.docker.com/compose/)
- (Optional) [GPG setup for signed commits](https://docs.github.com/en/authentication/managing-commit-signature-verification)
- (Optional) [Visual Studio Code](https://code.visualstudio.com/) with Docker and Dev Containers extensions

---

## 📚 Documentation

See [`docs/architecture.md`](docs/architecture.md) for:

- Overall system architecture
- Stage-by-stage integration strategy
- Guidelines for contribution
- Design patterns and service boundaries

---

## 🤝 Contribution

We welcome contributions in all forms:

- Improving Dockerfiles and configurations
- Adding or documenting new technology stages
- Writing tutorials, READMEs, and examples
- Creating tests and GitHub Actions workflows

To contribute:
1. Fork the repository
2. Create a branch from `main`
3. Submit a pull request with clear description

---

## 📄 License

This project is licensed under the **Apache License 2.0**.
All derivative works (e.g., academies based on this template) **must retain this license** and the original author attribution.
See [`LICENSE`](LICENSE) and [`NOTICE`](NOTICE) for details.

---

Made with ❤️ by [Programista1024.pl](https://programista1024.pl)
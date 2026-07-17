<div align="center">

# Serhat Güler

**Full Stack Software Engineer | Web, Backend & DevOps**

[![Portfolio](https://img.shields.io/badge/Portfolio-serhat.gueler.dev-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://serhat.gueler.dev/portfolio/)
[![Email](https://img.shields.io/badge/Email-serhat@gueler.dev-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:serhat@gueler.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/serhat-gueler/)

</div>

---

> Software engineer, professional since 2022. At two companies I designed, built and operated internal systems end to end **as the sole developer** - including a platform in production use for 50+ employees: from requirements and architecture to deployment and Linux server operations. Core stack: Laravel/PHP, React/TypeScript, Java/Spring Boot and Flutter, backed by Docker/CI-CD infrastructure. In public side projects I go deeper: C++/Qt systems programming, Kubernetes, and applied computer vision (YOLOv8, OCR).

## 💻 Tech Stack

### Production experience (from employment)

![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Project experience (public repos below)

![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

---

## 🚀 Featured Engineering Projects

### [TaskManager - SaaS Task Management Platform](https://github.com/sero583/taskmanager) · **[Live demo](https://taskmanager.gueler.dev)**
Production-grade full-stack SaaS, publicly deployed as a live demo: real-time sync via WebSockets (Laravel Reverb), MFA (WebAuthn passkeys, TOTP), SSO (Google/Microsoft/GitHub), RBAC, and a dual hybrid API (REST/OpenAPI + GraphQL).

* **Infrastructure:** runs via Docker Compose on my own Linux server; deployment-ready Kubernetes setup (18 manifests, HPA auto-scaling), tested in a cluster. PostgreSQL, MongoDB, Redis and RabbitMQ.
* **Quality:** CI/CD via GitHub Actions, k6 load testing (500 concurrent users), 120+ Pest tests with Codecov integration, PHPStan level 8.
> `Kubernetes` `Docker` `Laravel` `Vue.js` `TypeScript` `RabbitMQ` `Redis` `Meilisearch`

### [CHIP-8 Emulator - Hardware-Level Emulation](https://github.com/sero583/chip8-emulator) · *completed*
Classic COSMAC VIP emulator built from scratch in modern C++ with strict architectural separation of CPU, memory and UI. Raw opcode execution, rendering via a Qt 6 desktop GUI, automated CMake/Catch2 test infrastructure.
> `C++20` `Qt 6` `CMake` `Catch2` `GitHub Actions`

### [CrossPacket - Polyglot Code Generator](https://github.com/sero583/crosspacket) · *open source*
Cross-platform generator creating type-safe serialization classes for **9 programming languages** from a single JSON schema. Built for latency-critical WebSocket communication with dual serialization (JSON + MessagePack), deep map conversion and regex validation; CI tests all 9 languages in parallel at 95%+ coverage.
> `Python` `C++` `Rust` `Java` `Go` `Dart` `C#` `MessagePack`

### [RDR2 Object Detection - Applied ML Pipeline](https://github.com/sero583/RDR2-Object-Detection) · *open source*
Real-time computer vision at 60 FPS with a custom-trained YOLOv8 model: an end-to-end ML pipeline from Roboflow data annotation to ONNX inference with GPU acceleration.
> `Python` `YOLOv8` `PyTorch` `OpenCV` `ONNX`

### [ReceiptSnapper - AI-Powered Finance App](https://serhat.gueler.dev/portfolio) · *in active development*
Cross-platform personal finance and receipt management app: multi-engine OCR pipeline (Google ML Kit, Tesseract) with YOLOv8 receipt boundary detection via TensorFlow Lite, hardware-backed encryption (Android Keystore/iOS Keychain) with PBKDF2 key derivation, and German-compliant bookkeeping exports (GoBD/DATEV).
> `Flutter` `Dart` `TensorFlow Lite` `YOLOv8` `SQLite (Drift)` `Computer Vision`

---

## 🌍 Upstream Open Source Contributions

* **[flutter/flutter#182224](https://github.com/flutter/flutter/pull/182224)** - merged PR in the **Impeller rendering engine**: bilinear filtering for non-uniformly scaled text (C++).
* **Work in progress:** an **Impeller Vulkan desktop backend** for Windows (DirectComposition) and Linux (GTK) - a [series of open PRs](https://github.com/flutter/flutter/pulls?q=is%3Apr+author%3Asero583+is%3Aopen) split into reviewable pieces, with an authored design document (its flutter.dev redirect is merged).
* **[CloudburstMC](https://github.com/pulls?q=is%3Apr+author%3Asero583+is%3Amerged+org%3ACloudburstMC)** (Nukkit, Cloudburst, ProxyPass) - multiple merged PRs in the Java Minecraft-server ecosystem: bug fixes, API improvements and features.

---

## 💼 Professional Experience

**Full Stack Developer & IT Administrator (part-time)** | *Sunshine Dienstleistungen GmbH*
*Sep 2024 – Present*

* Sole developer of the company's internal management platform (Laravel, Flutter), digitalizing workflows for 50+ employees, from requirements analysis with management to production operations.
* Built the DevOps pipeline: CI/CD (GitHub Actions), Docker container deployments, Linux server administration.
* Implemented RBAC and Microsoft 365 integration (Graph API); responsible for domains, e-mail and backups.

**Full Stack Developer (working student)** | *ERPstudio GmbH*
*Nov 2022 – Aug 2024*

* Sole developer of a modular B2B commerce SaaS platform from concept to near-production; all architecture and technology decisions in my own responsibility.
* Designed the backend (Laravel/PHP, MySQL), built RESTful APIs, and integrated payment providers (Stripe, PayPal) into React/Redux interfaces.
* Configured multi-tenant server infrastructure (Apache vHosts).

**Full Stack Developer (full-time working student)** | *Accenture*
*Feb 2022 – Mar 2022*

* Delivered RESTful web services within a microservices architecture using Java and Spring Boot.
* Built multithreaded tools for parsing, processing and format conversion of large JSON datasets; unit testing with JUnit/Mockito.
* Left with a top-graded reference ("sehr gut") including an explicit invitation to re-apply.

---

## 🎓 Education

**B.Sc. Computer Science program - 150 of 210 ECTS completed**
*Hof University of Applied Sciences, Germany (Oct 2020 – Sep 2025)*

Completed the full theory core (software engineering, distributed systems, databases, system architecture), then chose to focus fully on hands-on software engineering.

---
<div align="center">
  <i>Syntax is just a tool. Architecture is the foundation. Let's build reliable systems.</i>
</div>

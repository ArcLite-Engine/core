# ArcLite Core

<p align="center">
  <strong>ArcLite Core</strong><br>
  The lightweight PHP engine powering Modura and custom framework development.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.1%2B-blue" alt="PHP Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Status-Active%20Development-orange" alt="Status">
  <img src="https://img.shields.io/badge/Version-0.1.0--dev-lightgrey" alt="Version">
</p>

---

## 🧠 What is ArcLite?

ArcLite Core is a lightweight, modular PHP runtime engine designed to power the **Modura** framework while remaining flexible enough for developers to build their own custom frameworks.

It provides the foundational building blocks required to construct modern PHP frameworks:

- HTTP Kernel
- Routing System
- Middleware Pipeline
- Dependency Injection Container
- Event Dispatcher (planned)
- PSR Compatibility (planned)

ArcLite focuses on **stability, modularity, and extensibility**.

---

## ✨ Philosophy

ArcLite is **not** a full-stack framework.

It is a **framework engine**.

It handles *how* an application runs — not *what* it includes.

This architectural separation allows:

- Modura to evolve independently
- Other developers to build their own frameworks
- Stable core architecture across versions
- Reduced upgrade friction

---

## 🚀 Why ArcLite?

Traditional frameworks tightly couple core runtime and features.

ArcLite separates them.

| ArcLite Core | Framework Layer (e.g., Modura) |
|-------------|---------------------------------|
| Handles HTTP lifecycle | Defines structure & conventions |
| Manages routing & middleware | Adds components (auth, db, views) |
| Provides DI container | Adds service providers |
| Minimal & stable | Feature-rich & extensible |

This design enables long-term stability at the engine level.

---

## 📦 Installation (Coming Soon)

```bash
composer require arclite/core

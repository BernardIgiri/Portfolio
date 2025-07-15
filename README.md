# Bernard Igiri's GitHub Portfolio

Welcome to my project portfolio. I’m a full-stack software engineer with over two decades of software development experience, building cutting-edge systems; from high-performance web apps and geospatial tools to secure platforms and developer-friendly frameworks. My work spans Rust, systems programming, web development, cloud infrastructure, and cross-language interoperability. For a detailed bio please visit my blog's about me page at: https://yequalscode.com/about-the-author

Below you'll find selected personal and professional projects, grouped by technology with descriptions and links.

---

## 📊 Tech Stack Index

| Language/Tech        | Projects                                                                 |
|----------------------|--------------------------------------------------------------------------|
| 🦀 **Rust**          | [Deferred Cell](#deferred-cell), [KDE Activity Script Selector](#kde-activity-script-selector) [Text Adventure Game](#text-adventure-game), [Text Edit 2](#text-edit-2), [Zellij Layout Generator](#zellij-layout-generator) |
| 🐹 **Go**            | [cfgcrypt](#cfgcrypt), [Restful User Auth](#restful-user-auth)                             |
| 🎮 **Godot (GDScript)** | [Godot Action RPG](#godot-action-rpg)                                                    |
| ⚛️ **JavaScript/React** | [Learn React JS](#learn-react-js), [Rich Text Editor](#rich-text-editor)                     |
| 🐍 **Python**         | [Python To Java AES Encrypt Decrypt](#python-to-java-aes-encrypt-decrypt), [SynoSnap](#synosnap), [Robot Car Navigation](#robot-car-navigation) |
| ☕ **Java**            | [Raffle Ticket App](#raffle-ticket-app), [Python To Java AES Encrypt Decrypt](#python-to-java-aes-encryptdecrypt) |
| 🧵 **C++**             | [3D Graphics Engine](#3d-graphics-engine), [Robot Car Navigation](#robot-car-navigation)    |
| 🧐 **AI / Vision**       | [Pangolin](#pangolin)                                                                     |

---

## 🦀 Rust

### Deferred Cell
[top](#bernard-igiris-github-portfolio)

Write-once, late-initialized cyclic graphs in Rust.  
🔧 [Repo](https://github.com/BernardIgiri/deferred-cell)

**Tech**: Rust, `Rc`, `OnceCell`, `Weak`, `thiserror`

**Features**:
- Safe write-once initialization for cyclic graphs
- Ergonomic API for deferred loading
- Custom error types for clean usage

---

### KDE Activity Script Selector

[top](https://chatgpt.com/g/g-p-6864422fdefc8191ac3a3ec9ffa48d9f-github-portfolio/c/6876bf76-6cf4-8004-9ea5-cd6f1174768b#bernard-igiris-github-portfolio)

Relm4-based desktop GUI tool for assigning shell scripts to KDE Activity lifecycle events.
 🔧 [Repo](https://github.com/BernardIgiri/kas-selector)

**Tech**: Rust, GTK4, Relm4, KDE, Fluent

**Features**:

- Assign `.sh` scripts to `started`, `activated`, `deactivated`, and `stopped` events
- Desktop GUI
- i18n support for multiple language translations
- Designed for KDE Plasma 6

### Text Adventure Game
[top](#bernard-igiris-github-portfolio)

A Rust-powered engine for interactive text-based adventures.  
🔧 [Repo](https://github.com/BernardIgiri/text-adventure-game)

**Tech**: Rust, INI file engine, CLI, cross-platform

**Features**:
- Game defined entirely via `.ini` files
- Entity schema enabling dynamic world building
- Precompiled binaries for all major platforms

---

### Text Edit 2
[top](#bernard-igiris-github-portfolio)

Simple desktop text editor built using GTK4 and Rust.  
🔧 [Repo](https://github.com/BernardIgiri/TextEdit2)

**Tech**: Rust, GTK4-rs

**Features**:
- Edit, open, and save files
- Cross-platform GTK UI
- Minimal boilerplate GUI project

---

### Zellij Layout Generator
[top](#bernard-igiris-github-portfolio)

CLI tool to generate custom Zellij layout files from TOML configs.  
🔧 [Repo](https://github.com/BernardIgiri/zellij-layout-generator)

**Tech**: Rust, TOML, KDL, CLI

**Features**:
- Define reusable terminal workflows
- Generate `.kdl` files for Zellij
- Broadcast support, dynamic panes

---

## 🐹 Go

### cfgcrypt
[top](#bernard-igiris-github-portfolio)

AES encryption utility for config files.  
🔧 [Repo](https://github.com/BernardIgiri/cfgcrypt)

**Tech**: Go, AES-CBC, Base64, CLI

**Features**:
- Wrap and encrypt text using `#{{...}}#`
- Outputs encrypted config + key file
- Fully CLI-controlled

---

### Restful User Auth
[top](#bernard-igiris-github-portfolio)

RESTful user authentication microservice.  
🔧 [Repo](https://github.com/BernardIgiri/restfulUserAuth)

**Tech**: Go, Docker, JWT, Microservices

**Features**:
- Secure signup/login APIs
- Token-based auth, password hashing
- Deployable via Docker Compose

---

## 🎮 Godot (GDScript)

### Godot Action RPG
[top](#bernard-igiris-github-portfolio)

Action RPG game based on HeartBeast’s tutorial.  
🔧 [Repo](https://github.com/BernardIgiri/GodotActionRPGTutorial)

**Tech**: Godot, GDScript

**Features**:
- Top-down player & enemy AI
- Health, combat, animation
- Cleanly structured scenes

---

## ⚛️ JavaScript / Web

### Learn React JS
[top](#bernard-igiris-github-portfolio)

React and Redux learning playground.  
🔧 [Repo](https://github.com/BernardIgiri/learnReactJS)

**Tech**: JavaScript, React, Redux

**Features**:
- Tic-Tac-Toe in vanilla React
- Redux state integration examples
- From official tutorials & Medium articles

---

### Rich Text Editor
[top](#bernard-igiris-github-portfolio)

Basic in-browser WYSIWYG editor.  
🔧 [Repo](https://github.com/BernardIgiri/archive-RichTextEditor)

**Tech**: JavaScript, HTML, CSS

**Features**:
- Bold/italic/underline/etc
- Content-editable region demo
- Lightweight, no dependencies

---

## 🐍 Python

### Python to Java AES Encrypt/Decrypt
[top](#bernard-igiris-github-portfolio)

Cross-language encryption demo.  
🔧 [Repo](https://github.com/BernardIgiri/PythonToJavaAESEncryptDecrypt)

**Tech**: Python, Java, AES-CBC

**Features**:
- Python encrypts, Java decrypts
- Base64 encoding, IV handling
- Shows cryptographic compatibility

---

### SynoSnap
[top](#bernard-igiris-github-portfolio)

Snapshot-style backup script for Synology.  
🔧 [Repo](https://github.com/BernardIgiri/SynoSnap)

**Tech**: Python, rsync

**Features**:
- Hardlinked snapshots (hourly, daily, etc.)
- Dry-run mode, minimal dependencies
- Cron-ready

---

## 🤖 Robotics & Embedded

### Robot Car Navigation
[top](#bernard-igiris-github-portfolio)

Full-stack robot control and obstacle avoidance.  
🔧 [Repo](https://github.com/BernardIgiri/archive-RobotCarNavigation)

**Tech**: C++, Python, PHP, HTML/CSS/JS

**Features**:
- Collision avoidance
- Pathfinding algorithms
- Web UI and low-level C++ integration

---

## ☕ Java

### Raffle Ticket App
[top](#bernard-igiris-github-portfolio)

Mobile raffle app with full backend.  
🔧 [Repo](https://github.com/BernardIgiri/archive-RaffleTicketApp)

**Tech**: Java (Android), PHP, MySQL

**Features**:
- REST API + Android client
- PayPal payment integration
- Static website frontend

---

## 🧵 C++ / Graphics

### 3D Graphics Engine
[top](#bernard-igiris-github-portfolio)
Cross-platform 3D renderer in C++ & OpenGL.  
🔧 [Repo](https://github.com/BernardIgiri/archive-CrossPlatform3dGraphicsEngine)

**Tech**: C++, OpenGL

**Features**:
- Scene rendering, camera, lighting
- Shader loading
- Multiplatform build targets

---

## 🧐 AI / Computer Vision

### Pangolin
[top](#bernard-igiris-github-portfolio)

Face recognition login demo.  
🔧 [Repo](https://github.com/BernardIgiri/pangolin)

**Tech**: Go, PHP, facial recognition

**Features**:
- Login via face recognition
- Webcam-based user match
- Demo interface + detection

---

Thanks for visiting! Feel free to reach out via [GitHub](https://github.com/BernardIgiri) or [LinkedIn](https://www.linkedin.com/in/bernardigiri).


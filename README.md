# 🚀 Odysseus AI Control Center

A Windows-based control center designed to simplify the deployment, startup, monitoring, maintenance, and basic system management of local Odysseus environments.

Odysseus AI Control Center centralizes core tasks such as Docker and Ollama service control, environment checks, system monitoring, and diagnostics into a single interface.

---

# 🟢 STABLE RELEASE (MAIN BRANCH)

This repository contains the **latest stable version (v1.4.0 - Mnemosyne)** of Odysseus AI Control Center.

This is the **recommended version for installation and daily use**.

Mnemosyne builds upon the stability-focused philosophy introduced by Athena while simplifying the architecture even further.

It has been tested primarily on the developer’s personal system and represents the current stable feature set.

⚠️ Notes:

* This project is currently in a maintenance-only state
* No active feature development is planned unless issues are reported
* Updates will be released only for bug fixes or compatibility problems
* Performance and behavior may vary across different systems
* Tested primarily on the developer's personal system
* This release represents the current stable baseline version

---

# 📸 Screenshots

### 🧠 Environment Detection & Validation

<img src="https://github.com/user-attachments/assets/7141561e-2466-4f77-a24c-aec99ddfe241" alt="Initialization" />

Automatically verifies Docker Desktop, Docker CLI, Ollama, WSL, and curl availability during startup.

---

### 🖥️ Main Dashboard

<img src="https://github.com/user-attachments/assets/6e238f68-fea8-4ee5-8e72-d948236cab3b" alt="Main Dashboard" />

View system status, installed models, logs, and service controls in one place.

---

### 🚀 Starting AI Services

<img src="https://github.com/user-attachments/assets/59798115-7a1c-4ddf-b25c-4d057f9e6807" alt="Starting AI Services" />

Starts Docker, Ollama, and Odysseus with automated readiness checks and startup validation.

---

### 🛑 Stopping AI Services

<img src="https://github.com/user-attachments/assets/0c143ece-bd90-4185-a76c-735143faca46" alt="Stopping AI Services" />

Stops running services safely. Some system-level components require user confirmation depending on configuration.

---

### 📦 Installed AI Models

<img src="https://github.com/user-attachments/assets/c98c2808-3597-4293-b49a-1052f101a519" alt="Installed AI Models" />

Displays locally installed Ollama models with metadata and system information.

---

### 📊 System Health Check

<img src="https://github.com/user-attachments/assets/04a0740b-4200-4f07-9f5f-af73af6a6991" alt="Health Check" />

Shows system status, storage usage, service health information, and environment diagnostics.

---

### 📜 Log Viewer

<img src="https://github.com/user-attachments/assets/3ceffc29-7591-40bd-8e61-969940cdfc62" alt="Log Viewer" />

Provides access to system and application logs for debugging and monitoring.

---

### ⚙️ Settings

<img src="https://github.com/user-attachments/assets/697f281d-3f31-4a4f-ba2a-5278c0171e3c" alt="Settings" />

Allows configuration of data paths, utility shortcuts, and basic system preferences.

---

# ✨ Features (v1.4.0 Stable)

## 🔍 Environment Checks

* Detect Docker Desktop installation and status
* Verify Docker Engine availability
* Check Ollama installation
* Check WSL availability (if enabled)
* Verify system tools (e.g., curl)
* Perform startup readiness checks
* Perform startup validation before reporting success
* Provide diagnostic output for troubleshooting

---

## 🚀 Service Management

* Start Odysseus environment from a single interface
* Auto-start Docker and Ollama when needed
* Monitor service startup status
* Validate system readiness before launching
* Startup validation before reporting success
* Restart Odysseus directly from the main menu
* Graceful shutdown controls

---

## 📊 System Monitoring

* View installed Ollama models
* Monitor storage usage
* Access logs and system status
* Startup validation diagnostics
* Basic configuration for data paths

---

## 🔧 System Utilities

* Docker status checking and basic troubleshooting guidance
* WSL detection and setup guidance
* General system health diagnostics
* Restart Odysseus workflow
* Log management and troubleshooting tools

---

# 🆕 What's New in Mnemosyne

### Added

* Startup Validation System
* Restart Odysseus menu option
* Improved startup diagnostics
* WSL shutdown during restart operations
* Clearer startup failure handling
* Improved logging visibility

### Removed

* Watchdog monitoring subsystem
* Watchdog background process
* Watchdog PID tracking
* Watchdog configuration settings
* Watchdog health display
* Automatic crash recovery automation

### Improved

* Startup reliability
* Recovery workflow
* Logging transparency
* Maintainability
* Code simplicity
* Predictable behavior

---

# 🎯 Purpose

This tool simplifies running a local Odysseus environment by combining Docker, Ollama, and system checks into a single control interface.

It reduces manual setup steps and improves usability for local AI workflows.

---

# 📋 Requirements

**Required**

* Windows 10 or Windows 11
* Docker Desktop
* Ollama
* Odysseus

**Recommended**

* WSL 2 enabled
* Administrative privileges for system operations

---

# 📚 Installation

1. Install Docker, Ollama, and Odysseus dependencies
2. Download latest stable release (v1.4.0)
3. Extract the package
4. Run `Odysseus AI Control Center.bat`
5. Follow setup instructions

---

# 📖 Installation Reference

📺 https://youtu.be/qiy-oPT8IhE

This guide was used during setup and development as a reference for installing Odysseus and required dependencies.

> Always refer to official Odysseus documentation for latest updates and configuration details.

---

# 📜 Release History

* v1.4.0 — Mnemosyne (Current Stable)
* v1.3.1 — Athena
* v1.2.0 — Icarus
* v1.0.0 — Genesis

---

## ⚠️ Disclaimer

Odysseus AI Control Center is provided **"as is" without any warranties or guarantees of any kind.**

This software:

* Has been tested primarily on the developer’s personal system
* May behave differently on other machines or system configurations
* Is currently in a **stable, maintenance-only state**
* Will only receive updates if bugs or compatibility issues are reported

Users are responsible for:

* Reviewing source code before execution
* Ensuring system compatibility
* Managing their own backups and system safety

The author is not responsible for any:

* Data loss
* System failures
* Configuration issues
* Software conflicts
* Hardware or environment problems

**Use entirely at your own risk.**

---

# 🤖 AI-Assisted Development Disclosure

This project was developed using a combination of human design and AI-assisted development tools.

* Portions of the code, logic, and documentation were generated or refined using AI systems
* All AI-generated content was reviewed and modified by the developer
* Development followed an iterative AI-assisted workflow

Estimated AI contribution: **~80–90%**

This disclosure is for transparency only and does not affect functionality or safety.

---

# 👨‍💻 Author

Created and maintained by **Yen The Programmer**

Beginner developer learning software development through experimentation, self-hosting, open-source projects, and AI-assisted workflows.

---

# 📌 License

This project is released under the MIT License.

You are free to:

* Use
* Modify
* Distribute
* Reuse in other projects

As long as attribution and license notice are included.

# Gitea on Ubuntu with Docker

This repository provides a simple guide to install and configure Gitea (a self-hosted Git platform) using Docker on Ubuntu.

---

## Prerequisites

- **Ubuntu** (with admin rights)
- **Docker** and **Docker Compose** installed

---

## Installation

1. **Create a directory**:
   ```bash
   mkdir ~/gitea
   cd ~/gitea

2. **Create docker-compose.yml**:
   ```bash
   nano docker-compose.yml
   ```

3. **Start container**:
   ```bash
   docker compose up -d
   ```

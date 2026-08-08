# Softy Pinko Docker Project

This repository contains a series of tasks focused on containerizing a web application using **Docker** and **Docker Compose**, setting up a multi-container architecture with **Nginx**, **Flask (Python)**, and implementing a **Reverse Proxy** and **Load Balancer**.

## Tasks Overview

* **Task 0 & 1:** Setting up the basic environment and Dockerfile foundations.
* **Task 2 (Static Server):** Created a static content server using Nginx to serve the front-end files.
* **Task 3 (API Server):** Created a dynamic API server using Python and Flask running in its own container.
* **Task 4 (Docker Compose):** Managed both front-end and back-end containers together using `docker-compose.yml`.
* **Task 5 (Proxy Server):** Added an Nginx reverse proxy in front of the application to route requests (`/` to front-end, `/api` to back-end) and closed direct external access to individual containers.
* **Task 6 (Horizontal Scaling):** Scaled the back-end API server horizontally using Docker Compose scaling (`--scale back-end=2`) to balance traffic via Nginx's Round-Robin algorithm.

##  Technologies Used
* **Docker & Docker Compose**
* **Nginx** (Static hosting, Reverse Proxy, Load Balancing)
* **Python / Flask** (Backend API)
* **HTML / JavaScript (jQuery)** (Frontend)

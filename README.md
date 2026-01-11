# Section 8 – VProfile Multi-Tier DevOps Project

This section contains a complete multi-tier Java application deployment using DevOps practices and automation.

## 🏗 Architecture

The project follows a 5-tier architecture:

- Nginx (Web Server / Reverse Proxy)
- Tomcat (Application Server)
- MariaDB (Database)
- Memcached (Caching)
- RabbitMQ (Message Broker)

Each component runs on a separate VM using Vagrant.

## ⚙ Tools Used

- Vagrant
- VirtualBox
- Linux (Ubuntu & CentOS Stream)
- Nginx
- Apache Tomcat
- MariaDB
- Memcached
- RabbitMQ
- Maven
- Git

## 📦 Application

- Java Spring MVC application (VProfile)
- WAR deployment on Tomcat
- Database and message queue integration

## 🎯 Objectives

- Understand multi-tier architecture
- Practice Infrastructure as Code
- Configure inter-service communication
- Reverse proxy using Nginx
- Manual and automated deployments

## 📁 Folder Structure

- architecture/ → diagrams and design explanation
- vagrant/ → Vagrantfile for multi-VM setup
- provisioning/ → shell scripts for service setup
- configs/ → config files (nginx, app configs)
- screenshots/ → output and verification images

## ✅ Outcome

Successfully deployed and accessed full-stack application using Nginx reverse proxy and multiple backend services.


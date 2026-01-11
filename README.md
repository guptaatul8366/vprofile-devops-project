# Section 8 – VProfile Multi-Tier DevOps Project

# 🚀 VProfile Multi-Tier DevOps Project

This project demonstrates deployment of a full-stack Java web application using a multi-tier DevOps architecture.

The goal is to simulate real production environments using separate servers for each service and configure communication between them.

---

## 🏗 Architecture Overview

The application is deployed using **5 different virtual machines**:

| VM Name | Role |
|--------|--------|
| web01  | Nginx Reverse Proxy |
| app01  | Apache Tomcat (Java App) |
| db01   | MariaDB Database |
| mc01   | Memcached Cache |
| rmq01  | RabbitMQ Message Broker |

### 🔁 Request Flow

Client → Nginx → Tomcat → Database / Cache / MQ

---

## ⚙ Tools & Technologies

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

---

## 📦 Application

- Java Spring MVC Application
- WAR built using Maven
- Deployed as ROOT.war on Tomcat

---

## ⚡ Setup Summary

### 1. Infrastructure
- Multi-VM Vagrantfile
- Private IP networking
- Hostname resolution using hostmanager plugin

### 2. Database Server (db01)
- Install MariaDB
- Create database & user
- Import database backup

### 3. Cache Server (mc01)
- Install Memcached
- Bind service to network
- Open firewall ports

### 4. Message Queue (rmq01)
- Install RabbitMQ
- Create admin user
- Enable remote connections

### 5. Application Server (app01)
- Install Java & Tomcat
- Install Maven
- Build WAR file
- Deploy to Tomcat webapps

### 6. Web Server (web01)
- Install Nginx
- Configure reverse proxy
- Forward traffic to Tomcat

---

## 📁 Repository Structure

# 🚀 VProfile Multi-Tier DevOps Project

This project demonstrates deployment of a full-stack Java web application using a multi-tier DevOps architecture.

The goal is to simulate real production environments using separate servers for each service and configure communication between them.

---

## 🏗 Architecture Overview

The application is deployed using **5 different virtual machines**:

| VM Name | Role |
|--------|--------|
| web01  | Nginx Reverse Proxy |
| app01  | Apache Tomcat (Java App) |
| db01   | MariaDB Database |
| mc01   | Memcached Cache |
| rmq01  | RabbitMQ Message Broker |

### 🔁 Request Flow

Client → Nginx → Tomcat → Database / Cache / MQ

---

## ⚙ Tools & Technologies

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

---

## 📦 Application

- Java Spring MVC Application
- WAR built using Maven
- Deployed as ROOT.war on Tomcat

---

## ⚡ Setup Summary

### 1. Infrastructure
- Multi-VM Vagrantfile
- Private IP networking
- Hostname resolution using hostmanager plugin

### 2. Database Server (db01)
- Install MariaDB
- Create database & user
- Import database backup

### 3. Cache Server (mc01)
- Install Memcached
- Bind service to network
- Open firewall ports

### 4. Message Queue (rmq01)
- Install RabbitMQ
- Create admin user
- Enable remote connections

### 5. Application Server (app01)
- Install Java & Tomcat
- Install Maven
- Build WAR file
- Deploy to Tomcat webapps

### 6. Web Server (web01)
- Install Nginx
- Configure reverse proxy
- Forward traffic to Tomcat

---

## 📁 Repository Structure

# 🚀 VProfile Multi-Tier DevOps Project

This project demonstrates deployment of a full-stack Java web application using a multi-tier DevOps architecture.

The goal is to simulate real production environments using separate servers for each service and configure communication between them.

---

## 🏗 Architecture Overview

The application is deployed using **5 different virtual machines**:

| VM Name | Role |
|--------|--------|
| web01  | Nginx Reverse Proxy |
| app01  | Apache Tomcat (Java App) |
| db01   | MariaDB Database |
| mc01   | Memcached Cache |
| rmq01  | RabbitMQ Message Broker |

### 🔁 Request Flow

Client → Nginx → Tomcat → Database / Cache / MQ

---

## ⚙ Tools & Technologies

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

---

## 📦 Application

- Java Spring MVC Application
- WAR built using Maven
- Deployed as ROOT.war on Tomcat

---

## ⚡ Setup Summary

### 1. Infrastructure
- Multi-VM Vagrantfile
- Private IP networking
- Hostname resolution using hostmanager plugin

### 2. Database Server (db01)
- Install MariaDB
- Create database & user
- Import database backup

### 3. Cache Server (mc01)
- Install Memcached
- Bind service to network
- Open firewall ports

### 4. Message Queue (rmq01)
- Install RabbitMQ
- Create admin user
- Enable remote connections

### 5. Application Server (app01)
- Install Java & Tomcat
- Install Maven
- Build WAR file
- Deploy to Tomcat webapps

### 6. Web Server (web01)
- Install Nginx
- Configure reverse proxy
- Forward traffic to Tomcat

---

## 📁 Repository Structure

vprofile-devops-project/
├── architecture/
├── vagrant/
├── provisioning/
├── configs/
└── screenshots/


---

## 🎯 What I Learned

- Multi-tier architecture design
- Infrastructure as Code with Vagrant
- Linux service configuration
- Reverse proxy using Nginx
- Java application deployment
- Inter-service communication
- Troubleshooting real server issues

---

## 📌 Future Improvements

- Full automation using provisioning scripts
- CI/CD pipeline using Jenkins
- Docker containerization
- Kubernetes deployment

---

## 🙋 Author

**Atul Gupta**  
Aspiring DevOps Engineer  
GitHub: https://github.com/guptaatul8366


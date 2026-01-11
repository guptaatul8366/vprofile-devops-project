# VProfile Architecture

## Components

1. web01 – Nginx Reverse Proxy
2. app01 – Tomcat Application Server
3. db01 – MariaDB Database Server
4. mc01 – Memcached Cache Server
5. rmq01 – RabbitMQ Message Broker

## Communication Flow

Client → Nginx → Tomcat → Database / Cache / MQ

## Why Separate VMs?

- Simulates real production architecture
- Easier to scale and troubleshoot
- Each service isolated

## Networking

All VMs are connected using private network IPs via Vagrant.
Hostname resolution is done using hostmanager plugin.


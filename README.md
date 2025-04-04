## Manual Deployment with Vagrant

This repository contains a **manual deployment** setup using **Vagrant** to provision multiple VMs for a web application.

### 📌 Vagrant Machines:
- `db01` → Database server (CentOS)
- `mc01` → Memcached server (CentOS)
- `rmq01` → RabbitMQ messaging service (CentOS)
- `app01` → Application server running Tomcat (CentOS)
- `web01` → Web server with Nginx (Ubuntu)

### 🚀 How to Use:

1. **Install Vagrant & VirtualBox**  
   - Download and install [Vagrant](https://www.vagrantup.com/downloads)  
   - Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)  

2. **Start the VMs**  

   ```bash
   cd vagrant
   vagrant up


https://github.com/Manishp919/webapp-setup/blob/automated-setup/Picture%20for%20Project-2.png?raw=true
Project Overview : 
This project automates the deployment of a multi-tier web application using Vagrant and shell scripts. It eliminates the manual setup process by provisioning virtual machines and configuring services automatically.  

Key Features : 
- Automated provisioning with Vagrantfile to set up required VMs.  
- Shell scripts for installing and configuring Nginx, Tomcat, PostgreSQL, RabbitMQ, and Memcached.  
- Ensures consistent and repeatable deployment across environments.  
- Reduces setup time compared to manual configuration.  
- Minimizes human errors caused by manual processes.  

Setup Instructions: 
1. Install Vagrant and VirtualBox on your system.  
2. Clone the repository and switch to the automated-setup branch.  
3. Run `vagrant up` to provision the virtual machines and configure services automatically.  
4. Once provisioning is complete, access each VM via SSH if needed.  
5. Verify service availability and ensure the web application is running.  
6. Access the application through the Nginx server in a web browser.  

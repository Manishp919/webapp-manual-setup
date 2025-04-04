1️⃣ **Install Prerequisites** → Install **Vagrant** and **VirtualBox**.  

2️⃣ **Clone Repository** →  
   ```bash
   git clone https://github.com/yourusername/webapp-manual-setup.git  
   cd webapp-manual-setup  
   ```  

3️⃣ **Start VMs** →  
   ```bash
   vagrant up  
   ```  

4️⃣ **SSH into VMs** →  
   ```bash
   vagrant ssh web01  # Nginx  
   vagrant ssh app01  # Tomcat  
   vagrant ssh db01   # PostgreSQL  
   ```  

5️⃣ **Manually Install & Configure Services** → Follow `setup-guide.md`.  

6️⃣ **Verify Setup** → Check running services on each VM.  

7️⃣ **Access Application** → Open browser and navigate to **http://192.168.56.11** (Nginx).  

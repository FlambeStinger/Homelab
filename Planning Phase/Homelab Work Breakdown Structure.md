**1.0 Project Initiation & Planning**

* 1.1 Finalize Project Scope  
* 1.2 Draft Work Breakdown Structure  
* 1.3 Define Project Timeline & Milestones  
* 1.4 Secure Project Funding ($150 budget)  
* 1.5 Create a Final Bill of Materials (BoM)

---

**2.0 Equipment & Software Procurement**

* 2.1 Hardware Acquisition  
  * 2.1.1 Research OpenWrt compatibility for Google Wifi & TP-Link APs  
  * 2.1.2 Procure new OpenWrt-compatible router (if needed)  
  * 2.1.3 Purchase any necessary cabling or tools  
  * 2.1.4 Conduct a weight test with all equipment in the backpack  
* 2.2 Software Acquisition  
  * 2.2.1 Download OpenWrt installation files  
  * 2.2.2 Download VMware/VirtualBox installation files  
  * 2.2.3 Download Docker & Kubernetes installers  
  * 2.2.4 Download Ansible and other necessary tools

---

**3.0 Core Infrastructure Build-Out**

* 3.1 Router Configuration  
  * 3.1.1 Install OpenWrt firmware on the router  
  * 3.1.2 Configure basic network settings  
  * 3.1.3 Establish a separate subnet and VLAN for the lab network  
  * 3.1.4 Configure DHCP and DNS services  
* 3.2 Host Machine Configuration (Lenovo Laptop)  
  * 3.2.1 Install operating system on the laptop  
  * 3.2.2 Install VMware/VirtualBox  
  * 3.2.3 Install Docker  
* 3.3 AP & Network Device Configuration  
  * 3.3.1 Configure Google Wifi and TP-Link APs (if compatible) to extend the lab network  
  * 3.3.2 Disable unused ports and radios on all APs  
  * 3.3.3 Connect cable dependent devices with CAT 5e/6a cabling

---

**4.0 Service & Security Deployment**

* 4.1 Network Security Implementation  
  * 4.1.1 Deploy FreeRadius container on the Lenovo Laptop  
  * 4.1.2 Configure 802.1X wireless authentication  
  * 4.1.3 Configure firewall rules on the OpenWrt router  
* 4.2 Automation & Telemetry  
  * 4.2.1 Install and configure Ansible on the HP management laptop  
  * 4.2.2 Write and test Ansible playbooks for container deployment  
  * 4.2.3 Deploy Splunk container on the Lenovo laptop  
  * 4.2.4 Configure Splunk to receive telemetry from network devices  
* 4.3 End Host Configuration (HP Envy Laptop)  
  * 4.3.1  Install and configure management tools (Ansible, Splunk forwarder, etc.)  
  * 4.3.2 Install remote access tools (i.e. SSH)  

---

**5.0 Testing & Documentation**

* 5.1 Functionality Testing  
  * 5.1.1 Test device communication within the lab network  
  * 5.1.2 Test internet access from lab devices  
  * 5.1.3 Time the setup and takedown process  
* 5.2 Documentation & Maintenance  
  * 5.2.1 Draft network topologies and configurations  
  * 5.2.2 Write troubleshooting guide  
  * 5.2.3 Develop maintenance plan and scripts

---

**6.0 Project Closure**

* 6.1 Final Review and Acceptance  
* 6.2 Archive all project documentation


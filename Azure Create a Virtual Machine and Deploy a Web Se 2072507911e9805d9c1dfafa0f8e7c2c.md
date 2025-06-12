# Azure: Create a Virtual Machine and Deploy a Web Server

Following the https://www.coursera.org/projects/azure-create-a-virtual-machine-and-deploy-a-web-server finish this and get certified.

- Instruction
    
    Now we will build (project goals). We will accomplish it in by completing each task in the project:
    
    - Create a Resource Group
        
        [https://portal.azure.com/](https://portal.azure.com/)
        
        ![image.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/image.png)
        
        ![image.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/image%201.png)
        
    - Create a Virtual Network and a subnet
        
        A. Create Virtual Network
        
        ![image.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/image%202.png)
        
        ![Create_Virtual_Network00_2025-06-04 15-54-43.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network00_2025-06-04_15-54-43.png)
        
        B. Configure Virtual network address space 
        
        ![Create_Virtual_Network01_2025-06-04 15-58-25.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network01_2025-06-04_15-58-25.png)
        
        C. Review before create
        
        ![Create_Virtual_Network03_2025-06-04 16-02-00.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network03_2025-06-04_16-02-00.png)
        
        D. Virtual Network resource complete
        
        ![Create_Virtual_Network04_2025-06-04 16-03-14.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network04_2025-06-04_16-03-14.png)
        
        E. Back to Virtual Network Settings check the address space tab
        
        ![Create_Virtual_Network05_2025-06-04 16-04-56.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network05_2025-06-04_16-04-56.png)
        
        F . Set the subnet 
        
        ![Create_Virtual_Network07_2025-06-04 16-05-42.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Create_Virtual_Network07_2025-06-04_16-05-42.png)
        
        G. Top level view thru the Topology regarding the Virtual Network (Completed this section)
        
    - Protect a subnet using a Network Security Group
        
        A. Head back to Resource Group
        
        ![Network Security Group00_2025-06-04 16-08-29.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group00_2025-06-04_16-08-29.png)
        
        B. Search the market for Network Security Group
        
        ![Network Security Group01_2025-06-04 16-09-54.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group01_2025-06-04_16-09-54.png)
        
        C. Install it or rather create it to populate your virtual network 
        
        ![Network Security Group02_2025-06-04 16-10-12.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group02_2025-06-04_16-10-12.png)
        
        D. Name the network security group instance details. Review and create.
        
        ![Network Security Group03_2025-06-04 16-11-35.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group03_2025-06-04_16-11-35.png)
        
        E. Now you have overview of your NSG(network security group)
        
        ![Network Security Group04_2025-06-04 16-12-54.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group04_2025-06-04_16-12-54.png)
        
        F. Head back to your main resource group and you will find two instances populate it
        
        ![Network Security Group05_2025-06-04 16-13-50.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group05_2025-06-04_16-13-50.png)
        
        G.  Click to enter your virtual network properties at the subnet tab
        
        ![Network Security Group06_2025-06-04 16-14-34.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group06_2025-06-04_16-14-34.png)
        
        H. Attach the network security group to the subnet
        
        ![Network Security Group07_2025-06-04 16-15-04.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group07_2025-06-04_16-15-04.png)
        
        I. This section is complete and this is the overview from topology tab
        
        ![Network Security Group08_2025-06-04 16-16-05.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Network_Security_Group08_2025-06-04_16-16-05.png)
        
    - Deploy Bastion to connect to a Virtual Machine
        
        A. navigate to virtual network tab
        
        ![Deploy Bastion00_2025-06-04 16-18-14.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion00_2025-06-04_16-18-14.png)
        
        B. Add a new subnet with detail as Azure Bastion with the following setting in the picture
        
        ![Deploy Bastion01_2025-06-04 16-21-26.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion01_2025-06-04_16-21-26.png)
        
        C. Review the new subnet
        
        ![Deploy Bastion02_2025-06-04 16-22-28.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion02_2025-06-04_16-22-28.png)
        
        D. Virtual network as in topology tab
        
        ![Deploy Bastion03_2025-06-04 16-23-47.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion03_2025-06-04_16-23-47.png)
        
        E. Navigate to Marketplace and search Bastion
        
        ![Deploy Bastion04_2025-06-04 16-27-53.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion04_2025-06-04_16-27-53.png)
        
        F. Install it or create 
        
        ![Deploy Bastion05_2025-06-04 16-28-34.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion05_2025-06-04_16-28-34.png)
        
        G. Create Bastion instance with following detail in the picture
        
        ![Deploy Bastion06_2025-06-04 16-32-25.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion06_2025-06-04_16-32-25.png)
        
        H. Review + create bastion instance
        
        ![Deploy Bastion07_2025-06-04 16-32-57.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion07_2025-06-04_16-32-57.png)
        
        I. Wait for Bastion to complete and can find it within the dashboard resources
        
        ![Deploy Bastion08_2025-06-04 16-36-26.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion08_2025-06-04_16-36-26.png)
        
        ![Deploy Bastion09-2025-06-04 16-43-25.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Deploy_Bastion09-2025-06-04_16-43-25.png)
        
    - Create an Ubuntu Server Virtual Machine
        
        A. Install an Ubuntu Server 22.04 LTS. Search it within the Marketplace
        
        ![Ubuntu Server00_2025-06-04 16-45-29.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server00_2025-06-04_16-45-29.png)
        
        1. Ubuntu Server in the marketplace
        
        ![Ubuntu Server01_2025-06-04 16-46-22.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server01_2025-06-04_16-46-22.png)
        
        B. Create a virtual machine with the following detail:
        
        ![Ubuntu Server02_2025-06-04 17-09-36.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server02_2025-06-04_17-09-36.png)
        
        b. pick your ssh username for ssh login later
        
        ![Ubuntu Server04_2025-06-04 17-17-23.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server04_2025-06-04_17-17-23.png)
        
        C. pick the your hard disk capacity or just follow the picture
        
        ![Ubuntu Server04_2025-06-04 17-19-39.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server04_2025-06-04_17-19-39.png)
        
        D. populate the Networking tab with the following settings
        
        ![Ubuntu Server04_2025-06-04 17-20-58.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server04_2025-06-04_17-20-58.png)
        
        d. Review and create
        
        ![Ubuntu Server04_2025-06-04 17-23-36.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server04_2025-06-04_17-23-36.png)
        
        E. Download private key and create  resource
        
        ![Ubuntu Server05_2025-06-04 17-25-37.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Ubuntu_Server05_2025-06-04_17-25-37.png)
        
    - Install Nextcloud by connecting via SSH using Bastion
        
        A. Top level view from Virtual network topology
        
        ![Install Nextcloud00_2025-06-04 17-33-37.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud00_2025-06-04_17-33-37.png)
        
        B. Navigate to the Overview tab
        
        ![Install Nextcloud01_2025-06-04 17-37-36.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud01_2025-06-04_17-37-36.png)
        
        C. Connect to Virtual machine via Bastion
        
        ![Install Nextcloud02_2025-06-04 17-38-28.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud02_2025-06-04_17-38-28.png)
        
        D. Enter your credential, tick the SSH, enter your username and load the ssh key file.
        
        ![Install Nextcloud03_2025-06-04 17-39-52.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud03_2025-06-04_17-39-52.png)
        
        ![Install Nextcloud04_2025-06-04 17-41-03.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud04_2025-06-04_17-41-03.png)
        
        E. While in terminal enter the following command:
        
        ![Install Nextcloud05_2025-06-04 17-43-44.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud05_2025-06-04_17-43-44.png)
        
        ![Install Nextcloud06_2025-06-04 17-49-05.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud06_2025-06-04_17-49-05.png)
        
        ![Install Nextcloud07_2025-06-04 17-51-14.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud07_2025-06-04_17-51-14.png)
        
        ![Install Nextcloud08_2025-06-04 17-52-08.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Install_Nextcloud08_2025-06-04_17-52-08.png)
        
        ```bash
        sudo snap install nextcloud -y
        
         sudo nextcloud.manual-install admin next123
         
         sudo nextcloud.enable-https self-signed
         
         exit
         (to reset your admin password, below:)
         sudo nextcloud.occ user:resetpassword admin
         or
         sudo -u www-data php /var/www/nextcloud/occ user:resetpassword admin
        ```
        
    - Publish an IP
        
        A. Navigate to Network Interface and select overview
        
        ![Publish an IP00_2025-06-04 17-54-43.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP00_2025-06-04_17-54-43.png)
        
        B. Navigate to Network settings | Edit IP configuration and fill in the items
        
        ![Publish an IP01_2025-06-04 18-04-19.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP01_2025-06-04_18-04-19.png)
        
        b. Overview of your IP config
        
        ![Publish an IP02_2025-06-04 18-06-00.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP02_2025-06-04_18-06-00.png)
        
        C. Navigate to Virtual machine | Network settings and add your own IP for the source IP then follow the rest of the config
        
        ![Publish an IP03_2025-06-04 18-14-28.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP03_2025-06-04_18-14-28.png)
        
        c. Extended config area before add.
        
        ![Publish an IP04_2025-06-04 18-14-53.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP04_2025-06-04_18-14-53.png)
        
        D. Browse your VM IP
        
        ![Publish an IP05_2025-06-04 18-17-12.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP05_2025-06-04_18-17-12.png)
        
        E. The preview of your Nextcloud inside the virtual machine. This section is complete.
        
        ![Publish an IP05_2025-06-04 18-17-57.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/Publish_an_IP05_2025-06-04_18-17-57.png)
        
    - Create a DNS label
        
        A. Head back to Virtual machine overview
        
        ![DNS label00_2025-06-04 18-19-23.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label00_2025-06-04_18-19-23.png)
        
        1. Review the topology around the virtual network.
        
        ![DNS label00_2025-06-04 18-22-36.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label00_2025-06-04_18-22-36.png)
        
        B. Click and navigate to VMIP_Nextcloud
        
        ![DNS label01_2025-06-04 18-28-06.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label01_2025-06-04_18-28-06.png)
        
        b. Navigate to Configuration tab within the VMIP and set your DNS nale label
        
        ![DNS label02_2025-06-04 18-29-36.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label02_2025-06-04_18-29-36.png)
        
        C. While within your Virtual network | Topology > VMIP overview. take notes of your config and DNS name.
        
        ![DNS label03_2025-06-04 18-31-49.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label03_2025-06-04_18-31-49.png)
        
        D. Relog to your ssh via Bastion
        
        ![DNS label04_2025-06-04 18-32-34.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label04_2025-06-04_18-32-34.png)
        
        E. While in terminal enter the following commands as below in the picture:
        
        ![DNS label05_2025-06-04 18-36-47.png](Azure%20Create%20a%20Virtual%20Machine%20and%20Deploy%20a%20Web%20Se%202072507911e9805d9c1dfafa0f8e7c2c/DNS_label05_2025-06-04_18-36-47.png)
        
        example of bash commands below:
        
        ```bash
        sudo nextcloud.occ config:system:set trusted_domains 1 --value=lebibutsenextcloud.eastus.cloudapp.azure.com
        
        exit
        ```
        
    
    Thanks for viewing this simple security project regarding Nextcloud now you have good basic understanding about network security and Azure cloud knowledge. This is the way!
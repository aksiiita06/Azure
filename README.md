# SAP INFRASTRUCTURE AS A CODE. 
These are ARM json templates build to quickly deploy an SAP Infra.

SAP-RHEL-DISK-INSTALL.json will build you SAP RHEL VM, with its own Vnet, NSG, public ip, credentials (ps1adm), and /sapmnt /usr/sap as separate disks. 
It wouldn't ask for any parameters as values is coded in it. 

Key Idea here is to create a quick deployment template i.e. Have an SAP VM ready in just 5 minutes!

Disk-from-snapshot json will create snapshots of the disks.
Again it wouldn't ask for any paramets as the values are coded inside it. 

VM-Clone-RHEL-SAP-2-BACKUP will clone the VM created earlier and create another VM within the subnet. 

P.S.: The code has been written from Hewlett Packard Laptop, and by a Hewlett Packard employee (Yours Truly!). So the Organization is the rightful owner of these codes. That being said, use it as long as you want.  



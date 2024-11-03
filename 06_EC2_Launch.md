## Laundhing EC" Instance

Stepa:

1. Select an EC"-Instance Type. 

Insance Type defines the Hardware Profile costs. 



2. Selct an AMI:

AMI Defiens Os to use. Some AMIs have peer installed software on them. 

AMI s are backed by EBS Snapshots. actual data of an EC2 stored in a EBS snapshot.
Snapsot are actually taken from live instane  as a kind of backup.

 So a snapsho is a point in time backup an instnce.

 We can customize out own AMI. 

 3. EC2 --> Launch Instance -->   

 ![EC2_1](images/EC2_1.png)  

- Name:   

![EC2_2](images/EC2_2.png) 

- AMI:  

![EC2_3](images/EC2_3.png) 


- Instance Type:  

![EC2_4](images/EC2_4.png)  

- Keypair:  

![EC2_5](images/EC2_5.png) 

- Network Setting;  

![EC2_6](images/EC2_6.png) 

- Netowrk:  

- Subnet:  

- Auto Asiign IP:  

- Firewall (Security Group):  

- Configue Storage: 8GB  
- Advanced Details:  

![EC2_7](images/EC2_7.png) 
    --->>> Launch Isntance 

    *We can see the informations by clicking on the instance.*


### Informations Tabs for an EC2:

![EC2_8](images/EC2_8.png) 

- Details  

![EC2_9](images/EC2_9.png) 


- Status and Alarm  

![EC2_10](images/EC2_10.png) 

- Monitoring  

![EC2_11](images/EC2_11.png) 

- Security  

![EC2_12](images/EC2_12.png) 

- Networking  
![EC2_13](images/EC2_13.png) 
- Storage  
![EC2_14](images/EC2_14.png) 
- Tags  
![EC2_15](images/EC2_15.png) 

---


## Launching Windows Server

The chritical settings here are:  

- selecht as AMI of Windows Server
![EC2_16](images/EC2_16.png)   

- select always a key pair.
- set n Security Group that enable RDP.  Because connecting an Windows server is just over Remote Desktop Protocol. RDP from Port 3389
![EC2_17](images/EC2_17.png)   
### Dom Heallis 040728287
### Lab 2

# Task 1 - Create policy and attemp to create a resource in difference region (im using resource group CST8911 - lab1, that's what i assigned the policy through and didn't want to restart)

created policy
![alt text](image.png)

trying to deploy a vnet outside of canada central
![alt text](image-1.png)

# Task 2 - Create a VNet

![alt text](image-2.png)

deployment complete
![alt text](image-3.png)

# Task 3: Create Subnets & Enable Storage Service Endpoint

private subnet configs
![alt text](image-4.png)

public subnet configs
![alt text](image-5.png)

# Task 4: Create Network Security Group (NSG)

configs for nsg
![alt text](image-6.png)

associating nsg to private subnet
![alt text](image-7.png)

# Task 5: Configure NSG Rules (Private Subnet)

allow azure storage
![alt text](image-8.png)

deny internet rule
![alt text](image-9.png)

both created
![alt text](image-10.png)

# Task 6: Configure NSG for Public Subnet (RDP Access)

creating new nsg for public subnet
![alt text](image-11.png)

adding inbound rule
![alt text](image-12.png)

associating to public subnet
![alt text](image-13.png)

# Task 7: Create a Storage Account with File Share

configs for storage account with private subnet
![alt text](image-14.png)

![alt text](image-15.png)

creating file share
![alt text](image-16.png)

# Task 8: Deploy Virtual Machines

creating private vm
![alt text](image-17.png)

public vm
![alt text](image-18.png)


# task 9: private vm Tests

private vm remapping to Z
![alt text](image-19.png)

# task 10: public vm test
access denied on public vm
![alt text](image-20.png)

EVERYTHING DELETED
![alt text](image-21.png)
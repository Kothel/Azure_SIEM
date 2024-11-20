# Azure_SIEM

# <h1>Azure SIEM Lab
  
  
## <a>Walkthrough </b>
###  1. First create honeypot VM
  - ![image](https://github.com/user-attachments/assets/9ccf1de9-4e13-4f3c-a5ae-de59a1a1501e)
  - Make a firewall rule to allow all traffic through the vm
  - ![image](https://github.com/user-attachments/assets/be0f9503-98f3-438e-a1bc-46f8bcdef049)




###  2. Create the log analytics workspace
  - ![image](https://github.com/user-attachments/assets/1b8b3589-7847-4054-8ab4-ab998dee25fd)
  - disable sql server on honeypot
  - ![image](https://github.com/user-attachments/assets/0b974116-1e33-490e-80bc-9bf79762ba21)
  - collect all events
  - ![image](https://github.com/user-attachments/assets/b532966b-62c5-4c80-9439-0a07ed0a578c)
  - connect log analitics to vm
  - ![image](https://github.com/user-attachments/assets/da737bee-3094-4dd0-9360-66fcf1163cd7)




###  3. configure VM
 
  - ![image](https://github.com/user-attachments/assets/6279178e-7f77-448e-9c59-db8ab148825f)
  - Remote desktop in
  - ![image](https://github.com/user-attachments/assets/e9b65552-4d97-44c2-b95a-4ba612848f45)
  - ![image](https://github.com/user-attachments/assets/df97edb4-1189-43b6-b26f-03308dec7ab3)
  - turn off window firewall
  - ![image](https://github.com/user-attachments/assets/4bdd9c08-5dda-40c7-a8e5-a18fa13dfb5e)
  - can ping




    - no Default gatway is asigned because the machine will act as the gatway to the network for itself
    - similar to the default gateway this server will act as the DNS server for the network so I will use the loopback adress

  ### 4. add own domain 
  - ![image](https://github.com/user-attachments/assets/b11ffb6d-2ab9-4b2b-8f68-6a5e26eaaede)
    - add an admin acount to domain
    - ![image](https://github.com/user-attachments/assets/2a48cc45-b551-4c97-88aa-b927cfef39c5)
 




 ### 5. Add RAS / NAT
  - ![image](https://github.com/user-attachments/assets/7175e4d3-7e82-4cf6-a2db-a921f977e1ff)
    - will allow clients on internal network to acess internet through the DC





  ### 6. Add DHCP
  - 
    - set range of DHCP to 172.16.0.100-200
    - ![image](https://github.com/user-attachments/assets/25a5582b-3aae-4e18-a810-51c999ba92a9)
  





  ### 7. use a script to add users to domain
  - ![image](https://github.com/user-attachments/assets/cdade551-344f-4b41-a961-8780b162e35f)

  - ![image](https://github.com/user-attachments/assets/a99fb347-ed46-4cf4-b131-de24eb8802e9)

  - ![image](https://github.com/user-attachments/assets/9c78b28a-f485-4818-8004-c6983c7f8f1e)




 ### 8. Connect client to the server in an internal network
   - ![image](https://github.com/user-attachments/assets/8030bc12-32f3-4678-aa36-8a664cc9316a)
   - ![image](https://github.com/user-attachments/assets/66533f4e-380e-41d4-9b6a-5945fa56a767)




 ### 9. Client Lease shows up in DHCP
   - ![image](https://github.com/user-attachments/assets/1062d56b-e67c-4c3c-90db-45cc23896615)
   - 



  ### 10. Users created with script work
  - ![image](https://github.com/user-attachments/assets/cd849ca1-60f5-4d2d-82be-aca7f98c487e)


# Active_Directory_Environment

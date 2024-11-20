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
  - ![image](https://github.com/user-attachments/assets/b9c305d4-56c5-4275-a332-2597853b8e75)
  - write and run script that extracts location data from event log into a txt file
  - 





    - no Default gatway is asigned because the machine will act as the gatway to the network for itself
    - similar to the default gateway this server will act as the DNS server for the network so I will use the loopback adress

  ### 4. Logs
  - ![image](https://github.com/user-attachments/assets/aa79257a-fc65-4cc9-b5cb-39a382ac8dd5)
  - copy custome log from vm
  - ![image](https://github.com/user-attachments/assets/b4d04f4a-5f1c-4b19-809b-ffa6fd0d7af0)
  - put log in log analisis
  - ![image](https://github.com/user-attachments/assets/6d6465de-3730-491c-9fc2-ce03f8bae7ba)
  - ![image](https://github.com/user-attachments/assets/e80118b7-8695-4601-895d-6a4b72e06d03)







 ### 5.Final map
  - ![image](https://github.com/user-attachments/assets/7175e4d3-7e82-4cf6-a2db-a921f977e1ff)
  - after 24 hours


# SIEM_HONEYPOT_LAB

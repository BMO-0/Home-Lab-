# Configure Shared Network Folders 

## Objective

Make shared folders on DCO1 to make it seem like a company

----

## Environment
VM: DCO!
Server Name: DC01
Operating System: Windows Server 2022 Evaluation

##Steps
1. Make a folder in the C:\ Drive and name it shared.
2. Right-click a folder → Properties → Sharing → Advanced Sharing.
3. Enable sharing and assign permission and choose who you want to be able to access the folder.
4. If that works and client computer has access to the folder, make 4 others files (IT, HR, Finance and Sales).
5. For these folders when sharing them allows the only corresponding security groups access to that folder.
6. Log in to users from different groups and see if they have access to the folders 

----

## Result
The correct user have access to the correct folder.

## Screenshot

<img width="1577" height="827" alt="image" src="https://github.com/user-attachments/assets/bfb11f7a-c630-4e26-af09-98007befb657" />

The folder sharing settings.

<img width="1032" height="805" alt="image" src="https://github.com/user-attachments/assets/3d22b93f-245d-4e74-9a94-4cf39f23ade4" />
<img width="1042" height="817" alt="image" src="https://github.com/user-attachments/assets/3d4365f9-e860-4173-b938-75b46882aac6" />
<img width="1027" height="807" alt="image" src="https://github.com/user-attachments/assets/4a125763-bb40-4f1e-aefd-46e87787c1e2" />
<img width="1036" height="820" alt="image" src="https://github.com/user-attachments/assets/66537447-6f4e-4dcb-95c8-936766d39200" />





User6 is not in IT Support group so it does not share this folder (image below).
<img width="1067" height="810" alt="image" src="https://github.com/user-attachments/assets/923ebb48-4bf2-4898-8da0-a024e4314a2b" /> 
User1 is in IT Support group so this files shares (image below).
<img width="1060" height="812" alt="image" src="https://github.com/user-attachments/assets/aaf77541-adbe-4c17-9cd5-9015fd4ee836" />
User1 can’t access the Finance Folder (image below).
<img width="1032" height="812" alt="image" src="https://github.com/user-attachments/assets/af6fe981-f33e-4059-a332-466c13dc19b7" />





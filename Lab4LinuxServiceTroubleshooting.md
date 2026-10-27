Linux Service Truobleshooting
Objective is to diagnose a failed Linux Service

<img width="405" height="43" alt="image" src="https://github.com/user-attachments/assets/392706ff-9d23-4e41-9fcc-f56c82359c8d" />

Step 1 - Check the service

<img width="785" height="139" alt="image" src="https://github.com/user-attachments/assets/6fc2a22c-d982-4c9c-a7d8-41e33bb11f92" />

Step 2 - Read the service logs

<img width="327" height="109" alt="image" src="https://github.com/user-attachments/assets/f72701e3-f463-400e-ae49-36a6cfb16adf" />

Step 3 - Inspect the service's configuration


<img width="413" height="20" alt="image" src="https://github.com/user-attachments/assets/7c7088a9-6a76-44ad-b7ef-7ab8c654bf50" />

Step 4 - Identify the error if there is any

Step 5 - Check whether the executbale exists


<img width="659" height="25" alt="image" src="https://github.com/user-attachments/assets/bd88a121-91ca-4f56-833c-5a2deb1cf3bb" />

Step 6 - Inspect the configured startup command

Step 7 - Review the findings
The service failed because its configured executbale did not exist. The next thing to troubleshoot would be the 'ExecStart path to a valid program, rather than restsrting the service several times over

<img width="574" height="73" alt="image" src="https://github.com/user-attachments/assets/a0727407-5c80-4634-bd31-7b8edc84e096" />
 
 Step 8 - Open the service configuration

 <img width="379" height="198" alt="image" src="https://github.com/user-attachments/assets/a28bea20-8a88-4d51-846b-0625c663a85d" />

 Step 8A - Find the broken line, fix it, then save and exit nano editor

 <img width="496" height="30" alt="image" src="https://github.com/user-attachments/assets/b808c326-e022-46bd-8bef-3f7e43ef6edb" />

 Step 9 - Reload the service configuration. This command tells systemd to read your changes

 <img width="656" height="42" alt="image" src="https://github.com/user-attachments/assets/3ed6efff-e607-4ff5-870e-0738e39b29f5" />

<img width="597" height="30" alt="image" src="https://github.com/user-attachments/assets/09bc0dc8-a400-4828-87ab-e56da7623d17" />

Step 10 - Clear the failure 

<img width="720" height="187" alt="image" src="https://github.com/user-attachments/assets/9f69fa46-5c4d-4107-8992-54337cad2526" />

Step 11 - Verify that it works( It shiuld say active running)

<img width="1224" height="239" alt="image" src="https://github.com/user-attachments/assets/227be20f-be67-483f-bfb2-496d04da85df" />

Step 12 - Check the service logs

Lab complete














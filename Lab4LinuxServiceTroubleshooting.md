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







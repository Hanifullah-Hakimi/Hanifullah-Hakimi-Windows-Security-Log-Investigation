# Windows Security Log Investigation Lab

## Overview
I used Windows Event Viewer to create a test event and investigate Windows Security logs. The goal was to understand authentication events and practice basic SOC investigation techniques.

## Tools Used
- Windows Event Viewer
- Windows Security logs
- Windows PowerShell
- Task Manager

## Activities Performed
- Created a test event in the Windows Application log.
- Examined Security Event ID 4624 (successful logon).
- Investigated Event ID 4625 (failed logon).
- Reviewed Event ID 4634 (logoff).
- Examined logon types, timestamps, account fields, source address, and caller process information.

## Findings
One failed-logon event (4625) was examined. It showed Logon Type 2, source address 127.0.0.1, and caller process `C:\Windows\System32\svchost.exe`.

## Conclusion
The available evidence was insufficient to classify the failed logon as malicious. The event demonstrated the importance of examining authentication details and related activity before reaching a security conclusion.

## Skills Learned
- Navigating Windows Event Viewer
- Interpreting Windows Security Event IDs
- Understanding Windows logon types
- Examining authentication failures
- Writing evidence-based investigation conclusions

Screenshots: <img width="1542" height="822" alt="image" src="https://github.com/user-attachments/assets/eb2109fb-af46-4e63-a9f6-772564b1ec1c" />

<img width="952" height="557" alt="image" src="https://github.com/user-attachments/assets/6bc3c6c0-6c96-4c1c-9617-b192115923df" />


<img width="1772" height="812" alt="image" src="https://github.com/user-attachments/assets/999e43c6-df46-47b8-a0cd-c0dab82feab4" />






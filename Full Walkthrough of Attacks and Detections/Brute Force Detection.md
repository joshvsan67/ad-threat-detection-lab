# Brute Force

## Hydra
Decided to use hydra for this since crowbar was not cooperating with me on RDP brute forces.

<img width="638" height="465" alt="Brute Force Attack" src="https://github.com/user-attachments/assets/27b6fd3a-7a54-4213-86bb-d99622ce6f58" />

<img width="635" height="470" alt="Success!" src="https://github.com/user-attachments/assets/6bd79ef6-59b0-4e87-a2c3-b51a3b2285e7" />

Eventually a success!


## Splunk Event Logs
Query: index=* (EventCode=4624 OR EventCode=4625) host="Bruce-Wayne-PC"
<img width="1920" height="534" alt="Splunk query" src="https://github.com/user-attachments/assets/ac8d353a-e589-414f-94c5-30a9b9b69d47" />

Event Logs:
<img width="1892" height="880" alt="Splunk Event Logs" src="https://github.com/user-attachments/assets/198023a2-d73b-4a92-b905-40448fd94246" />
Showing a bunch of 4625 Windows Event IDs and eventually has a successful 4624 event id logon.


Looking further into the log...
<img width="517" height="167" alt="Splunk Kali Source Hostname" src="https://github.com/user-attachments/assets/f55f9347-f790-4220-9438-77bd3d9a8c50" />

Consistent with kali workstation name and source network address of 192.168.10.250.

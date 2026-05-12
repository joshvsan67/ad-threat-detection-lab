# System Configuration and Network Discovery (T1016)

Running Atomic Red team on this attack (very useful tool for generating attacks). 

<img width="509" height="183" alt="T1016 - Discovery using command line" src="https://github.com/user-attachments/assets/9d6b7bed-6a68-43ed-a617-998e14781ad9" />

Probably a nice progression after getting brute-forced, the attacker starts configuration and network discovery once it gets control of the CLI.

## Invoking the command...

<img width="983" height="606" alt="Atomic" src="https://github.com/user-attachments/assets/6b3f0e03-e4b9-47fe-8b60-b4a1bf8e62b7" />

<img width="533" height="723" alt="Atomic 2" src="https://github.com/user-attachments/assets/55509904-c9b9-4d59-aa01-b73b68b2266c" />

Doing a lot of commands!

## MITRE Attack Framework for T1016

<img width="1907" height="911" alt="MITRE Attack Framework" src="https://github.com/user-attachments/assets/03447e3b-10a7-4d79-9852-b01a19930f0b" />

## Splunk Queries and Logs

index=* host="Bruce-Wayne-PC" (whoami.exe OR ipconfig.exe OR nslookup.exe OR netstat.exe)  ProcessID="'3144'"
<img width="1905" height="915" alt="Better query" src="https://github.com/user-attachments/assets/2bdde8ad-d58c-40c9-b48b-256a19d70537" />

<img width="1634" height="233" alt="DNS Server Discovery" src="https://github.com/user-attachments/assets/f9225bfa-5da8-451b-98eb-a2ab65772dc3" />

<img width="1624" height="257" alt="image" src="https://github.com/user-attachments/assets/d01e3982-df59-4863-8fd4-8acf170b0b7d" />




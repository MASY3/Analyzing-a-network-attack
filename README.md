# Analyzing-a-network-attack
Tasked with analyzing an alert from our monitoring system indicating a problem with the web server. 
In this project I was tasked with using a packet sniffer to capture data packets in transit to and from the web server. I noticed a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. I suspect the server is under attack by a malicious actor. 

I took the server offline temporarily so that the machine can recover and return to a normal operating status. I also configured the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. I knew that our IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. I needed to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. Also that I would need to inform my lead of this issue. 

green	Normal TCP connection handshakes	---,
red	Attack activity		---,
yellow	Normal TCP connections failing due to attack		

attached you will find an incident report and tcp/ip logs

![image](https://github.com/MarcoSantibanez/Analyzing-a-network-attack/assets/138132151/f5753aa3-84d9-49f9-96a9-ef63a51622f9)

![image](https://github.com/MarcoSantibanez/Analyzing-a-network-attack/assets/138132151/f1209c71-fd29-4498-a53d-f29172b5bb7b)

![image](https://github.com/MarcoSantibanez/Analyzing-a-network-attack/assets/138132151/1fdd41aa-346e-47ec-96f6-e79a85d7bd1c)

![image](https://github.com/MarcoSantibanez/Analyzing-a-network-attack/assets/138132151/fd9d7bfd-c8b2-48b4-9f89-7d4bf9a4181f)

![image](https://github.com/MarcoSantibanez/Analyzing-a-network-attack/assets/138132151/47185ce5-c965-492a-ac07-83f6b630e871)



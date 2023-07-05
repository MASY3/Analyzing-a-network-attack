# Analyzing-a-network-attack
Tasked with analyzing an alert from our monitoring system indicating a problem with the web server. 
In this project I was tasked with using a packet sniffer to capture data packets in transit to and from the web server. I noticed a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. I suspect the server is under attack by a malicious actor. 

I took the server offline temporarily so that the machine can recover and return to a normal operating status. I also configured the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. I knew that our IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. I needed to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. Also that I would need to inform my lead of this issue. 

green	Normal TCP connection handshakes	---	
red	Attack activity		---
yellow	Normal TCP connections failing due to attack		

attached you will find an incident report and tcp/ip logs

# Nmap-Detection
I have performed nmap detection on my local host network and saved the results to a html file 

First scanned the internal network and the image is provided as 1.png

Second i have done scanned the local ip and saved the result in xml file and converted it to html file as shown in 2.png.

Therefore, here are the potential risks and common services running on these ports:
   1.Port 53/tcp: The scan identifies the domain name system and the potential risks are DNS Spoofing, DDoS Amplification, Info Leakage.
   2.Port 135/tcp: Identifies Microsoft Remote Procedure Call which allows applications to communicate and request services from other computers on the same                           network.
                    Potential risks are Reconnaissance and Remote Code Execution.
   3.Port 139/tcp: NetBIOS used for sharing giles and other resouces in a lan and potential risks are data exposure, user enumeration, etc.
   4.Port 445/tcp: SMB operates directly over TCP/IP used for windows file sharing, remote service access, etc and potential risks are ransomware propogation,                         credential theft, etc.

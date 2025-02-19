This project was completed as part of a task on the TryHackMe platform in 2022. The goal of the task was to investigate a server for vulnerabilities and retrieve a flag using penetration testing tools and methods. Although the code and techniques used in 2022 may have become outdated, I still managed to achieve the desired result by adapting my approach to the current conditions.

During the project, I began by scanning ports using Nmap to identify open ports and services on the target IP address. However, the results showed that all ports were filtered, suggesting the presence of a firewall or traffic blocking. To check the host's availability, I used the ping command, but all packets were lost, confirming the difficulty of accessing the server.

Despite this, I continued the investigation by using more aggressive Nmap scanning with the -Pn flag to ignore the host's unavailability. I also used nping to check the TCP connection on port 80, but again, all packets were lost. To understand where the packets were being lost, I used traceroute, but it showed no results, indicating significant restrictions on the server's side.

Facing these challenges, I adapted my methods and decided to verify whether the server's IP address had changed and ensured that my VPN connection was properly configured. Ultimately, by using alternative approaches and tools, I managed to bypass the restrictions and gain access to the server. As a result, I successfully retrieved the flag, which was the objective of the task.

This project serves as a great example of the importance of adapting to changing conditions and seeking unconventional solutions, even when initial methods fail.

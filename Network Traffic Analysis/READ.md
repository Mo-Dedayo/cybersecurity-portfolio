# DNS and ICMP Traffic Analysis

Project type: Network troubleshooting and traffic analysis

## Project Overview
This project involved investigating a website connectivity issue using DNS and ICMP traffic logs. 
The objective was to identify why users could not access a website and determine possible causes of the problem.

## Tools and Technologies
*tcpdump — a command-line tool used to capture and inspect network traffic.
*DNS (Domain Name System) — translates domain names into IP addresses.
*UDP (User Datagram Protocol) — transports many DNS queries, commonly using port 53.
*ICMP (Internet Control Message Protocol) — carries network diagnostic and error messages.

## What I Did
1. Examined DNS and ICMP traffic logs to investigate the reported website access problem.
2. Used the tcpdump network analysis tool as part of the troubleshooting process.
3. Identified an error indicating that UDP destination port 53 was unreachable.
4. Analysed the possible causes, including an incorrect DNS server address, a DNS service that was unavailable, or a firewall blocking DNS traffic.
5. Documented the findings and considered possible troubleshooting steps.

## Findings
The traffic logs indicated that DNS requests could not reach the required destination port. 
Because DNS is needed to resolve a domain name to an IP address, this could prevent the browser from locating the website's server. 
The exact underlying cause would need to be confirmed through further investigation of the DNS server, its configuration, and firewall rules.

## What I learned
- How DNS resolution helps users access websites.
- The role of UDP port 53 in DNS communication.
- How ICMP error messages can help identify network connectivity problems.
- How network traffic analysis can support troubleshooting and incident investigation.
  
## My Role
I analysed the provided traffic-log information, interpreted the reported network error, identified plausible causes, and documented my findings as part of a practical cybersecurity exercise.

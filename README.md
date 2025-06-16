# Bug-Bounty-FootPrinting-Scanning-
FootPrinting &amp; Scanning - Bug Bounty Program training

# FootPrinting & Scanning – Bug Bounty (HackerOne)

This project documents the entire **Footprinting and Scanning** phase during authorized security testing of a target domain in a Bug Bounty program on HackerOne.


**Activity Type:** OSINT, Passive & Active Footprinting + Port Scanning  
**Target:** `truck-api.eu-east-1.indriverapp.com`  
**Environment:** Bug Bounty – HackerOne | "In Scope" & "Critical"

## Goal:

The main goal was to collect publicly available information, identify open ports, services, technologies, and assess the target"s level of protection.

## Tools Used:

1. `WHOIS, DIG, NSLOOKUP, HOST, theHarvester`
2. `WHATWEB, WAFW00F`
3. `Nmap`
4. `Curl (HTTP headers)`
5. `FFUF (Directory bruteforce)`

## HackerOne Rules Followed:

1. No DoS/DDoS, shell access, or unauthorized data access
2. Limited number of requests (≤ 5 threads, delay ≥ 0.2s)
3. Testing only within allowed domains

## Results:

1. Domain is protected via **Amazon CloudFront CDN + WAF**
2. Open ports: `80` (HTTP); `443` (HTTPS)
3. No vulnerable endpoints were discovered
4. Domain has strong security and proper configuration

## Acces to the project:

[FootPrinting & Scanning.pdf](./FootPrinting%20&%20Scanning.pdf)

## 🧑‍💻 Author

Bc. Peter Mulik **(mulcb0t)**

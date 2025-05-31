# Sublist3r - Subdomain Enumeration Tool #
Sublist3r is a Python-based tool designed to enumerate subdomains of websites using OSINT. It helps in reconnaissance for penetration testing and bug bounty hunting.

## 📌 Features ##
Fast and lightweight

Uses multiple search engines and services

Supports multithreading

Can save results to a file

Optional bruteforce support

## ⚙️ Installation ##
```
git clone https://github.com/aboul3la/Sublist3r.git 
cd Sublist3r
pip install -r requirements.txt
```
## Uses ##
``` python3 sublist3r.py -d example.com ```
## For Example ##

```python3 sublist3r.py -d example.com -t 20 -o subdomains.txt ```

## 📚 Sources Used ##
Sublist3r gathers subdomains from:

Google

Yahoo

Bing

Baidu

Ask

Netcraft

Virustotal

ThreatCrowd

DNSdumpster

SSL Certificates

PassiveDNS

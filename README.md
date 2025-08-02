# Nginx Log Analyzer

A simple shell script to analyze Nginx access logs directly from the command line. This project is great for practicing basic Linux shell scripting skills using tools like `awk`, `sort`, `uniq`, and `head`.

---
##  Features

The script analyzes a given Nginx access log and outputs:

-  Top 5 IP addresses with the most requests
-  Top 5 requested paths
-  Top 5 response status codes
-  Top 5 user agents

---
##  Requirements

- Bash (run with Git Bash, Linux terminal, or WSL)
- Tools: `awk`, `sort`, `uniq`, `head`
- An Nginx log file (included: `sample-nginx-log.log`)
---
##  Usage

1. **Clone the repository**

```bash
git clone https://github.com/your-username/nginx-log-analyzer.git
cd nginx-log-analyzer

## output https://roadmap.sh/projects/nginx-log-analyser

Top 5 IP addresses with the most requests:
      5 }
      3 margin:
      3 <meta
      3
      2 width:

Top 5 most requested paths:
     43
      1 or
      1 illustrative
      1 "Open

Top 5 response status codes:
     43
      1 in
      1 for
      1 "Helvetica

Top 5 user agents:
     45
      1 Helvetica Neue

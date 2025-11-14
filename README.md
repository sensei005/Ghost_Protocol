# Ghost_Protocol

## About
- This repository documents my practical journey as a Security Engineer.  
- It is a living log of my cybersecurity journey: labs, writeups, experiments, and the receipts that I actually did the work.  

## Contents
- Daily/weekly logs
- Hands-on labs
- Writeups & reflections
- Certifications progress

## Labs & Practice Environments

### OWASP Juice Shop 

– Installed and configured vulnerable web app for hands-on web pentesting practice.
- run nmap scan on lab ip on port:3000 and uploaded the output 'nmap_recon.txt' in 'recon_juice_shop'
- run ffuf (web fuzzing tool) to find hidden directories, endpoint, parameters using common wordlists by replacing 'FUZZ' and saved the output in 'ffuf_output.json' and uploaded in 'recon_juice_shop': ffuf -u http://10.177.66.159/FUZZ -w /usr/share/wordlists/dirb/common.txt -o ffuf_output.json


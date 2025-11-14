# Recon Summary - Juice Shop
Date: 2025-11-14

## Nmap Findings
- Port 3000 open (Node.js Express)
- Server header reveals Express 4.x
- TLS not configured
- Potential attack surface: /api, /admin

## FFUF Findings
- /api 200
- /ftp 403
- /config 500

## Notes
Likely custom API endpoints.
Next step: Manual inspection with Burp (focus on auth and feedback features).

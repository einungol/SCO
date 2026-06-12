SOC Alert Triage Log
# Alert 1
*Date:12/06/2026
*Alert Title: RDP Brute Force Detected
*Severity: Medium
*Source IP: 218.92.0.56
*Target: 172.16.17.148

*Hypotesis: Try to connect RDP (Remote Desktop Protocal port 3389) with drifferent password 

*Evidence: 
  Source IP is flaggeed as Malicious 
  Failed to logined 2 time
  Successful to login on the third try
*Classification: True positive - Malicious
*Action Taken: Isolatded device, Blocked source IP
*Time to Triag: 10 minutes

# Alert 2
*Date:12/06/2026
*Alert Title: SQL Injection Detected
*Severity: Hight
*Source IP: 118.194.247.28
*Target: WebServer1000

*Hypotesis: Found Injection payload in the http request

*Evidence: 
  Source IP is flaggeed as Malicious 
  SQL injection XSS RCE payload in the request
  
*Classification: True positive - Malicious
*Action Taken: Isolatded device, escalate the case to a Tier II analyst for advanced investigation and remediation.
*Time to Triag: 10 minutes

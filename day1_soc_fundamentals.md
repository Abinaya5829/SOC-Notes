# What is soc?
Security Operation Center.(Continuous monitoring + Detection of threats + Incident response)

The soc Tier structure :
Tier1 - Alert monitoring and reporting
Tier2 - depth investigation of alert 
Tier3 - incident response and recover the threat 

# Alert vs Incident:
*Alert is the notification that something is ubnormal.
*Incident is the confirmed security event after investigation

# Basic SOC workflow:
=> SIEM system generates the alert if any malicious behaviour present.
=> it can analyse the alert from SIEM and validate it compared to historical data.
=> The security event is confirmed and report to the tier3.
=> The SOC team can excute the incident response.
=> final these process are documented.

# Real world example:
cloudflare data breach 
=> It is find out by third party (salesforce).No internal alert was triggerd because it compromised OAuth token.
=> in the investigation of data breach find the OAuth token misuse and access logs from Salesforce was viewed.
=> It denied the compromised OAuth token and full audit of the salesforce log to find out the affected client.




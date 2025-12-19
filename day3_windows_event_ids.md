# System Configuration:
It include the boot(boot log,os boot information,GUI boot), services(it list out all services configured to system),tools(we can launch application) and etc.
In this the attacker may execute hiiden tools ,boots and etc. the evidence are service creation or modification events, boot-related logs, new services running under unusual accounts

# UAC Settings:
The User Account Control was controlled by admin prompts.the UAC disabled and unexpected attempts is malicious.
the evidence is configuration changes related to UAC.

# Registry Editor:
It is a database to store necessary information about users profiles,installed application on computer, documents and hardware devices. registry keys are updated during software installation or system configuration.
The malicious was attackers modify the registry to make malware run automatically after reboot.
The evidence is registry modification in profiles ,startup-related registry keys pointing to unknown files.

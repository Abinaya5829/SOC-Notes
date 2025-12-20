# Linux Authentication:
The authenticated user can log in expected hours.login via SSH from known ip addresses with one or two attempt.
The attacker may try multiple failed attemps to loggin and they login from foreign ip addresses.
The evidence contains authentication logs(/var/log/auth.log (Ubuntu/Debian)),(/var/log/secure (RHEL/CentOS)), 
SSH authentication entries,  sudo usage, and user session activity.

# sudo Usage:
Grants temporary elevated privileges to run administrative tasks.
It is used for system maintenance by authorized user and it is used in business hours.
The attacker used by unauthorized user and unusual commands. it used to disable logging, alter user permissions, 
or access sensitive files. they came from foreign ip addresses.
The evidence was authentication logs from ubntu and fedora(/var/log/auth.log), sudo command execution records. 
User, command, timestamp correlation


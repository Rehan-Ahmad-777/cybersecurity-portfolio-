# Metasploitable2 Bind Shell

## Target
- IP: 192.168.56.102

## Steps

1. Scanned target using nmap
2. Found port 6200 open
3. Connected using netcat:
   nc 192.168.56.102 6200
4. Got shell access

## Result
Successfully obtained bind shell access.

## Learning
Bind shell allows attacker to connect directly to victim's open port.

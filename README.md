# Homelab
This repository is for my homelab project stuff.

I am running Proxmox virtual environment on an old intel i5-based server called P-PRXMX01. 

My primary desktop PC is called P-MGMT01 in this case. 

I have a 600M/200M fiber connection and my network stack is currently:

Primary network:
Cisco ASA5506X + Aruba 6000 switch
Cisco AIR-AP1852I-E-K9 WLAN AP  

Inbetween primary network and proxmox network:
Netgate 1100 PfSense + HP 24 port switch (just for testing purposes, no real need)

Naming conventions:

P = Physica
V = Virtual

V-DC01
V-APP01
V-xxxxx ...



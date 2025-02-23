---
description: Attacking a network
---

# Attacking a network lvl\_1

We're going to build out a local network in virtualbox, set up some malware and do a basic attack.



Tasks:: \
\
Task 1:: \
Download and install [virtualbox](https://www.virtualbox.org/wiki/Downloads) and the [extension pack](https://www.virtualbox.org/wiki/Downloads).\
Download and install [ubuntu](https://ubuntu.com/download/desktop/thank-you?version=24.04.2\&architecture=amd64\&lts=true) and [kali](https://www.kali.org/get-kali/#kali-virtual-machines) VMs on virtualbox\
Name the ubuntu VM "target\_1" and kali "Attack\_box"\
Put both VMs on a virtual network\
\
Task 2::\
Set up a netcat bind on ubuntu and connect to it from kali.\
\
Task 3::\
Create two more ubuntu boxes and name them target\_2 and target\_3\
Set up a python3 bind on target\_2, set up a compiled C program bind on target\_3&#x20;

Task 4::\
Using ssh port forwarding connect to target\_3 through target\_1 and target\_2\
Attack\_Box\
\> target\_1\
\>> target\_2\
\>>> target\_3\
\
Task 5::\
Persist our backdoors with a systemd script on target\_1, a cron job on target\_2, and an anacron job on target\_3\
\
Task 6::\
Use meterpreter (RAT (Remote Access Tool))to connect to target\_3 through target\_1 and target\_2\




\

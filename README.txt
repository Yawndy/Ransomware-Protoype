Libraries Used: argparse, paramiko, time, uuid, pickle, base64, yaml, os, signal, sys, atexit, logzero, threading, socket, io, datetime, cryptography, fernet.

Environmental setup:

Server - Ubuntu 18.04 VM with two NAT interfaces, (192.168.216.148 and 192.168.216.150). Paramiko is listening on 192.168.216.148, and Open-SSH server is listening on 192.168.216.150.

Folders created: 
- "/home/algarcia1/victims"



Instructions:

Run "Server.py" to listen for incoming connections, prompt victim to execute "Run_Me.py". "Ransomware_Protoype.py" will automatically deploy to victim's machine after "Run_Me.py" execution.
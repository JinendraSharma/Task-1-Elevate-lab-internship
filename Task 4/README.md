#  Telnet Access to Windows via KpyM Server

## Overview
This setup enables Telnet access to a Windows host from a Kali Linux client running inside a virtual machine (VM), 
using the KpyM Telnet Server. It’s ideal for testing legacy protocols, remote shell access, and reproducible lab environments.

## Setup
- Install [KpyM Telnet Server](http://www.kpym.com/) on the Windows host
- Ensure port 23 is allowed through Windows Firewall
- Start the KTS (KpyM Telnet Server) service
- Connect from Kali Linux (in VM) using:
- cmd used--
  telnet <windows-ip> 23

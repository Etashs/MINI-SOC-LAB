\# Mini SOC Lab - Day 3



\## Objective



Deploy Wazuh agent and perform attack simulation against Metasploitable2.



\## Components



\- Windows Host

\- Wazuh Manager 4.12.0

\- Wazuh Indexer

\- Wazuh Dashboard

\- Kali Linux VM

\- Metasploitable2 VM



\## Attack Simulation



Target:

Metasploitable2



Service:

UnrealIRCd



Exploit:

exploit/unix/irc/unreal\_ircd\_3281\_backdoor



Result:

Meterpreter session established.



\## Wazuh Agent



Manager IP:

192.168.56.1



Version:

4.12.0



\## Challenges



\- Network unreachable

\- Repository issue

\- GPG key issue

\- Agent version mismatch



\## Resolution



Fixed repository configuration and aligned versions.

